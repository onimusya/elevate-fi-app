# Technical Architecture - Elevate Finance

**Version**: 1.0
**Last Updated**: October 27, 2025
**Status**: Design Phase

---

## Table of Contents

1. [System Overview](#system-overview)
2. [High-Level Architecture](#high-level-architecture)
3. [Component Architecture](#component-architecture)
4. [Data Flow Diagrams](#data-flow-diagrams)
5. [Blockchain Architecture](#blockchain-architecture)
6. [Infrastructure Architecture](#infrastructure-architecture)
7. [Security Architecture](#security-architecture)
8. [Deployment Architecture](#deployment-architecture)

---

## System Overview

Elevate Finance is a multi-tier, blockchain-enabled platform consisting of:

- **Frontend Layer**: Next.js application with Shadcn UI
- **Backend Layer**: Node.js/TypeScript API services
- **Blockchain Layer**: Solana smart contracts (Anchor framework)
- **Data Layer**: NeonDB (PostgreSQL) + Cloudflare KV
- **AI Layer**: Python ML services for investment analysis
- **Infrastructure Layer**: Cloudflare + Vercel edge network

---

## High-Level Architecture

```
┌─────────────────────────────────────────────────────────────────────┐
│                          CLIENT LAYER                                │
├─────────────────────────────────────────────────────────────────────┤
│  Web Browser (Desktop/Mobile)                                        │
│  ┌──────────────────────────────────────────────────────────────┐  │
│  │  Next.js Frontend (React + TypeScript)                        │  │
│  │  • Shadcn UI Components                                       │  │
│  │  • Tailwind CSS Styling                                       │  │
│  │  • WalletConnect Integration                                  │  │
│  └──────────────────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────────────────┘
                              ▼
┌─────────────────────────────────────────────────────────────────────┐
│                        CLOUDFLARE EDGE                               │
├─────────────────────────────────────────────────────────────────────┤
│  • CDN (Static Assets, Images)                                       │
│  • DDoS Protection                                                   │
│  • WAF (Web Application Firewall)                                    │
│  • DNS Management                                                    │
│  • KV Cache (Session, Campaign Data)                                 │
└─────────────────────────────────────────────────────────────────────┘
                              ▼
┌─────────────────────────────────────────────────────────────────────┐
│                       APPLICATION LAYER                              │
├─────────────────────────────────────────────────────────────────────┤
│  ┌──────────────────┐  ┌──────────────────┐  ┌─────────────────┐  │
│  │  API Gateway     │  │  Backend API     │  │  AI Service     │  │
│  │  (Vercel Edge)   │  │  (Node.js/TS)    │  │  (Python)       │  │
│  │                  │  │                  │  │                 │  │
│  │  • Rate Limiting │  │  • Business      │  │  • Campaign     │  │
│  │  • Auth Check    │  │    Logic         │  │    Scoring      │  │
│  │  • Request       │  │  • REST APIs     │  │  • Sentiment    │  │
│  │    Routing       │  │  • WebSockets    │  │    Analysis     │  │
│  └──────────────────┘  └──────────────────┘  └─────────────────┘  │
└─────────────────────────────────────────────────────────────────────┘
                              ▼
┌─────────────────────────────────────────────────────────────────────┐
│                         DATA LAYER                                   │
├─────────────────────────────────────────────────────────────────────┤
│  ┌──────────────────┐  ┌──────────────────┐  ┌─────────────────┐  │
│  │  NeonDB          │  │  Cloudflare KV   │  │  Message Queue  │  │
│  │  (PostgreSQL)    │  │  (Cache)         │  │  (Redis/SQS)    │  │
│  │                  │  │                  │  │                 │  │
│  │  • User Data     │  │  • Session Data  │  │  • Events       │  │
│  │  • Campaigns     │  │  • Campaign      │  │  • Notifications│  │
│  │  • Transactions  │  │    Listings      │  │  • Async Jobs   │  │
│  │  • KYC Records   │  │  • API Cache     │  │                 │  │
│  └──────────────────┘  └──────────────────┘  └─────────────────┘  │
└─────────────────────────────────────────────────────────────────────┘
                              ▼
┌─────────────────────────────────────────────────────────────────────┐
│                      BLOCKCHAIN LAYER                                │
├─────────────────────────────────────────────────────────────────────┤
│                      Solana Blockchain                               │
│  ┌──────────────────────────────────────────────────────────────┐  │
│  │  Smart Contracts (Anchor Framework - Rust)                    │  │
│  │                                                               │  │
│  │  ┌─────────────────┐  ┌─────────────────┐  ┌──────────────┐ │  │
│  │  │ Token Program   │  │ Escrow Program  │  │ Distribution │ │  │
│  │  │ (SPL Token-22)  │  │ (3-of-5 Multisig)│  │ Program      │ │  │
│  │  │                 │  │                 │  │              │ │  │
│  │  │ • Mint Tokens   │  │ • Lock Funds    │  │ • Release    │ │  │
│  │  │ • Transfer      │  │ • Milestone     │  │   Dividends  │ │  │
│  │  │   Restrictions  │  │   Voting        │  │ • Profit     │ │  │
│  │  │ • Lock-up       │  │ • Refunds       │  │   Sharing    │ │  │
│  │  └─────────────────┘  └─────────────────┘  └──────────────┘ │  │
│  └──────────────────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────────────────┘
                              ▼
┌─────────────────────────────────────────────────────────────────────┐
│                     EXTERNAL SERVICES                                │
├─────────────────────────────────────────────────────────────────────┤
│  • KYC/AML: Sumsub, Onfido                                          │
│  • Payments: Stripe (cards), Transak (bank), MoonPay (crypto)       │
│  • Email: SendGrid, Resend                                           │
│  • Monitoring: Sentry, Datadog                                       │
│  • Analytics: Mixpanel, PostHog                                      │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Component Architecture

### Frontend Components

```
┌─────────────────────────────────────────────────────────────────┐
│                    Next.js Application                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              App Router (Next.js 14+)                   │    │
│  │                                                         │    │
│  │  /                 → Landing Page                       │    │
│  │  /campaigns        → Browse Campaigns                   │    │
│  │  /campaigns/[id]   → Campaign Detail                    │    │
│  │  /invest/[id]      → Investment Flow                    │    │
│  │  /portfolio        → Portfolio Dashboard                │    │
│  │  /admin            → Admin Panel                        │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                 UI Components (Shadcn)                  │    │
│  │                                                         │    │
│  │  • Button, Card, Dialog, Dropdown, Form, Table         │    │
│  │  • Charts (Recharts), Data Tables                      │    │
│  │  • Custom: CampaignCard, InvestmentFlow, Portfolio     │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                State Management                         │    │
│  │                                                         │    │
│  │  • React Context (Auth, Wallet)                        │    │
│  │  • React Query (Server State, Caching)                 │    │
│  │  • Zustand (Client State - optional)                   │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              WalletConnect Integration                  │    │
│  │                                                         │    │
│  │  • @solana/wallet-adapter-react                        │    │
│  │  • @solana/wallet-adapter-wallets                      │    │
│  │  • @walletconnect/solana                               │    │
│  │  • Support: Phantom, Solflare, Backpack, Ledger        │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              Blockchain Interaction                     │    │
│  │                                                         │    │
│  │  • @solana/web3.js (RPC calls)                         │    │
│  │  • @coral-xyz/anchor (Smart contract interaction)      │    │
│  │  • Transaction signing and submission                  │    │
│  │  • Balance queries, token transfers                    │    │
│  └────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

### Backend Components

```
┌─────────────────────────────────────────────────────────────────┐
│                  Backend API (Node.js/TypeScript)                │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                   API Routes                            │    │
│  │                                                         │    │
│  │  /api/auth           → Authentication                   │    │
│  │  /api/users          → User Management                  │    │
│  │  /api/campaigns      → Campaign CRUD                    │    │
│  │  /api/investments    → Investment Flow                  │    │
│  │  /api/kyc            → KYC/AML Verification             │    │
│  │  /api/transactions   → Transaction History              │    │
│  │  /api/admin          → Admin Operations                 │    │
│  │  /api/ai             → AI Recommendations               │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                  Middleware Layer                       │    │
│  │                                                         │    │
│  │  • Authentication (JWT validation)                      │    │
│  │  • Rate Limiting (per user, per IP)                    │    │
│  │  • Request Validation (Zod schemas)                    │    │
│  │  • Error Handling (standardized responses)             │    │
│  │  • Logging (structured logs)                           │    │
│  │  • CORS (allowed origins)                              │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                  Service Layer                          │    │
│  │                                                         │    │
│  │  • UserService                                         │    │
│  │  • CampaignService                                     │    │
│  │  • InvestmentService                                   │    │
│  │  • BlockchainService (Solana RPC)                      │    │
│  │  • PaymentService (Stripe, Transak)                    │    │
│  │  • KYCService (Sumsub, Onfido)                         │    │
│  │  • NotificationService (Email, Push)                   │    │
│  │  • CacheService (Cloudflare KV)                        │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                  Data Access Layer                      │    │
│  │                                                         │    │
│  │  • Prisma ORM (NeonDB PostgreSQL)                      │    │
│  │  • Models: User, Campaign, Investment, Transaction     │    │
│  │  • Migrations, Seeding                                 │    │
│  │  • Query optimization, Indexing                        │    │
│  └────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

### AI Service Components

```
┌─────────────────────────────────────────────────────────────────┐
│                    AI Service (Python)                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              Data Ingestion Pipeline                    │    │
│  │                                                         │    │
│  │  • Financial Data (Balance Sheet, P&L, Cash Flow)      │    │
│  │  • Sentiment Data (Twitter, LinkedIn, News)            │    │
│  │  • Founder Data (LinkedIn API, Web Scraping)           │    │
│  │  • Market Data (Industry trends, Competitors)          │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                Analysis Modules                         │    │
│  │                                                         │    │
│  │  1. Financial Analysis                                  │    │
│  │     • Revenue growth, Burn rate, Runway                │    │
│  │     • Unit economics (CAC, LTV)                        │    │
│  │     • Profitability metrics                            │    │
│  │                                                         │    │
│  │  2. Sentiment Analysis                                  │    │
│  │     • NLP (BERT, FinBERT)                              │    │
│  │     • Social media sentiment scoring                   │    │
│  │     • News sentiment tracking                          │    │
│  │                                                         │    │
│  │  3. Founder Analysis                                    │    │
│  │     • Background verification                          │    │
│  │     • Network analysis (LinkedIn connections)          │    │
│  │     • Track record evaluation                          │    │
│  │                                                         │    │
│  │  4. Market Analysis                                     │    │
│  │     • TAM/SAM/SOM calculation                          │    │
│  │     • Competitor landscape                             │    │
│  │     • Industry growth trends                           │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │             Recommendation Engine                       │    │
│  │                                                         │    │
│  │  • Scoring Algorithm (Weighted Components)             │    │
│  │  • Risk Assessment (0-100 scale)                       │    │
│  │  • Confidence Intervals (Bayesian inference)           │    │
│  │  • Explainability (Top 5 factors)                      │    │
│  │  • Continuous Learning (Human feedback loop)           │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │                 ML Infrastructure                       │    │
│  │                                                         │    │
│  │  • Model Training (TensorFlow/PyTorch)                 │    │
│  │  • Model Versioning (MLflow)                           │    │
│  │  • Experiment Tracking (Weights & Biases)              │    │
│  │  • Model Serving (FastAPI endpoints)                   │    │
│  └────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

---

## Data Flow Diagrams

### 1. Investment Flow (End-to-End)

```
┌─────────┐       ┌─────────┐       ┌─────────┐       ┌─────────┐
│ Investor│       │ Frontend│       │ Backend │       │ Solana  │
│         │       │         │       │   API   │       │Blockchain│
└────┬────┘       └────┬────┘       └────┬────┘       └────┬────┘
     │                 │                 │                 │
     │ 1. Browse       │                 │                 │
     │ Campaigns       │                 │                 │
     ├────────────────>│                 │                 │
     │                 │                 │                 │
     │                 │ 2. Fetch        │                 │
     │                 │ Campaigns       │                 │
     │                 ├────────────────>│                 │
     │                 │                 │                 │
     │                 │                 │ 3. Query        │
     │                 │                 │ NeonDB +        │
     │                 │                 │ KV Cache        │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │                 │ 4. Return       │         │       │
     │                 │ Campaign List   │         │       │
     │                 │<────────────────┤         │       │
     │                 │                 │         │       │
     │ 5. Select       │                 │         │       │
     │ Campaign &      │                 │         │       │
     │ Amount          │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 6. Initiate     │         │       │
     │                 │ Investment      │         │       │
     │                 ├────────────────>│         │       │
     │                 │                 │         │       │
     │                 │                 │ 7. Validate     │
     │                 │                 │ (KYC, Limits)   │
     │                 │                 │<────────┘       │
     │                 │                 │         │       │
     │                 │ 8. Payment      │         │       │
     │                 │ Required        │         │       │
     │                 │<────────────────┤         │       │
     │                 │                 │         │       │
     │ 9. Connect      │                 │         │       │
     │ Wallet          │                 │         │       │
     │ (WalletConnect) │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 10. Wallet      │         │       │
     │                 │ Connected       │         │       │
     │                 │<────────────────│         │       │
     │                 │                 │         │       │
     │ 11. Approve     │                 │         │       │
     │ Transaction     │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 12. Sign & Send │         │       │
     │                 │ Transaction     │         │       │
     │                 ├─────────────────┼─────────────────>│
     │                 │                 │         │       │
     │                 │                 │         │ 13. Execute
     │                 │                 │         │ Smart Contract
     │                 │                 │         │ (Transfer USDC,
     │                 │                 │         │  Mint Tokens)
     │                 │                 │         │<────────┐
     │                 │                 │         │         │
     │                 │ 14. Transaction │         │         │
     │                 │ Confirmed       │         │         │
     │                 │<────────────────┼─────────────────┤
     │                 │                 │         │       │
     │                 │ 15. Update DB   │         │       │
     │                 │ (Investment     │         │       │
     │                 │  Record)        │         │       │
     │                 │<────────────────┤         │       │
     │                 │                 │         │       │
     │ 16. Show        │                 │         │       │
     │ Confirmation    │                 │         │       │
     │<────────────────┤                 │         │       │
     │                 │                 │         │       │
     │                 │ 17. Send Email  │         │       │
     │                 │ Receipt         │         │       │
     │<────────────────┼─────────────────┤         │       │
     │                 │                 │         │       │
```

### 2. Campaign Creation Flow

```
┌─────────┐       ┌─────────┐       ┌─────────┐       ┌─────────┐
│ Company │       │ Frontend│       │ Backend │       │  Admin  │
└────┬────┘       └────┬────┘       └────┬────┘       └────┬────┘
     │                 │                 │                 │
     │ 1. Start        │                 │                 │
     │ Campaign        │                 │                 │
     │ Creation        │                 │                 │
     ├────────────────>│                 │                 │
     │                 │                 │                 │
     │                 │ 2. Multi-step   │                 │
     │                 │ Wizard          │                 │
     │                 │ (7 steps)       │                 │
     │                 │<────────────────│                 │
     │                 │                 │                 │
     │ 3. Fill Details │                 │                 │
     │ (Company info,  │                 │                 │
     │  Financials,    │                 │                 │
     │  Team, etc.)    │                 │                 │
     ├────────────────>│                 │                 │
     │                 │                 │                 │
     │                 │ 4. Auto-save    │                 │
     │                 │ Draft (every    │                 │
     │                 │ 30 seconds)     │                 │
     │                 ├────────────────>│                 │
     │                 │                 │                 │
     │                 │                 │ 5. Save to DB   │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │ 6. Upload       │                 │         │       │
     │ Documents       │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 7. Upload to    │         │       │
     │                 │ Storage (S3/R2) │         │       │
     │                 ├────────────────>│         │       │
     │                 │                 │         │       │
     │ 8. Preview      │                 │         │       │
     │ Campaign        │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 9. Render       │         │       │
     │                 │ Preview         │         │       │
     │                 │<────────────────┤         │       │
     │                 │                 │         │       │
     │ 10. Submit for  │                 │         │       │
     │ Review          │                 │         │       │
     ├────────────────>│                 │         │       │
     │                 │                 │         │       │
     │                 │ 11. Change      │         │       │
     │                 │ Status to       │         │       │
     │                 │ "Under Review"  │         │       │
     │                 ├────────────────>│         │       │
     │                 │                 │         │       │
     │                 │                 │ 12. Notify      │
     │                 │                 │ Admin Team      │
     │                 │                 ├────────────────>│
     │                 │                 │         │       │
     │                 │                 │         │ 13. Review
     │                 │                 │         │ Campaign
     │                 │                 │         │ (KYC, Docs,
     │                 │                 │         │  Compliance)
     │                 │                 │         │<────────┐
     │                 │                 │         │         │
     │                 │                 │ 14. Approve or  │
     │                 │                 │ Reject          │
     │                 │                 │<────────────────┤
     │                 │                 │         │       │
     │                 │ 15. Update      │         │       │
     │                 │ Status &        │         │       │
     │                 │ Notify Company  │         │       │
     │<────────────────┼─────────────────┤         │       │
     │                 │                 │         │       │
     │ 16. If Approved │                 │         │       │
     │ Campaign Goes   │                 │         │       │
     │ Live            │                 │         │       │
     │<────────────────┤                 │         │       │
     │                 │                 │         │       │
```

### 3. AI Recommendation Flow

```
┌─────────┐       ┌─────────┐       ┌─────────┐       ┌─────────┐
│ Investor│       │ Backend │       │   AI    │       │ External│
│         │       │   API   │       │ Service │       │  APIs   │
└────┬────┘       └────┬────┘       └────┬────┘       └────┬────┘
     │                 │                 │                 │
     │ 1. Request      │                 │                 │
     │ Recommendations │                 │                 │
     ├────────────────>│                 │                 │
     │                 │                 │                 │
     │                 │ 2. Fetch User   │                 │
     │                 │ Profile &       │                 │
     │                 │ Investment      │                 │
     │                 │ History         │                 │
     │                 │<────────┐       │                 │
     │                 │         │       │                 │
     │                 │ 3. Call AI      │                 │
     │                 │ Recommendation  │                 │
     │                 │ API             │                 │
     │                 ├────────────────>│                 │
     │                 │                 │                 │
     │                 │                 │ 4. Fetch        │
     │                 │                 │ Active          │
     │                 │                 │ Campaigns       │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │                 │                 │ 5. For Each     │
     │                 │                 │ Campaign:       │
     │                 │                 │ Fetch Data      │
     │                 │                 ├────────────────>│
     │                 │                 │                 │
     │                 │                 │ • Financials    │
     │                 │                 │ • Social        │
     │                 │                 │   Sentiment     │
     │                 │                 │ • Founder Info  │
     │                 │                 │<────────────────┤
     │                 │                 │                 │
     │                 │                 │ 6. Run Scoring  │
     │                 │                 │ Algorithm       │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │                 │                 │ 7. Calculate    │
     │                 │                 │ Match Score     │
     │                 │                 │ (User Profile   │
     │                 │                 │  vs Campaign)   │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │                 │                 │ 8. Generate     │
     │                 │                 │ Explanations    │
     │                 │                 │ (Top 5 factors) │
     │                 │                 │<────────┐       │
     │                 │                 │         │       │
     │                 │ 9. Return       │         │       │
     │                 │ Ranked          │         │       │
     │                 │ Recommendations │         │       │
     │                 │<────────────────┤         │       │
     │                 │                 │         │       │
     │                 │ 10. Cache       │         │       │
     │                 │ Results         │         │       │
     │                 │ (Cloudflare KV) │         │       │
     │                 │<────────┐       │         │       │
     │                 │         │       │         │       │
     │ 11. Display     │         │       │         │       │
     │ Recommendations │         │       │         │       │
     │<────────────────┤         │       │         │       │
     │                 │         │       │         │       │
     │ 12. User        │         │       │         │       │
     │ Feedback        │         │       │         │       │
     │ (Like/Dislike)  │         │       │         │       │
     ├────────────────>│         │       │         │       │
     │                 │         │       │         │       │
     │                 │ 13. Log         │         │       │
     │                 │ Feedback for    │         │       │
     │                 │ Model Training  │         │       │
     │                 ├────────────────>│         │       │
     │                 │         │       │         │       │
```

---

## Blockchain Architecture

### Solana Smart Contract Structure

```
┌─────────────────────────────────────────────────────────────────┐
│                  Solana Program Architecture                     │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              Token Program (SPL Token-2022)             │    │
│  │                                                         │    │
│  │  Instructions:                                          │    │
│  │  • initialize_mint()                                    │    │
│  │    - Create new token for campaign                     │    │
│  │    - Set transfer hook (whitelist check)               │    │
│  │    - Set lock-up period (12 months)                    │    │
│  │                                                         │    │
│  │  • mint_to()                                            │    │
│  │    - Mint tokens to investor wallet                    │    │
│  │    - Record on-chain ownership                         │    │
│  │                                                         │    │
│  │  • transfer_checked()                                   │    │
│  │    - Transfer with whitelist verification              │    │
│  │    - Check lock-up expiry                              │    │
│  │    - Enforce compliance rules                          │    │
│  │                                                         │    │
│  │  Accounts:                                              │    │
│  │  • mint (PDA)                                           │    │
│  │  • token_account (ATA)                                  │    │
│  │  • whitelist (PDA)                                      │    │
│  │  • lock_schedule (PDA)                                  │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │             Escrow Program (3-of-5 Multisig)            │    │
│  │                                                         │    │
│  │  Instructions:                                          │    │
│  │  • initialize_escrow()                                  │    │
│  │    - Create escrow account for campaign                │    │
│  │    - Set multi-sig authorities (3-of-5)                │    │
│  │    - Set campaign parameters (goal, deadline)          │    │
│  │                                                         │    │
│  │  • deposit()                                            │    │
│  │    - Receive USDC from investors                       │    │
│  │    - Update campaign funding total                     │    │
│  │    - Emit deposit event                                │    │
│  │                                                         │    │
│  │  • propose_release()                                    │    │
│  │    - Admin proposes fund release                       │    │
│  │    - Set milestone and amount                          │    │
│  │                                                         │    │
│  │  • sign_release()                                       │    │
│  │    - Collect signatures (need 3 of 5)                  │    │
│  │    - Execute when threshold reached                    │    │
│  │                                                         │    │
│  │  • release_funds()                                      │    │
│  │    - Transfer USDC to company wallet                   │    │
│  │    - Deduct platform fee (2%)                          │    │
│  │    - Update campaign status                            │    │
│  │                                                         │    │
│  │  • refund()                                             │    │
│  │    - Return USDC to investors if goal not met          │    │
│  │    - Pro-rata refund calculation                       │    │
│  │                                                         │    │
│  │  Accounts:                                              │    │
│  │  • escrow (PDA)                                         │    │
│  │  • escrow_authority (PDA)                               │    │
│  │  • campaign_state (PDA)                                 │    │
│  │  • multisig_config (PDA)                                │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  ┌────────────────────────────────────────────────────────┐    │
│  │              Distribution Program                       │    │
│  │                                                         │    │
│  │  Instructions:                                          │    │
│  │  • schedule_distribution()                              │    │
│  │    - Company schedules dividend/profit share           │    │
│  │    - Set distribution date and amount                  │    │
│  │                                                         │    │
│  │  • execute_distribution()                               │    │
│  │    - Distribute USDC to all token holders              │    │
│  │    - Pro-rata based on ownership                       │    │
│  │    - Emit distribution events                          │    │
│  │                                                         │    │
│  │  • claim_distribution()                                 │    │
│  │    - Investor claims their share                       │    │
│  │    - Transfer USDC to investor wallet                  │    │
│  │                                                         │    │
│  │  Accounts:                                              │    │
│  │  • distribution_pool (PDA)                              │    │
│  │  • claim_record (PDA per investor)                      │    │
│  └────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

### On-Chain Data Structures

```rust
// Campaign State (stored on-chain)
pub struct Campaign {
    pub campaign_id: [u8; 32],
    pub company_pubkey: Pubkey,
    pub mint_pubkey: Pubkey,
    pub escrow_pubkey: Pubkey,

    pub goal_amount: u64,          // Target in USDC (6 decimals)
    pub raised_amount: u64,        // Current raised amount
    pub min_investment: u64,       // Minimum per investor
    pub max_investment: u64,       // Maximum per investor (if any)

    pub start_timestamp: i64,
    pub end_timestamp: i64,
    pub lock_up_duration: i64,     // 12 months = 31536000 seconds

    pub status: CampaignStatus,    // Draft, Active, Funded, Closed
    pub investor_count: u32,

    pub bump: u8,
}

// Escrow State
pub struct Escrow {
    pub campaign_id: [u8; 32],
    pub authority: Pubkey,
    pub usdc_vault: Pubkey,

    pub total_deposited: u64,
    pub total_released: u64,
    pub total_refunded: u64,

    pub multisig_threshold: u8,    // 3
    pub multisig_signers: Vec<Pubkey>, // 5 signers

    pub bump: u8,
}

// Investment Record
pub struct Investment {
    pub investor_pubkey: Pubkey,
    pub campaign_id: [u8; 32],

    pub amount_usdc: u64,
    pub tokens_received: u64,
    pub investment_timestamp: i64,
    pub lock_up_expiry: i64,

    pub bump: u8,
}

// Lock Schedule (per investor per campaign)
pub struct LockSchedule {
    pub investor: Pubkey,
    pub mint: Pubkey,
    pub locked_amount: u64,
    pub unlock_timestamp: i64,
    pub bump: u8,
}

// Distribution Record
pub struct Distribution {
    pub campaign_id: [u8; 32],
    pub distribution_id: u64,

    pub total_amount: u64,
    pub amount_per_token: u64,      // Calculated pro-rata
    pub distribution_timestamp: i64,

    pub claimed_count: u32,
    pub total_claimed: u64,

    pub bump: u8,
}
```

---

## Infrastructure Architecture

### Deployment Topology

```
                         ┌─────────────────────────┐
                         │   Cloudflare Global     │
                         │   Edge Network          │
                         │   (180+ Locations)      │
                         └────────┬────────────────┘
                                  │
                    ┌─────────────┴─────────────┐
                    │                           │
         ┌──────────▼────────┐       ┌─────────▼──────────┐
         │  Cloudflare CDN   │       │  Cloudflare KV     │
         │                   │       │  (Edge Cache)      │
         │  • Static Assets  │       │                    │
         │  • Images         │       │  • Session Data    │
         │  • CSS/JS         │       │  • Campaign Cache  │
         └──────────┬────────┘       └─────────┬──────────┘
                    │                           │
                    └─────────────┬─────────────┘
                                  │
                    ┌─────────────▼─────────────┐
                    │   Vercel Edge Functions   │
                    │   (Next.js Deployment)    │
                    │                           │
                    │   Regions:                │
                    │   • Singapore (Primary)   │
                    │   • Hong Kong             │
                    │   • Tokyo                 │
                    │   • Mumbai                │
                    └─────────────┬─────────────┘
                                  │
                ┌─────────────────┼─────────────────┐
                │                 │                 │
    ┌───────────▼──────────┐  ┌──▼──────────┐  ┌──▼──────────┐
    │   Backend API        │  │  NeonDB     │  │  AI Service │
    │   (Node.js/TS)       │  │ (PostgreSQL)│  │  (Python)   │
    │                      │  │             │  │             │
    │   Hosted on:         │  │  Primary:   │  │  Hosted on: │
    │   • Railway          │  │  Singapore  │  │  • Railway  │
    │   • Render           │  │             │  │  • Render   │
    │   • Fly.io           │  │  Replicas:  │  │  • Modal    │
    │                      │  │  Hong Kong  │  │             │
    │   Region: Singapore  │  │             │  │  Region:    │
    │                      │  │             │  │  Singapore  │
    └───────────┬──────────┘  └──┬──────────┘  └──┬──────────┘
                │                │                │
                └────────────────┼────────────────┘
                                 │
                    ┌────────────▼────────────┐
                    │   Solana Blockchain     │
                    │                         │
                    │   Networks:             │
                    │   • Devnet (Testing)    │
                    │   • Testnet (Staging)   │
                    │   • Mainnet (Production)│
                    └─────────────────────────┘
```

### Geographic Distribution

```
┌─────────────────────────────────────────────────────────────────┐
│                        Asia-Pacific Region                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  🌏 Singapore (Primary Data Center)                              │
│  ├─ NeonDB Primary (PostgreSQL)                                 │
│  ├─ Backend API Servers                                         │
│  ├─ AI Service Nodes                                            │
│  └─ Cloudflare Edge PoP                                         │
│                                                                  │
│  🌏 Hong Kong (Secondary)                                        │
│  ├─ NeonDB Replica (Read-only)                                  │
│  ├─ Backend API (Failover)                                      │
│  └─ Cloudflare Edge PoP                                         │
│                                                                  │
│  🌏 Tokyo (Edge)                                                 │
│  ├─ Cloudflare Edge PoP                                         │
│  └─ Vercel Edge Functions                                       │
│                                                                  │
│  🌏 Mumbai (Edge)                                                │
│  ├─ Cloudflare Edge PoP                                         │
│  └─ Vercel Edge Functions                                       │
│                                                                  │
│  🌏 Dubai (Edge - for UAE users)                                 │
│  ├─ Cloudflare Edge PoP                                         │
│  └─ Vercel Edge Functions                                       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘

Latency Targets:
• Singapore users:     <50ms  (local)
• Hong Kong users:     <30ms  (via HK PoP)
• UAE users:           <80ms  (via Dubai PoP)
• Thailand users:      <60ms  (via Singapore PoP)
• Malaysia users:      <40ms  (via Singapore PoP)
• Indonesia users:     <70ms  (via Singapore PoP)
```

---

## Security Architecture

### Authentication & Authorization Flow

```
┌─────────────────────────────────────────────────────────────────┐
│                    Authentication Flow                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌──────────────────────────────────────────────────────┐      │
│  │  1. User Login                                        │      │
│  │                                                       │      │
│  │  Options:                                             │      │
│  │  a) Email + Password                                  │      │
│  │  b) Social OAuth (Google, LinkedIn)                   │      │
│  │  c) Wallet Connect (Solana wallet signature)          │      │
│  └──────────────────────────────────────────────────────┘      │
│                    ▼                                             │
│  ┌──────────────────────────────────────────────────────┐      │
│  │  2. Authentication Service                            │      │
│  │                                                       │      │
│  │  • Verify credentials                                 │      │
│  │  • Check account status (active, suspended)           │      │
│  │  • Enforce MFA if enabled (TOTP, SMS)                │      │
│  │  • Rate limiting (5 attempts per 15 minutes)          │      │
│  └──────────────────────────────────────────────────────┘      │
│                    ▼                                             │
│  ┌──────────────────────────────────────────────────────┐      │
│  │  3. Generate JWT Tokens                               │      │
│  │                                                       │      │
│  │  Access Token (15 minutes expiry):                    │      │
│  │  {                                                    │      │
│  │    "user_id": "uuid",                                 │      │
│  │    "email": "user@example.com",                       │      │
│  │    "role": "investor|company|admin",                  │      │
│  │    "kyc_status": "verified|pending|rejected",         │      │
│  │    "iat": timestamp,                                  │      │
│  │    "exp": timestamp + 15min                           │      │
│  │  }                                                    │      │
│  │                                                       │      │
│  │  Refresh Token (7 days expiry):                       │      │
│  │  {                                                    │      │
│  │    "user_id": "uuid",                                 │      │
│  │    "token_family": "uuid",                            │      │
│  │    "iat": timestamp,                                  │      │
│  │    "exp": timestamp + 7days                           │      │
│  │  }                                                    │      │
│  └──────────────────────────────────────────────────────┘      │
│                    ▼                                             │
│  ┌──────────────────────────────────────────────────────┐      │
│  │  4. Store Refresh Token                               │      │
│  │                                                       │      │
│  │  • Hash refresh token                                 │      │
│  │  • Store in NeonDB (refresh_tokens table)             │      │
│  │  • Associate with user_id and device_id               │      │
│  └──────────────────────────────────────────────────────┘      │
│                    ▼                                             │
│  ┌──────────────────────────────────────────────────────┐      │
│  │  5. Return Tokens to Client                           │      │
│  │                                                       │      │
│  │  Response:                                            │      │
│  │  {                                                    │      │
│  │    "access_token": "...",                             │      │
│  │    "refresh_token": "...",                            │      │
│  │    "token_type": "Bearer",                            │      │
│  │    "expires_in": 900                                  │      │
│  │  }                                                    │      │
│  └──────────────────────────────────────────────────────┘      │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Role-Based Access Control (RBAC)

```
┌─────────────────────────────────────────────────────────────────┐
│                        Permission Matrix                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Resource         │ Investor │ Company │ Admin │ AI Service    │
│  ─────────────────┼──────────┼─────────┼───────┼───────────────┤
│  Browse Campaigns │    ✓     │    ✓    │   ✓   │      ✓        │
│  View Campaign    │    ✓     │    ✓    │   ✓   │      ✓        │
│  Create Campaign  │    ✗     │    ✓    │   ✗   │      ✗        │
│  Edit Campaign    │    ✗     │   Own   │   ✓   │      ✗        │
│  Invest           │    ✓     │    ✗    │   ✗   │      ✗        │
│  View Portfolio   │   Own    │    ✗    │   ✓   │      ✗        │
│  Approve Campaign │    ✗     │    ✗    │   ✓   │      ✗        │
│  KYC Review       │    ✗     │    ✗    │   ✓   │      ✗        │
│  Generate AI Score│    ✗     │    ✗    │   ✗   │      ✓        │
│  View All Users   │    ✗     │    ✗    │   ✓   │      ✗        │
│  Escrow Release   │    ✗     │    ✗    │  3/5  │      ✗        │
│  Platform Config  │    ✗     │    ✗    │   ✓   │      ✗        │
│                                                                  │
│  Legend:                                                         │
│  ✓   = Full Access                                               │
│  ✗   = No Access                                                 │
│  Own = Can only access own resources                             │
│  3/5 = Requires 3 of 5 multi-sig approvals                       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Data Security Layers

```
┌─────────────────────────────────────────────────────────────────┐
│                    Security Layers (Defense in Depth)            │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Layer 1: Network Security                                       │
│  ┌────────────────────────────────────────────────────────┐    │
│  │ • Cloudflare WAF (OWASP Top 10 protection)             │    │
│  │ • DDoS Protection (Layer 3, 4, 7)                      │    │
│  │ • Rate Limiting (per IP, per user)                     │    │
│  │ • Geo-blocking (block high-risk countries)             │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  Layer 2: Application Security                                   │
│  ┌────────────────────────────────────────────────────────┐    │
│  │ • JWT Authentication (RSA-256 signed)                  │    │
│  │ • RBAC (Role-Based Access Control)                     │    │
│  │ • Input Validation (Zod schemas)                       │    │
│  │ • SQL Injection Prevention (Prisma ORM)                │    │
│  │ • XSS Prevention (React auto-escaping, CSP headers)    │    │
│  │ • CSRF Protection (SameSite cookies, tokens)           │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  Layer 3: Data Security                                          │
│  ┌────────────────────────────────────────────────────────┐    │
│  │ • Encryption at Rest (AES-256)                         │    │
│  │   - NeonDB: Transparent encryption                     │    │
│  │   - File Storage: Encrypted S3/R2 buckets              │    │
│  │                                                         │    │
│  │ • Encryption in Transit (TLS 1.3)                      │    │
│  │   - HTTPS for all API calls                            │    │
│  │   - WSS for WebSockets                                 │    │
│  │                                                         │    │
│  │ • PII Encryption (Application-level)                   │    │
│  │   - Email, Phone, ID numbers (AES-256-GCM)            │    │
│  │   - Separate encryption keys per data type             │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  Layer 4: Blockchain Security                                    │
│  ┌────────────────────────────────────────────────────────┐    │
│  │ • Wallet Signature Verification (Ed25519)              │    │
│  │ • Transaction Simulation (before submission)           │    │
│  │ • Multi-sig Escrow (3-of-5 threshold)                  │    │
│  │ • Smart Contract Audits (external firms)               │    │
│  │ • Transfer Hooks (KYC whitelist checks)                │    │
│  │ • Emergency Pause Mechanism (admin-controlled)         │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
│  Layer 5: Monitoring & Incident Response                         │
│  ┌────────────────────────────────────────────────────────┐    │
│  │ • Real-time Security Monitoring (Sentry, Datadog)      │    │
│  │ • Audit Logging (immutable logs to NeonDB)             │    │
│  │ • Anomaly Detection (AI-powered)                       │    │
│  │ • Incident Response Plan (documented procedures)       │    │
│  │ • Bug Bounty Program (HackerOne)                       │    │
│  └────────────────────────────────────────────────────────┘    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## Deployment Architecture

### CI/CD Pipeline

```
┌─────────────────────────────────────────────────────────────────┐
│                    Continuous Deployment Pipeline                │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Developer        GitHub         GitHub Actions    Environments │
│  ──────────      ────────        ──────────────    ─────────── │
│                                                                  │
│      │                                                           │
│      │ 1. git push                                               │
│      ├──────────────>                                            │
│      │               │                                           │
│      │               │ 2. Trigger                                │
│      │               │ Workflow                                  │
│      │               ├─────────────>                             │
│      │               │              │                            │
│      │               │              │ 3. Checkout Code           │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 4. Run Linters             │
│      │               │              │ (ESLint, Prettier)         │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 5. Run Tests               │
│      │               │              │ (Jest, Vitest)             │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 6. Build                   │
│      │               │              │ (Next.js, TypeScript)      │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 7. Security Scan           │
│      │               │              │ (Snyk, Trivy)              │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 8. Deploy                  │
│      │               │              ├────────────────────>       │
│      │               │              │                   │        │
│      │               │              │                   │        │
│  Branch-based Deployment:                              │        │
│  ────────────────────────────────────────────────────────────── │
│                                                         │        │
│  • feature/*   → Preview Deploy (Vercel Preview URL)    │        │
│  • develop     → Development (Solana Devnet)            │        │
│  • staging     → Staging (Solana Testnet)               │        │
│  • main        → Production (Solana Mainnet)            │        │
│                                                         │        │
│      │               │              │ 9. Run E2E Tests           │
│      │               │              │ (Playwright)               │
│      │               │              │<──────┐                    │
│      │               │              │       │                    │
│      │               │              │ 10. Notify                 │
│      │               │              │ (Slack, Discord)           │
│      │<──────────────┼──────────────┤                            │
│      │               │              │                            │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Environment Configuration

```
┌─────────────────────────────────────────────────────────────────┐
│                     Environment Matrix                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Component      │ Development │ Staging    │ Production         │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Frontend       │ Localhost   │ Vercel     │ Vercel             │
│                 │ :3000       │ Preview    │ elevate-fi.com     │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Backend API    │ Localhost   │ Railway    │ Railway            │
│                 │ :4000       │ Staging    │ Production         │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Database       │ Local       │ NeonDB     │ NeonDB             │
│                 │ PostgreSQL  │ Singapore  │ Singapore          │
│                 │ Docker      │            │ (w/ HK replica)    │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Cache          │ Local       │ Cloudflare │ Cloudflare         │
│                 │ (in-memory) │ KV Staging │ KV Production      │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Blockchain     │ Solana      │ Solana     │ Solana             │
│                 │ Devnet      │ Testnet    │ Mainnet            │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  RPC Endpoint   │ Public      │ Helius     │ Helius Premium     │
│                 │ Devnet      │ Testnet    │ + Triton (backup)  │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  AI Service     │ Localhost   │ Modal      │ Modal              │
│                 │ :5000       │ Staging    │ Production         │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  KYC Provider   │ Sumsub      │ Sumsub     │ Sumsub             │
│                 │ Sandbox     │ Sandbox    │ Production         │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Payment        │ Stripe      │ Stripe     │ Stripe             │
│                 │ Test Mode   │ Test Mode  │ Live Mode          │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Monitoring     │ Local Logs  │ Sentry     │ Sentry +           │
│                 │             │            │ Datadog            │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│  Analytics      │ None        │ PostHog    │ PostHog +          │
│                 │             │            │ Mixpanel           │
│  ───────────────┼─────────────┼────────────┼────────────────────┤
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## Performance Targets

```
┌─────────────────────────────────────────────────────────────────┐
│                    Performance SLAs                              │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Metric                        │ Target      │ Critical         │
│  ──────────────────────────────┼─────────────┼──────────────────┤
│  Frontend (Time to Interactive)│ <2s (p95)   │ <3s (p99)        │
│  API Response Time             │ <200ms (p95)│ <500ms (p99)     │
│  Database Query Time           │ <50ms (p95) │ <100ms (p99)     │
│  Cache Hit Rate                │ >80%        │ >70%             │
│  Blockchain TX Confirmation    │ <5s (p95)   │ <10s (p99)       │
│  AI Recommendation Generation  │ <1s (p95)   │ <2s (p99)        │
│  Concurrent Users              │ 5,000       │ 10,000 (burst)   │
│  Uptime                        │ 99.9%       │ 99.5% (min)      │
│  Error Rate                    │ <0.1%       │ <1%              │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

**Document Status**: Draft v1.0
**Next Update**: After Phase 1 infrastructure setup
**Owner**: Engineering Team
