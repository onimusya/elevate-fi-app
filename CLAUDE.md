# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**Elevate Finance** is an AI-enabled DeFi token & equity crowdfunding platform for SMEs and startups in Asia. The platform combines:
- Blockchain tokenization (Solana-first, multi-chain later)
- Real-world asset (RWA) backing
- AI-powered investment analysis and recommendations
- Regulatory compliance for 6 Asian markets (Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia)

**Current Status**: Pre-development planning phase. Only documentation exists (PRD, project overview, UI mockup).

---

## Project Structure

This is currently a **greenfield project** with only documentation:

```
elevate-fi-app/
├── docs/
│   ├── PRD.md                    # Comprehensive Product Requirements Document
│   ├── project-overview.md       # Technical specifications and strategic decisions
│   └── mockup-design.png         # UI/UX design reference
└── CLAUDE.md                     # This file
```

**Note**: Code implementation has not started. When development begins, expect these directories:
- `/programs` - Solana smart contracts (Anchor framework)
- `/app` - Frontend application (likely Next.js/React)
- `/api` or `/backend` - Backend services
- `/ai` - AI/ML models and training pipelines

---

## Key Architecture Decisions

### 1. Blockchain Stack (Phase 1 MVP)

**Primary Chain**: Solana
- **Rationale**: Low fees ($0.00025/tx), 400ms finality, 65K TPS
- **Token Standard**: SPL Token-2022 with transfer hooks for compliance
- **Wallet Integration**: Phantom (primary)
- **Networks**: Support deployment to Devnet, Testnet, and Mainnet

**Smart Contract Requirements**:
- Escrow mechanism (3-of-5 multi-sig)
- 12-month lock-up period enforcement
- Whitelist-based transfer restrictions
- Milestone-based fund release (investor voting)

**Future Multi-Chain** (Phase 2):
- Ethereum: ERC-1400 security tokens
- Sui: Object-based programmable ownership

### 2. Stablecoin Support

**Accepted Tokens**:
- USDC (SPL) - Primary
- USDT (SPL) - Secondary

**Fiat On-Ramps**:
- Stripe (credit/debit cards)
- Transak (bank transfers, Asia-focused)
- MoonPay (global coverage)

### 3. User Roles & Permissions

Five distinct user types with specific permissions:

1. **Companies/Issuers**: Campaign creation, document upload, investor updates
2. **Retail Investors**: Portfolio dashboard, AI insights, secondary trading
3. **Institutional Investors**: API access (Phase 2), bulk investments
4. **Platform Admins**: Campaign approval, KYC review, compliance, treasury
5. **AI Investment Manager**: Read campaign data, write recommendations, audit logging

### 4. Campaign Lifecycle States

```
Draft → Submitted for Review → Under Review → Approved/Live → Funded → Closed
                                                           ↘ Rejected
```

**Key Constraints**:
- Minimum raise: $50,000 USD
- Maximum raise: $5,000,000 USD (Phase 1)
- All-or-nothing funding (no partial)
- Overfunding allowed up to 150% of target
- Duration: 30, 60, or 90 days (company chooses)

### 5. AI Investment Manager Specifications

**Data Sources**:
- Financial statements (balance sheet, P&L, cash flow)
- Social sentiment (Twitter, LinkedIn, news, Reddit)
- Founder background (education, ventures, network)
- Market data (industry trends, competitor analysis)

**AI Methodologies** (Progressive Enhancement):
- **Phase 1**: Rule-based + basic ML → Human approval (100% oversight)
- **Phase 2**: Deep learning + reinforcement learning → 50% spot-checks
- **Phase 3**: Autonomous for <$100K deals → 10% random audit

**Governance**:
- Weekly AI decision review
- Monthly model performance audits
- Quarterly retraining cycles

### 6. Compliance & Regulatory

**Target Markets** (in priority order):
1. Singapore (MAS CMS License) - Q1 2026
2. Hong Kong (SFC Type 1 License) - Q2 2026
3. UAE Dubai (VARA VASP License) - Q3 2026
4. Thailand (SEC Digital Asset Broker) - Q4 2026
5. Malaysia (IEO Operator License) - Q1 2027
6. Indonesia (OJK ECF License) - Q2 2027

**KYC/AML Requirements**:
- Enhanced KYC (document verification, liveness check, sanctions screening)
- 7-year transaction data retention
- Immutable audit trails (blockchain-backed)

**Investment Limits** (vary by country):
- Singapore: 50 non-accredited investors max per offer
- Thailand: ≤250K THB ($7K) per investor per project
- Malaysia: ≤20K MYR per issuer per year (retail)
- Indonesia: ≤5M IDR (~$320) per investor per year

---

## Performance & Scale Requirements

**User Capacity**:
- Concurrent users: 5,000
- Year 1 target: 100,000 total users
- Year 2 target: 500,000 total users

**Performance SLAs**:
- Page load: <2s (desktop), <3s (mobile)
- API response: <200ms (p95), <500ms (p99)
- Blockchain finality: <5s (Solana)
- Uptime: 99.9%

**Geographic Distribution**:
- Southeast Asia: 50%
- East Asia: 30%
- Middle East: 20%
- CDN: Cloudflare with edge caching
- Data residency: Singapore (primary), Hong Kong (backup)

---

## Fee Structure & Monetization

**Platform Fees**:
- 2% of funds raised (paid by companies)
- Volume discounts: 1.5% for $1M-$3M, 1% for >$3M

**Performance Fees**:
- 20% of profits above 8% hurdle rate (pooled fund investors)

**Transaction Fees**:
- 0.5% on secondary market trades (0.25% buyer, 0.25% seller)

**Investment Thresholds**:
- Minimum: $100 USD (USDC/USDT)
- Maximum: None (triggers enhanced due diligence for large amounts)

**Profit Distribution**:
- Quarterly (March 31, June 30, Sept 30, Dec 31)
- Same stablecoin as original investment
- Automated on-chain (Phase 2)

---

## Development Guidelines

### When Building Smart Contracts

1. **Always provide deployment options** for:
   - Solana Devnet (testing)
   - Solana Testnet (staging)
   - Solana Mainnet (production)

2. **Critical Security Features**:
   - Multi-sig escrow (3-of-5 signatures minimum)
   - Time-based lock-ups (12-month minimum, enforced on-chain)
   - Whitelist-based transfers (KYC/AML compliance)
   - Emergency pause mechanism (admin-controlled)
   - Upgrade mechanism with time-lock

3. **Testing Requirements**:
   - Unit tests for all token operations
   - Integration tests for escrow flows
   - Compliance tests for transfer restrictions
   - Load tests for concurrent investor scenarios

### When Building the AI System

1. **Data Privacy**:
   - PDPA (Singapore) and GDPR-ready architecture
   - Anonymize data for model training
   - 3-year retention for AI training data

2. **Explainability**:
   - Every recommendation must include top 5 factors
   - Confidence intervals (e.g., "70-85% probability")
   - Comparison to similar campaigns

3. **Bias Mitigation**:
   - Regular audits for demographic bias (gender, ethnicity, age)
   - Fairness constraints in model training
   - Third-party annual audit with public results

### When Building the Frontend

1. **UI/UX Reference**: See `docs/mockup-design.png` for design system
   - Clean, modern aesthetic with "tree growth" investment metaphor
   - Card-based campaign listings
   - Left sidebar filtering (Region, Industry, Goal)

2. **Wallet Integration**:
   - **WalletConnect** for universal Solana wallet support
   - Primary wallets: Phantom, Solflare, Backpack
   - Future: MetaMask (Ethereum), Sui Wallet
   - Hardware wallet support: Ledger, Trezor

3. **Multi-Language Support** (Phase 2+):
   - English (default)
   - Cantonese (Hong Kong)
   - Arabic (UAE)
   - Thai, Bahasa (Thailand, Malaysia, Indonesia)

---

## Documentation References

**Primary Documents**:
- `docs/PRD.md` - Comprehensive Product Requirements Document
  - Executive Summary (vision, market, competition, KPIs, roadmap)
  - Market Analysis (TAM/SAM/SOM, competitors, personas, regulatory landscape)
  - Product Vision & Strategy (3-year vision, strategic pillars, growth, monetization)
  - Functional Requirements (coming soon)

- `docs/project-overview.md` - Technical specifications and constraints
  - Blockchain strategy (Solana SPL Token-2022)
  - AI Investment Manager specs
  - User roles and permissions
  - Campaign lifecycle and escrow mechanism
  - Payment infrastructure
  - Performance requirements

- `docs/mockup-design.png` - UI/UX design reference for frontend development

---

## Important Constraints & Non-Negotiables

1. **No US operations in Phase 1** - Defer until SEC regulatory clarity
2. **Retail-friendly** - No accreditation requirements (aligns with Asian regulations)
3. **All-or-nothing funding** - No partial funding allowed
4. **12-month minimum lock-up** - Enforced via smart contracts
5. **AI transparency** - All recommendations must be explainable
6. **Multi-sig security** - 3-of-5 minimum for escrow releases
7. **Data residency** - Singapore/Hong Kong only (regulatory compliance)

---

## Revenue Targets & Business Metrics

**3-Year Goals**:
- Year 1: $150M GMV, 100K users, $3.3M revenue
- Year 2: $750M GMV, 500K users, $20M revenue
- Year 3: $2.5B GMV, 2M users, $73M revenue

**North Star Metric**: $500M Total Value Locked (TVL) by end of Year 3

**Unit Economics** (Year 3 target):
- LTV: $370 (3-year)
- CAC: $18
- LTV:CAC ratio: 20.5x
- Payback period: 1.8 months

---

## Asset Classes Supported

**RWA (Real-World Assets)**:
- Real estate (commercial, residential, REITs)
- Inventory (supply chain, warehouse receipts)
- Intellectual property (patents, trademarks, royalties)
- Revenue streams (receivables, subscriptions)

**Equity Instruments**:
- Common shares
- Preference shares (cumulative, non-cumulative, participating)
- Convertible notes
- SAFE agreements

---

## Tech Stack (Confirmed)

**Blockchain**:
- Solana Anchor framework (Rust)
- SPL Token-2022 standard
- **WalletConnect** for Solana wallet integration (Phantom, Solflare, etc.)

**Backend**:
- Node.js/TypeScript
- **NeonDB** (PostgreSQL) - Serverless Postgres for transaction data, 7-year retention
- **Cloudflare KV** - Edge caching and session management
- Message queue (campaign events, investor notifications)

**Frontend**:
- Next.js/React with TypeScript
- **Shadcn UI** - Component library for consistent, accessible UI
- Tailwind CSS (based on mockup design)
- Solana Web3.js
- WalletConnect adapter for wallet integration

**AI/ML**:
- Python (TensorFlow/PyTorch)
- Data pipeline for financial analysis, sentiment, voice analysis
- Model versioning and experiment tracking

**Infrastructure**:
- Cloudflare (CDN, KV cache, DNS, DDoS protection)
- Vercel or Cloudflare Pages (hosting, edge functions)
- Singapore region for data residency (NeonDB)
- Automated deployment pipelines (Devnet → Testnet → Mainnet)

