## 🎯 PROJECT OVERVIEW

### Vision Statement
Elevate Finance democratizes access to capital for SMEs and startups in Asia by combining blockchain tokenization, real-world asset (RWA) backing, and institutional-grade AI analysis. We enable companies to raise funds through cryptocurrency and fiat while providing investors with unprecedented liquidity and AI-powered investment intelligence.

### Core Value Propositions
- **For Companies**: Simplified fundraising through tokenization, access to global capital, fractional ownership
- **For Investors**: AI-powered due diligence, diversified portfolio options, liquidity through secondary markets
- **For Platform**: Performance-based revenue, network effects, data-driven insights

---

## 🌏 STRATEGIC DECISIONS & CONSTRAINTS

### Regulatory & Compliance
- **Target Market**: Asia-first (Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia)
- **US Operations**: Not in Phase 1 (future consideration post-SEC clarity)
- **KYC/AML Level**: Enhanced KYC (document verification, liveness check, sanctions screening)
- **Investor Access**: Retail investors (no accreditation requirements)
- **Securities Compliance**: Follow MAS (Singapore), SFC (Hong Kong), local securities laws
- **Data Privacy**: PDPA (Singapore), GDPR-ready architecture

### AI Investment Manager Specifications
**Data Sources for Analysis:**
- Financial statements (balance sheet, P&L, cash flow)
- Market data (industry trends, competitor analysis, market size)
- Social sentiment (Twitter, LinkedIn, news articles, Reddit)
- Founder background (education, previous ventures, professional network)

**AI Methodologies:**
- Voice analysis (pitch deck presentations, founder interviews)
- Behavioral patterns (communication style, response time, decision-making)
- Psychometric testing (personality assessment, leadership traits)
- Financial modeling (revenue projections, burn rate analysis)

**Decision Authority:**
- **Phase 1**: AI recommends → Humans approve (100% oversight)
- **Phase 2**: AI learns from approved decisions (reinforcement learning)
- **Phase 3**: AI auto-invests up to threshold (e.g., $10K-$50K per deal) with human approval for larger amounts

**Governance:**
- Investment committee oversight required
- Weekly AI decision review
- Monthly model performance audits
- Quarterly retraining cycles

### Blockchain & Tokenization Strategy

**Phase 1 (MVP): Solana-First**
- **Primary Chain**: Solana (low fees $0.00025/tx, 400ms finality, 65K TPS), provide build option to deploy to Solana Devnet, Testnet and Mainnet
- **Token Standard**: SPL Token-2022 with transfer hooks
- **Transfer Restrictions**: Whitelist-based transfers for securities compliance
- **Wallet**: Phantom wallet integration (primary)

**Phase 2: Multi-Chain Expansion**
- **Ethereum**: ERC-1400 (security tokens with partitions)
- **Sui**: Object-based tokens with programmable ownership

**Asset Classes for Tokenization:**

**RWA Tokens:**
- Real Estate (commercial, residential, REITs)
- Inventory (supply chain financing, warehouse receipts)
- Intellectual Property (patents, trademarks, royalty streams)
- Revenue Streams (future receivables, subscription revenue)

**Equity Instruments:**
- Common shares
- Preference shares (cumulative, non-cumulative, participating)
- Convertible notes
- SAFE agreements

**Ownership Mapping:**
- Off-chain legal registry (Carta, Pulley integration consideration)
- Smart contract as immutable ledger
- Bi-directional sync every 24 hours
- Multi-sig admin controls for registry updates

### Investment Pool Mechanics

**Fee Structure:**
- **Platform Fee**: 2% of funds raised (paid by companies)
- **Performance Fee**: 20% of profits above 8% hurdle rate (paid by pooled fund investors)
- **Transaction Fee**: 0.5% on secondary market trades
- **Withdrawal Fee**: None (encourage holding)

**Investment Thresholds:**
- **Minimum Investment**: $100 USD equivalent (USDC/USDT/DAI)
- **Maximum Investment**: None (but large investments trigger enhanced due diligence)
- **Pooled Fund Minimum**: $100 USD (fractional shares)

**Profit Distribution:**
- **Frequency**: Quarterly (March 31, June 30, Sept 30, Dec 31)
- **Method**: Manual distribution → Automated on-chain (Phase 2)
- **Currency**: Same stablecoin as original investment
- **Tax Reporting**: Automated 1099-like statements

**Liquidity Options:**
- **Lock-up Period**: 12 months minimum (standard for private equity)
- **Early Exit**: Not permitted (enforced by smart contract)
- **Secondary Market**: P2P trading after lock-up via integrated marketplace
- **Market Makers**: Platform can provide liquidity (future consideration)

### User Roles & Permissions System

**1. Companies/Issuers**
- Self-service campaign creation (draft mode)
- Upload documents (pitch deck, financials, legal docs)
- Manage investor updates
- View analytics dashboard
- Requires admin approval before going live
- Cannot modify funding amount after approval
- Can pause campaign (admin notification)

**2. Retail Investors**
- No investment limits (aligns with Asia retail-friendly regulations)
- Portfolio dashboard (holdings, returns, distributions)
- AI insights access (recommendations, risk scores)
- Secondary market trading
- Wallet management (self-custody)

**3. Institutional Investors** (Same UI - future: advanced features)
- Same interface as retail (Phase 1)
- Future: Bulk investment API, custom reporting, white-glove service

**4. Platform Admins**
Recommended permissions structure:
- **Super Admin**: Full system access, user management, fund withdrawals
- **Compliance Officer**: Campaign approval/rejection, KYC review, freeze accounts
- **Finance Manager**: Fee management, distribution processing, treasury operations
- **Support Agent**: User support tickets, document verification, basic account management
- **AI Manager**: Model training, decision review, AI parameter tuning
- **Developer**: Smart contract deployment, system maintenance, API management

**5. AI Investment Manager (Automated Role)**
- Read access to all campaign data
- Write access to recommendation database
- Cannot execute investments (Phase 1)
- Logs all decisions for audit trail

### Fundraising Lifecycle

**Campaign States:**
1. **Draft**: Company creates, edits freely
2. **Submitted for Review**: Admin notified, company cannot edit
3. **Under Review**: Admin evaluating, can request changes
4. **Approved/Live**: Accepting investments, countdown timer active
5. **Funded**: Goal reached, funds in escrow
6. **Closed**: Distribution complete, tokens issued
7. **Rejected**: Admin declined, reason provided

**Campaign Parameters:**
- **Minimum Raise**: $50,000 USD equivalent
- **Maximum Raise**: $5,000,000 USD equivalent (Phase 1 - regulatory safe harbor)
- **Funding Duration**: Fixed periods (30, 60, 90 days - company chooses)
- **All-or-Nothing**: Yes (funding goal must be met)
- **Overfunding**: Allowed up to 150% of target (hard cap)

**Escrow Mechanism:**
- **Smart Contract Multi-Sig**: 3-of-5 signature requirement
- **Signers**: Platform (2 keys), Company (1 key), Independent Auditor (1 key), Investor Representative (1 key)
- **Release Conditions**: Goal met + compliance checks passed + milestone achieved
- **Refund Process**: Automatic if goal not met within funding period
- **Partial Funding**: Not allowed (all-or-nothing model)

**Milestone-Based Release:**
- Companies can propose milestone schedules (e.g., 30% at close, 40% at product launch, 30% at revenue target)
- Investors vote on milestone achievement
- Requires 66% investor approval to release tranche

### Payment Infrastructure

**Stablecoins Supported:**
- **USDC** (Circle - primary, highest liquidity)
- **USDT** (Tether - widely adopted in Asia)

**Chain-Specific Stablecoins:**
- Solana: USDC (SPL), USDT (SPL)
- Ethereum: USDC (native), USDT (native)
- Sui: USDC (Wormhole), USDT (Wormhole)

**Fiat On-Ramps (Phase 1):**
- **Stripe**: Credit/debit cards (Visa, Mastercard) - 2.9% + $0.30 fee
- **Transak**: Bank transfer, local payment methods (Asia-focused)
- **MoonPay**: 150+ countries, compliance-first

**Custody Model:**
- **Self-Custody**: Users control private keys (Phantom, MetaMask, Sui Wallet)
- **Wallet Abstraction**: Email/social login with embedded wallets (future - Web3Auth, Magic)
- **Platform Wallet**: Optional for beginners (non-custodial under the hood)
- **Hardware Wallet Support**: Ledger, Trezor integration

**Bank Account Strategy:**
- **Phase 1**: Crypto-only (no fiat bank accounts)
- **Phase 2**: Fiat accounts in Singapore (DBS, OCBC) and Hong Kong (HSBC, Standard Chartered)

### Scale & Performance Requirements

**User Capacity:**
- **Concurrent Users**: 5,000 simultaneous users
- **Total Users**: 100,000 in Year 1, 500,000 in Year 2
- **Active Campaigns**: 50-100 concurrent campaigns

**Transaction Volume:**
- **Investment Transactions**: 100 TPS peak (credit card checkout flow)
- **Blockchain Transactions**: Delegated to Solana (65K TPS capacity)
- **API Requests**: 10,000 requests/minute

**Geographic Distribution:**
- **Primary Regions**: Southeast Asia (50%), East Asia (30%), Middle East (20%)
- **CDN Strategy**: Cloudflare global network with edge caching
- **Data Residency**: Singapore (primary), Hong Kong (backup)

**Performance SLAs:**
- **Page Load Time**: <2 seconds (desktop), <3 seconds (mobile)
- **API Response Time**: <200ms (p95), <500ms (p99)
- **Blockchain Confirmation**: <5 seconds (Solana finality)
- **Uptime**: 99.9% (43 minutes downtime/month allowed)

**Data Retention:**
- **Transaction Data**: 7 years (regulatory requirement)
- **User Activity Logs**: 1 year
- **AI Training Data**: 3 years
- **Campaign Data**: Indefinite (archival)
