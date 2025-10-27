# Product Requirements Document (PRD)
# Elevate Finance: AI-Enabled DeFi Token & Equity Crowdfunding Platform

**Document Version:** 1.0
**Last Updated:** October 27, 2025
**Document Owner:** Product Team
**Status:** Draft

---

## 1. Executive Summary

### 1.1 Project Vision and Mission

**Vision Statement**

Elevate Finance will become the leading tokenized investment platform in Asia, democratizing access to capital for high-growth SMEs and startups while providing retail and institutional investors with AI-powered investment intelligence and unprecedented liquidity through blockchain technology.

**Mission Statement**

To bridge the $2.5 trillion SME financing gap in Asia by combining blockchain tokenization, real-world asset (RWA) backing, and institutional-grade AI analysis—enabling companies to raise funds seamlessly while giving investors access to curated, data-driven investment opportunities previously reserved for venture capitalists.

**Core Problem We Solve**

1. **For Companies:** Traditional fundraising is slow (6-12 months), expensive (10-15% in fees), geographically limited, and requires extensive networks
2. **For Investors:** Limited access to pre-IPO deals, information asymmetry, illiquidity (7-10 year lock-ups), high minimum investments ($50K-$500K)
3. **For Markets:** Fragmented regulatory environments, lack of transparency, limited secondary market infrastructure

**Our Solution**

A blockchain-native platform that tokenizes equity and real-world assets, leverages AI for due diligence and recommendations, and provides regulatory-compliant infrastructure for cross-border capital formation with built-in liquidity mechanisms.

---

### 1.2 Target Market and Opportunity Size

**Primary Target Markets (Phase 1: Years 1-2)**

| Country/Region | Market Focus | Regulatory Framework | Go-Live Priority |
|----------------|--------------|---------------------|------------------|
| **Singapore** | Fintech hub, SME-friendly | MAS (Securities & Futures Act) | Q1 2026 (Launch) |
| **Hong Kong** | Gateway to China, APAC wealth | SFC (Securities Ordinance) | Q2 2026 |
| **UAE** | Middle East hub, crypto-friendly | VARA (Virtual Asset Regulatory Authority) | Q3 2026 |
| **Thailand** | Growing startup ecosystem | SEC Thailand (Digital Asset Act) | Q4 2026 |
| **Malaysia** | Islamic finance integration | SC Malaysia (Capital Markets Act) | Q1 2027 |
| **Indonesia** | Largest SEA population (275M) | OJK + Bappebti | Q2 2027 |

**Market Opportunity Size**

**TAM (Total Addressable Market): $847 Billion**
- Asia-Pacific alternative financing market: $392B (2024)
- Global security token market projection: $16T by 2030 (Asia share: ~35% = $5.6T)
- Conservative 3-year addressable slice: **$847B**

**SAM (Serviceable Addressable Market): $127 Billion**
- Target segment: SMEs and startups raising $50K-$5M
- Asia SME funding gap: $2.5T (Source: ADB 2023)
- Addressable through tokenization (5%): **$127B**

**SOM (Serviceable Obtainable Market): $2.5 Billion (Year 3)**
- Year 1 target: $150M in total fundraising volume (0.12% market share)
- Year 2 target: $750M (0.59% market share)
- Year 3 target: $2.5B (1.97% market share)

**User Acquisition Projections**

| Metric | Year 1 | Year 2 | Year 3 |
|--------|--------|--------|--------|
| **Total Registered Users** | 100,000 | 500,000 | 2,000,000 |
| **Active Investors** | 25,000 | 150,000 | 600,000 |
| **Companies Onboarded** | 200 | 1,000 | 3,500 |
| **Funded Campaigns** | 75 | 450 | 1,750 |
| **Average Raise per Campaign** | $2M | $1.67M | $1.43M |

---

### 1.3 Competitive Landscape

**Competitive Positioning Matrix**

| Platform | Type | Geography | AI Integration | Blockchain | Liquidity | Regulatory |
|----------|------|-----------|----------------|------------|-----------|------------|
| **Elevate Finance** | DeFi + RWA | Asia-first | ✅ Full AI | Solana (multi-chain ready) | Secondary market | MAS/SFC compliant |
| **Republic** | Equity Crowdfunding | US/Global | ❌ None | Ethereum (limited) | Limited | SEC Reg CF/A+ |
| **StartEngine** | Equity Crowdfunding | US-focused | ❌ None | ❌ None | Blockchain escrow only | SEC Reg CF/A+ |
| **Kickstarter** | Rewards-based | Global | ❌ None | ❌ None | N/A | Not securities |
| **Indiegogo** | Rewards/Equity | Global | ❌ None | ❌ None | N/A | Limited securities |
| **Securitize** | Tokenization Platform | Global | ❌ None | Multi-chain | DS Protocol | US/EU compliant |
| **INX** | Security Token Exchange | US/Global | ❌ None | Ethereum | ✅ Exchange | SEC registered |
| **Polymath** | Tokenization Protocol | Global | ❌ None | Polymesh | Limited | Framework only |

**Key Differentiators**

1. **AI Investment Manager** (Unique): Institutional-grade analysis democratized for retail investors—analyzes financials, sentiment, founder psychometrics, and provides explainable recommendations
2. **Asia-First Regulatory Compliance**: Purpose-built for MAS, SFC, VARA frameworks (not retrofitted from US regulations)
3. **RWA + Equity Hybrid**: Tokenizes both traditional equity AND real-world assets (IP, inventory, receivables)
4. **Retail-Friendly Economics**: $100 minimum investment vs. $500-$10,000 on competitors
5. **Built-in Liquidity**: 12-month lock-up with secondary market (vs. 5-10 year illiquidity on traditional platforms)
6. **Multi-Chain Strategy**: Solana (low fees) first, expanding to Ethereum/Sui (vs. single-chain competitors)

**Competitive Advantages**

| Advantage | Description | Moat Strength |
|-----------|-------------|---------------|
| **First-Mover in Asia RWA+AI** | No direct competitor combining AI, RWA tokenization, and Asia compliance | ⭐⭐⭐⭐⭐ High |
| **Proprietary AI Models** | Custom-trained models on Asian startup data (not available to competitors) | ⭐⭐⭐⭐ Medium-High |
| **Regulatory Licenses** | MAS CMS license creates 12-18 month barrier to entry | ⭐⭐⭐⭐⭐ Very High |
| **Network Effects** | More companies → More investors → Better AI training data → Better recommendations | ⭐⭐⭐⭐ Medium-High |
| **Tech Stack Efficiency** | Solana's 400ms finality and $0.00025 fees vs. Ethereum's 12s/$2+ | ⭐⭐⭐ Medium |

**Threats and Mitigation**

1. **Binance/Coinbase enters market**: Mitigation → Move fast on regulatory approvals, focus on AI differentiation
2. **Traditional VCs build competing platforms**: Mitigation → Lock in exclusivity partnerships with top accelerators (Y Combinator Asia, 500 Startups)
3. **Bear market reduces crypto adoption**: Mitigation → Fiat on-ramp prioritization, marketing as "equity platform with crypto benefits"

---

### 1.4 Success Metrics and KPIs

**North Star Metric: Total Value Locked (TVL)**
Target: $500M TVL by end of Year 3

**Primary KPIs (Business Health)**

| Category | Metric | Year 1 Target | Year 2 Target | Year 3 Target |
|----------|--------|---------------|---------------|---------------|
| **Revenue** | Platform Fees (2% of raises) | $3M | $15M | $50M |
| | Performance Fees (20% above hurdle) | $0.5M | $4M | $15M |
| | Transaction Fees (0.5% secondary) | $0.2M | $1.5M | $8M |
| | **Total Revenue** | **$3.7M** | **$20.5M** | **$73M** |
| **GMV** | Total Fundraising Volume | $150M | $750M | $2.5B |
| **Efficiency** | Campaign Success Rate | >60% | >70% | >75% |
| | Average Funding Time | <45 days | <35 days | <30 days |
| **Growth** | MoM User Growth Rate | 15% | 10% | 8% |
| | MoM GMV Growth Rate | 20% | 12% | 10% |

**Secondary KPIs (User Engagement)**

| Metric | Definition | Target (Year 1) | Target (Year 2) |
|--------|------------|-----------------|-----------------|
| **Investor Engagement** | | | |
| Conversion Rate (Visitor → Investor) | % of site visitors who invest | 2.5% | 4% |
| Average Investment Size | Median $ per transaction | $500 | $750 |
| Repeat Investment Rate | % of investors who invest 2+ times | 35% | 50% |
| Portfolio Diversification | Avg # of campaigns per investor | 3.2 | 5.1 |
| **Company Engagement** | | | |
| Application Completion Rate | % of started campaigns submitted | 65% | 75% |
| Time to First Investment | Days from campaign launch | <7 days | <5 days |
| Investor Update Frequency | Updates per month | 2.5 | 3.2 |
| **AI Performance** | | | |
| Recommendation Click-Through Rate | % of AI recs clicked | 25% | 35% |
| AI-Recommended Deal Success | % of AI-approved deals that fund | 75% | 80% |
| Risk Score Accuracy | Calibration error (Brier score) | <0.15 | <0.10 |

**Operational KPIs**

| Metric | Target | Measurement Frequency |
|--------|--------|----------------------|
| KYC Approval Time | <24 hours (avg) | Daily |
| Campaign Review Time | <5 business days | Weekly |
| Customer Support Response Time | <2 hours (business hours) | Daily |
| Platform Uptime | 99.9% | Real-time |
| Smart Contract Gas Optimization | <$0.50 per token issuance | Monthly |
| Fraud Detection Rate | >95% catch rate, <2% false positive | Weekly |

---

### 1.5 High-Level Roadmap

**Phase 1: MVP Launch & Validation (Months 1-6)**

**Q1 2026: Foundation**
- ✅ **Month 1-2:** Core platform development
  - User authentication (email, wallet, social)
  - Basic KYC integration (Sumsub/Onfido)
  - Campaign creation wizard (draft mode)
  - Smart contract development (SPL Token-2022)
  - Admin approval dashboard

- ✅ **Month 3-4:** Payment & Investment Flow
  - Phantom wallet integration
  - Stablecoin deposits (USDC, USDT)
  - Fiat on-ramp (Stripe integration)
  - Investment escrow smart contracts
  - Transaction history tracking

- ✅ **Month 5-6:** Launch Preparation
  - AI recommendation engine v1.0 (rule-based + basic ML)
  - Beta testing (50 users, 5 pilot companies)
  - MAS CMS license application submitted
  - Marketing website launch
  - **Milestone: Soft launch in Singapore**

**Q2 2026: Market Entry**
- 📍 **Month 7-8:** Singapore Operations
  - 10 campaigns live (target $20M total raise)
  - Investor acquisition campaigns (target 5,000 users)
  - AI feedback loop implementation
  - Secondary market v1.0 (P2P trading after lock-up)

- 📍 **Month 9-10:** Hong Kong Expansion
  - SFC compliance implementation
  - Cantonese language support
  - Hong Kong banking partnerships (HSBC/DBS)
  - Local PR and influencer partnerships

- 📍 **Month 11-12:** Optimization
  - AI model v2.0 (deep learning, sentiment analysis)
  - Mobile app launch (iOS/Android)
  - Enhanced analytics dashboards
  - **Milestone: $50M total GMV, 25,000 users**

---

**Phase 2: Scale & AI Enhancement (Months 7-18)**

**Q3 2026: Regional Expansion**
- UAE market entry (VARA license)
- Multi-language support (Arabic, Thai, Bahasa)
- Institutional investor onboarding (white-glove service)
- API for third-party integrations

**Q4 2026: Product Deepening**
- AI Investment Manager v3.0
  - Voice analysis integration (pitch deck sentiment)
  - Behavioral pattern recognition
  - Automated risk scoring (95% accuracy target)
- Milestone-based fund release (smart contract automation)
- Advanced portfolio analytics
- **Milestone: $200M GMV, 150,000 users**

**Q1 2027: Infrastructure Scaling**
- Multi-chain expansion (Ethereum, Sui)
- Decentralized identity (DID) integration
- On-chain governance (token holder voting)
- Institutional-grade custody (Fireblocks integration)

**Q2 2027: Advanced Features**
- AI-powered portfolio optimization
- Automated tax reporting (jurisdiction-specific)
- Fractional RWA tokenization (real estate, IP)
- **Milestone: $750M GMV, 500,000 users**

---

**Phase 3: Market Leadership & Innovation (Months 19-36)**

**Q3 2027: Platform Maturity**
- AI autonomous investment (up to $50K per deal)
- Cross-chain atomic swaps
- DeFi yield strategies for idle capital
- White-label platform for regional partners

**Q4 2027: Ecosystem Expansion**
- Elevate Finance DAO launch
- Native platform token (governance + utility)
- Grant program for developers ($5M fund)
- **Milestone: $1.5B GMV, 1M users**

**2028: Global Dominance**
- Latin America expansion (Brazil, Mexico)
- EU market entry (MiCA compliance)
- US consideration (post-regulatory clarity)
- Strategic acquisition of complementary platforms
- **Milestone: $2.5B GMV, 2M users, profitability**

---

**Dependency Timeline**

| Milestone | Dependencies | Risk Level |
|-----------|--------------|------------|
| **MVP Launch (Month 6)** | Smart contract audit, MAS license pending | 🟡 Medium |
| **Singapore Operations (Month 8)** | MAS license approval | 🔴 High |
| **Hong Kong Expansion (Month 10)** | SFC compliance, banking partner | 🟡 Medium |
| **AI v3.0 (Month 15)** | Sufficient training data (500+ campaigns) | 🟢 Low |
| **Multi-chain (Month 19)** | Ethereum bridge security audit | 🟡 Medium |

---

**Investment Requirements**

| Phase | Duration | Capital Required | Use of Funds |
|-------|----------|-----------------|--------------|
| **Phase 1 (MVP)** | Months 1-6 | $2.5M | Tech development (60%), licenses (20%), marketing (15%), operations (5%) |
| **Phase 2 (Scale)** | Months 7-18 | $8M | User acquisition (40%), tech (30%), compliance (15%), team expansion (15%) |
| **Phase 3 (Leadership)** | Months 19-36 | $15M | Marketing (35%), M&A (25%), infrastructure (20%), R&D (20%) |
| **Total** | 36 months | **$25.5M** | Fully diluted to Series A profitability |

---

**Key Assumptions**

1. MAS CMS license approved within 6-9 months
2. Average campaign raise: $2M (Year 1) declining to $1.4M (Year 3) as micro-campaigns grow
3. Campaign success rate: 60% (conservative vs. 75% industry average for vetted deals)
4. Crypto market remains stable or bullish (no prolonged bear market)
5. No major regulatory changes blocking tokenized securities in target markets
6. AI training data quality improves with scale (network effects kick in at 500+ campaigns)

---

**Success Criteria (End of Phase 1 - Month 6)**

- ✅ 50+ campaigns submitted
- ✅ 25+ campaigns funded
- ✅ $50M total capital raised
- ✅ 25,000 registered users
- ✅ 5,000 active investors
- ✅ MAS license approved (or pending with no red flags)
- ✅ <5% fraud/default rate
- ✅ 99.5%+ platform uptime
- ✅ AI recommendation accuracy >70%
- ✅ Net Promoter Score (NPS) >50

---

## 2. Market Analysis

### 2.1 Market Size & Growth Trajectory

**Global Context: The Tokenization Mega-Trend**

The tokenization of real-world assets (RWA) represents one of the most significant capital market innovations since the invention of the stock exchange. According to Boston Consulting Group (BCG), tokenized assets will reach **$16 trillion by 2030**, representing ~10% of global GDP.

**Asia-Pacific Opportunity Breakdown**

| Market Segment | 2024 Size | 2027 Projection | CAGR | Elevate's Addressable % |
|----------------|-----------|-----------------|------|------------------------|
| **Alternative Financing** | $392B | $687B | 18.2% | 18.5% ($127B) |
| Traditional crowdfunding | $114B | $167B | 13.6% | 0% (not our market) |
| Equity crowdfunding | $43B | $89B | 27.3% | 75% (direct competition) |
| P2P lending | $187B | $312B | 18.6% | 0% (debt, not equity) |
| Tokenized securities | $48B | $119B | 35.2% | 90% (our core market) |
| **SME Financing Gap** | $2.5T | $3.1T | 7.4% | 5% (tokenization-ready) |
| **Venture Capital (Asia)** | $89B | $142B | 16.8% | 12% (overlap with our market) |

**TAM Calculation (Conservative)**
```
Base TAM = Alternative Financing (2027) + 5% of SME Gap + 12% of VC
         = $687B + ($3.1T × 5%) + ($142B × 12%)
         = $687B + $155B + $17B
         = $859B (rounded to $847B for conservatism)
```

**SAM Calculation**
```
Filters applied:
1. Deal size: $50K - $5M (excludes micro-loans and large institutional deals)
2. Asset type: Equity + RWA tokenization (excludes pure debt)
3. Geography: 6 target markets (excludes rest of Asia-Pacific)
4. Regulatory readiness: Markets with clear digital asset frameworks

SAM = $859B × 14.8% (deal size filter) = $127B
```

**SOM Calculation (Year 3)**
```
Market penetration strategy:
- Year 1: 0.12% market share = $150M GMV
- Year 2: 0.59% market share = $750M GMV
- Year 3: 1.97% market share = $2.5B GMV

Rationale: Republic.com achieved $1.5B GMV in Year 5 (US only).
We're targeting faster growth due to:
1. Larger addressable market (Asia > US for SME financing)
2. AI-driven user acquisition efficiency
3. Multi-chain flexibility (lower barriers to entry)
```

---

**Country-Specific Market Analysis**

#### Singapore
- **Market Size**: $23B alternative financing (2024)
- **Regulatory Maturity**: ⭐⭐⭐⭐⭐ Very High (MAS Payment Services Act, Securities & Futures Act)
- **Blockchain Adoption**: 14% of population owns crypto (highest in APAC)
- **SME Population**: 273,000 SMEs (99% of all enterprises)
- **Key Insights**: Government-backed initiatives (Project Guardian, MAS FinTech Regulatory Sandbox) create favorable environment
- **Elevate's Target**: $50M GMV Year 1, $250M Year 3

#### Hong Kong
- **Market Size**: $31B alternative financing (2024)
- **Regulatory Maturity**: ⭐⭐⭐⭐ High (SFC Virtual Asset Trading Platform regime)
- **Blockchain Adoption**: 11% crypto ownership
- **SME Population**: 360,000 SMEs (98% of all enterprises)
- **Key Insights**: Gateway to mainland China wealth, strong fintech infrastructure
- **Elevate's Target**: $40M GMV Year 1, $200M Year 3

#### UAE (Dubai + Abu Dhabi)
- **Market Size**: $18B alternative financing (2024)
- **Regulatory Maturity**: ⭐⭐⭐⭐⭐ Very High (VARA in Dubai, ADGM in Abu Dhabi)
- **Blockchain Adoption**: 25% crypto ownership (global leader)
- **SME Population**: 410,000 SMEs (94% of all enterprises)
- **Key Insights**: Zero taxation on crypto, VARA full-stack licensing framework
- **Elevate's Target**: $30M GMV Year 1, $150M Year 3

#### Thailand
- **Market Size**: $27B alternative financing (2024)
- **Regulatory Maturity**: ⭐⭐⭐ Medium (SEC Digital Asset Act 2018, updated 2023)
- **Blockchain Adoption**: 8% crypto ownership
- **SME Population**: 3.1M SMEs (99.5% of all enterprises)
- **Key Insights**: Large SME base, growing startup ecosystem (21 unicorns by 2024)
- **Elevate's Target**: $15M GMV Year 1, $100M Year 3

#### Malaysia
- **Market Size**: $19B alternative financing (2024)
- **Regulatory Maturity**: ⭐⭐⭐ Medium (SC Capital Markets & Services Act, Islamic Finance)
- **Blockchain Adoption**: 6% crypto ownership
- **SME Population**: 1.2M SMEs (97% of all enterprises)
- **Key Insights**: Shariah-compliant tokenization opportunity (40% Muslim population)
- **Elevate's Target**: $10M GMV Year 1, $75M Year 3

#### Indonesia
- **Market Size**: $52B alternative financing (2024, largest in SEA)
- **Regulatory Maturity**: ⭐⭐ Medium-Low (OJK + Bappebti dual regulation)
- **Blockchain Adoption**: 4% crypto ownership (but 11M users in absolute terms)
- **SME Population**: 64M SMEs (99.99% of all enterprises)
- **Key Insights**: Massive population (275M), but regulatory complexity requires careful approach
- **Elevate's Target**: $5M GMV Year 1, $50M Year 3

---

### 2.2 Competitor Analysis

**Competitive Landscape Categories**

We face competition across four distinct categories:

1. **Traditional Equity Crowdfunding Platforms** (Indirect competition)
2. **Blockchain-Native Fundraising Platforms** (Direct competition)
3. **Security Token Exchanges** (Partial competition - liquidity layer)
4. **Tokenization Infrastructure Providers** (Potential partners or acquirers)

---

#### Category 1: Traditional Equity Crowdfunding

**Republic (US + Global)**
- **Founded**: 2016
- **Total Raised**: $1.5B+ across 500+ companies (as of 2024)
- **Business Model**: 2% platform fee + 6% carry on returns
- **Strengths**: Brand recognition, SEC compliance, large investor base (2M+ users)
- **Weaknesses**: US-centric, no AI, limited blockchain integration, 5-10 year illiquidity
- **Threat Level**: 🟡 Medium (may expand to Asia)

**StartEngine (US)**
- **Founded**: 2014
- **Total Raised**: $800M+ across 600+ companies
- **Business Model**: 6-8% of capital raised
- **Strengths**: High-volume campaigns, secondary trading (via blockchain registry)
- **Weaknesses**: No tokenization, limited international presence, no AI
- **Threat Level**: 🟢 Low (minimal Asia presence)

**Crowdcube (UK/EU)**
- **Founded**: 2011
- **Total Raised**: £1.5B+ across 1,200+ companies
- **Business Model**: 7% success fee
- **Strengths**: Established European network, strong compliance
- **Weaknesses**: No Asia operations, no blockchain, traditional equity only
- **Threat Level**: 🟢 Low (geographic non-overlap)

**Seedrs (UK, acquired by Republic in 2021)**
- **Status**: Now part of Republic's European expansion
- **Significance**: Consolidation trend in the industry

---

#### Category 2: Blockchain-Native Fundraising

**DAO Maker (Global, Web3 focus)**
- **Founded**: 2017
- **Total Raised**: $300M+ (primarily crypto projects)
- **Business Model**: Token sales, IDO launchpad
- **Strengths**: Strong crypto community, multi-chain (Ethereum, BSC, Polygon)
- **Weaknesses**: Crypto-native only (not RWA/equity), regulatory grey area, no AI
- **Threat Level**: 🟢 Low (different target market: crypto projects vs. traditional SMEs)

**Tokensoft (US)**
- **Founded**: 2017
- **Total Raised**: $500M+ (infrastructure + client raises)
- **Business Model**: SaaS + revenue share
- **Strengths**: Compliance-first, institutional clients (Coinbase, Circle)
- **Weaknesses**: US-only, no retail platform, no AI
- **Threat Level**: 🟡 Medium (could partner with Asian platforms)

**Securitize (Global)**
- **Founded**: 2017
- **Total Raised**: $700M+ tokenized (e.g., KoreConX, ASPD)
- **Business Model**: Tokenization-as-a-service (TaaS)
- **Strengths**: Multi-chain infrastructure, strong compliance (SEC/EU)
- **Weaknesses**: B2B focus (not investor-facing marketplace), no AI, expensive ($50K+ setup fees)
- **Threat Level**: 🟡 Medium (potential partner or competitor if they launch consumer platform)

---

#### Category 3: Security Token Exchanges

**INX (US/Global)**
- **Founded**: 2017
- **Status**: SEC-registered broker-dealer + ATS (Alternative Trading System)
- **Strengths**: Full regulatory approval, secondary market liquidity
- **Weaknesses**: Limited primary issuance, high compliance costs, no Asia license
- **Threat Level**: 🟡 Medium (if they enter Asia)

**tZero (US, Overstock subsidiary)**
- **Founded**: 2018
- **Status**: SEC-registered ATS
- **Strengths**: Established secondary market, institutional backing
- **Weaknesses**: US-only, declining activity (pivoting away from retail)
- **Threat Level**: 🟢 Low (exiting retail market)

---

#### Category 4: Tokenization Infrastructure

**Polymath / Polymesh**
- **Product**: Blockchain infrastructure for security tokens
- **Business Model**: Protocol usage fees
- **Relevance**: Potential blockchain partner for Phase 2 multi-chain expansion
- **Threat Level**: 🟢 Low (infrastructure player, not direct competitor)

**Fireblocks**
- **Product**: Institutional custody + tokenization APIs
- **Business Model**: SaaS ($25K+ annual)
- **Relevance**: Potential custody partner for institutional tier
- **Threat Level**: 🟢 Low (infrastructure player)

---

**Competitive Comparison Matrix (Detailed)**

| Feature | Elevate Finance | Republic | Securitize | INX | DAO Maker |
|---------|----------------|----------|------------|-----|-----------|
| **Primary Markets** | Asia (6 countries) | US, EU | US, EU | US | Global (crypto) |
| **Asset Classes** | Equity, RWA, IP | Equity, debt | Equity, debt, funds | Equity, tokens | Tokens only |
| **Blockchain Integration** | ✅ Full (Solana → multi-chain) | ⚠️ Limited (registry) | ✅ Full (multi-chain) | ✅ Full (Ethereum) | ✅ Full (multi-chain) |
| **AI Investment Tools** | ✅ Full AI manager | ❌ None | ❌ None | ❌ None | ❌ None |
| **Minimum Investment** | $100 | $100 | $500-$10,000 | $1,000 | $100 (crypto) |
| **Liquidity** | 12-month lock-up + secondary | 5-year+ illiquid | Varies (DS Protocol) | ✅ Active exchange | ✅ High (DEX) |
| **Regulatory Status** | MAS/SFC pending | SEC Reg CF/A+ | SEC/EU compliant | SEC ATS | ⚠️ Unclear |
| **Target Users** | Retail + institutions | Retail + accredited | Institutions | Accredited | Crypto natives |
| **Platform Fees** | 2% + 20% carry | 2% + 6% carry | 5-10% | 0.5% trading | 3-10% IDO |
| **KYC/AML** | ✅ Enhanced (Sumsub) | ✅ Standard | ✅ Enhanced | ✅ Institutional | ⚠️ Varies |
| **Secondary Market** | ✅ Built-in (Phase 2) | ❌ None (Republic Note) | ⚠️ DS Protocol (limited) | ✅ Primary feature | ✅ DEX trading |

---

**Key Insights from Competitive Analysis**

1. **No Direct Asia-First Competitor**: All major platforms are US/EU-centric, creating first-mover advantage
2. **AI is Untapped**: Zero competitors offer AI-powered investment recommendations
3. **Liquidity Gap**: Most platforms offer poor secondary market access (our differentiator)
4. **Regulatory Arbitrage**: Asia's progressive crypto regulations (UAE, Singapore) provide advantages over SEC's strict stance
5. **Tokenization Cost**: Competitors charge $50K-$500K for tokenization; we can offer self-service at $0 (subsidized by 2% platform fee)

---

### 2.3 User Personas

We've identified **five primary personas** and **two secondary personas** based on behavioral research, market interviews, and competitive benchmarking.

---

#### Persona 1: The Ambitious Founder (Company/Issuer)

**Demographics**
- **Name Archetype**: Sarah Tan (Singapore), Arjun Patel (India-UAE), Wei Chen (Hong Kong)
- **Age**: 28-42
- **Education**: Bachelor's or Master's in Business, Engineering, or STEM
- **Location**: Singapore (35%), Hong Kong (25%), UAE (20%), Thailand/Malaysia (15%), Indonesia (5%)
- **Company Stage**: Pre-seed to Series A ($50K-$5M fundraising need)

**Psychographics**
- **Goals**: Raise capital quickly (<90 days), access global investor base, maintain control (prefer equity over debt)
- **Pain Points**:
  - Traditional VC process takes 6-12 months
  - Bank loans require collateral they don't have
  - Angel investors demand board seats
  - Regional VCs focus on "hot" sectors only (AI, fintech) — other sectors struggle
- **Motivations**: Speed to market, valuation control, avoiding dilution to single investor
- **Tech Savviness**: High (80% have used crypto wallets, 60% understand smart contracts)

**Behavioral Patterns**
- **Research Approach**: Spends 2-3 weeks comparing platforms before applying
- **Decision Factors** (ranked): 1) Success rate, 2) Time to funding, 3) Platform fees, 4) Investor quality
- **Information Sources**: Y Combinator blogs, TechCrunch, Hacker News, Telegram/Discord communities
- **Objections**:
  - "Will tokenization complicate my cap table?"
  - "What if investors dump tokens immediately after lock-up?"
  - "Is this legally compliant with my country's securities laws?"

**Jobs to Be Done**
1. **Primary Job**: Raise capital without giving up board control or excessive equity
2. **Secondary Jobs**: Build investor community, validate product-market fit, gain PR/visibility
3. **Tertiary Jobs**: Network with other founders, access mentorship

**Success Metrics (Founder's POV)**
- Funding goal reached in <60 days
- Investor diversification (50+ small investors > 1 large investor)
- Positive PR coverage from campaign
- Post-campaign investor engagement (updates read rate >40%)

**Elevate's Value Proposition**
- **Speed**: 30-45 day average funding time (vs. 6 months traditional VC)
- **Control**: No board seats required, keep 100% operational control
- **Global Access**: Investors from 50+ countries (not limited to local VCs)
- **AI Credibility**: AI endorsement = "institutional stamp of approval" for investors

---

#### Persona 2: The Savvy Retail Investor (Primary Investor)

**Demographics**
- **Name Archetype**: Jason Lim (Singapore millennial), Priya Kumar (UAE professional), David Wong (HK finance worker)
- **Age**: 25-45
- **Income**: $50K-$200K annual (upper-middle class)
- **Education**: Bachelor's degree (70%), Master's (25%)
- **Location**: Singapore (30%), Hong Kong (25%), UAE (20%), Thailand (15%), Malaysia (10%)
- **Investment Experience**: 3-10 years in stocks/crypto, 0-2 years in alternatives

**Psychographics**
- **Goals**: Diversify beyond stocks/crypto, access "insider" deals, build passive income, be part of startup success stories
- **Pain Points**:
  - VCs and angel networks are "old boys clubs" (invite-only)
  - Minimum investments too high ($50K-$500K)
  - No transparency in traditional private equity
  - Fear of being "exit liquidity" for insiders
- **Motivations**: FOMO on startup success, desire for higher returns than index funds (8%+ vs. 7% S&P 500), status (being an "investor")
- **Tech Savviness**: High (100% have crypto wallets, 75% have traded NFTs or DeFi)

**Behavioral Patterns**
- **Investment Style**: Portfolio approach (prefer 5-10 small investments vs. 1 large bet)
- **Research Depth**: Reads pitch deck + watches video (15 min), checks AI score, reads 2-3 investor comments
- **Decision Timeline**: 3-7 days from discovery to investment
- **Average Investment**: $500-$1,500 per campaign
- **Risk Tolerance**: Medium-high (comfortable with 50% loss if 2-3x upside potential)

**Jobs to Be Done**
1. **Primary Job**: Generate higher returns than traditional investments (target: 15-25% annual)
2. **Secondary Jobs**: Learn about emerging industries, network with founders, feel like "smart money"
3. **Tertiary Jobs**: Diversify across geographies, support causes/sectors I believe in

**Success Metrics (Investor's POV)**
- Portfolio IRR >15% annually
- At least 2 "home runs" (5-10x returns) every 3 years
- Regular updates from companies (prefer quarterly)
- Ability to exit within 18-24 months (12-month lock-up + 6-12 months secondary trading)

**Objections**
- "How do I know this isn't a scam?"
- "What if the company fails — do I lose everything?"
- "Why should I trust the AI recommendations?"
- "Can I actually sell my tokens after the lock-up?"

**Elevate's Value Proposition**
- **AI Due Diligence**: Don't spend 10 hours researching — AI analyzes 50+ data points in seconds
- **Low Minimum**: Start with $100, build portfolio gradually
- **Transparency**: Full financials, founder backgrounds, AI risk scores
- **Liquidity**: 12-month lock-up (vs. 7-10 years in traditional PE) + secondary market

---

#### Persona 3: The Institutional Investor (Whale)

**Demographics**
- **Name Archetype**: Family Office Manager, Venture Debt Fund, Corporate VC Arm
- **AUM**: $10M-$500M
- **Location**: Singapore (40%), Hong Kong (35%), UAE (15%), Other (10%)
- **Investment Mandate**: Alternative assets allocation (5-15% of portfolio)

**Psychographics**
- **Goals**: Deal flow, co-investment opportunities, data-driven sourcing
- **Pain Points**:
  - Too many inbound pitches (500+/year), need filtering
  - Due diligence costs $10K-$50K per deal
  - Limited exposure to micro-cap deals ($500K-$2M)
- **Motivations**: Alpha generation, early access to unicorns, portfolio diversification

**Behavioral Patterns**
- **Investment Style**: Lead investor or co-lead (10-30% of round)
- **Ticket Size**: $50K-$500K per deal
- **Research Depth**: Full due diligence (financials, legal, IP review) — 2-4 weeks
- **Decision Timeline**: 30-60 days from discovery to wire transfer

**Jobs to Be Done**
1. **Primary Job**: Source deals competitors don't see
2. **Secondary Jobs**: Leverage AI for pipeline prioritization, reduce due diligence costs
3. **Tertiary Jobs**: Signal credibility to LPs (show data-driven process)

**Success Metrics**
- Portfolio DPI (Distributed to Paid-In) >2.0x
- Top quartile IRR vs. peer funds
- 60%+ of deals reach Series A

**Elevate's Value Proposition (Phase 2)**
- **API Access**: Programmatic deal flow filtering
- **AI Scoring**: Pre-vetted opportunities (only see top 10%)
- **Co-Investment Rights**: Lead rounds alongside retail (price discovery benefit)

---

#### Persona 4: The Compliance Officer (Internal Admin)

**Demographics**
- **Role**: Head of Compliance, Risk Manager, Legal Counsel
- **Age**: 35-55
- **Experience**: 10-20 years in financial services, law, or regulatory affairs
- **Location**: Singapore HQ (primary), Remote (secondary)

**Psychographics**
- **Goals**: Prevent regulatory violations, minimize platform risk, maintain license
- **Pain Points**:
  - Manual KYC review (50+ applications/day)
  - False positives in sanctions screening
  - Staying updated on changing regulations across 6 jurisdictions
- **Motivations**: Career protection (avoid fines), efficiency (reduce manual work)

**Jobs to Be Done**
1. **Primary Job**: Approve/reject campaigns and users without legal risk
2. **Secondary Jobs**: Generate audit reports for regulators, monitor suspicious activity
3. **Tertiary Jobs**: Train AI models on compliance patterns

**Elevate's Value Proposition**
- **Automated Workflows**: KYC/AML rules engine (reduce manual review by 70%)
- **Audit Trails**: Immutable blockchain records
- **Jurisdiction Customization**: Country-specific compliance rules

---

#### Persona 5: The Platform Admin (Internal Operations)

**Demographics**
- **Role**: Customer Success Manager, Finance Ops, AI Manager
- **Age**: 25-40
- **Experience**: 3-10 years in fintech, operations, or data science

**Psychographics**
- **Goals**: Operational efficiency, user satisfaction, system uptime
- **Pain Points**: Manual data entry, user support tickets (500+/week), AI model drift
- **Motivations**: Career growth, learning cutting-edge tech, bonus tied to KPIs

**Jobs to Be Done**
1. **Primary Job**: Keep platform running smoothly (99.9% uptime)
2. **Secondary Jobs**: Improve user metrics (NPS, conversion rate)
3. **Tertiary Jobs**: Optimize AI models, reduce operational costs

**Elevate's Value Proposition**
- **Admin Dashboard**: Single pane of glass for all operations
- **AI Explainability**: Understand why AI made recommendations
- **Automation**: Reduce manual tasks (e.g., distribution payouts, investor updates)

---

### 2.4 Pain Points & Solutions

**Mapping Pain Points to Product Features**

| User Persona | Top 3 Pain Points | Elevate's Solution | Feature Priority |
|--------------|-------------------|-------------------|------------------|
| **Ambitious Founder** | 1. Slow fundraising (6-12 months)<br>2. High costs (10-15% fees)<br>3. Geographic limitations | 1. 30-45 day funding cycles<br>2. 2% platform fee<br>3. Global investor access | 🔴 P0 (MVP) |
| | 4. Cap table complexity<br>5. Lack of investor engagement post-funding | 4. Automated tokenized cap table<br>5. Built-in investor update tools | 🟡 P1 (Phase 2) |
| **Savvy Retail Investor** | 1. Information asymmetry (no access to due diligence)<br>2. High minimums ($50K+)<br>3. Illiquidity (7-10 years) | 1. AI-powered analysis + transparent data<br>2. $100 minimum<br>3. 12-month lock-up + secondary market | 🔴 P0 (MVP) |
| | 4. Scam risk<br>5. Tax reporting complexity | 4. AI fraud detection + KYC<br>5. Automated tax statements | 🟡 P1 (Phase 2) |
| **Institutional Investor** | 1. Deal flow overload (500+ pitches/year)<br>2. High due diligence costs ($10K-$50K)<br>3. Limited micro-cap exposure | 1. AI-filtered top 10% deals<br>2. Shared due diligence reports<br>3. Co-investment marketplace | 🟠 P2 (Phase 3) |
| **Compliance Officer** | 1. Manual KYC review (hours/day)<br>2. Multi-jurisdiction complexity<br>3. Audit trail gaps | 1. Automated KYC workflows<br>2. Country-specific rule engines<br>3. Blockchain audit logs | 🔴 P0 (MVP) |
| **Platform Admin** | 1. Operational inefficiency<br>2. User support load<br>3. AI model management | 1. Admin dashboard automation<br>2. Self-service knowledge base<br>3. AI explainability tools | 🟡 P1 (Phase 2) |

---

### 2.5 Regulatory Landscape by Country

**Overview of Regulatory Frameworks**

Elevate Finance operates in a **complex multi-jurisdictional environment**. Below is a detailed analysis of each target market's regulatory requirements.

---

#### Singapore (Primary Launch Market)

**Regulatory Bodies**
- **MAS (Monetary Authority of Singapore)**: Primary regulator for securities and payment services
- **ACRA (Accounting and Corporate Regulatory Authority)**: Company registration

**Applicable Laws**
1. **Securities and Futures Act (SFA)**: Governs issuance of securities (equity tokens qualify as "securities")
2. **Payment Services Act (PSA)**: Regulates digital payment token services
3. **Personal Data Protection Act (PDPA)**: Data privacy compliance

**Licensing Requirements**
- **CMS License (Capital Markets Services)**: Required for operating a platform facilitating securities offerings
  - **Type**: Dealing in securities, advising on corporate finance
  - **Application Timeline**: 6-12 months
  - **Costs**: $50K-$150K (legal + compliance setup)
  - **Net Tangible Assets**: Minimum $250K SGD
- **Alternative**: MAS Fintech Regulatory Sandbox (faster approval, 6-month pilot, then full license)

**Key Regulations**
- **Prospectus Exemptions**:
  - Small offers exemption: Raises ≤ $5M SGD in 12 months (no prospectus needed)
  - Institutional/accredited investors exemption
- **KYC/AML**: Enhanced due diligence required (liveness check, sanctions screening via ACRA BizFile)
- **Investor Limits**:
  - Up to 50 non-accredited investors per offer (without prospectus)
  - Unlimited accredited investors
- **Custody Requirements**: Client assets must be held in trust account or statutory trust

**Tokenization-Specific Rules**
- **Project Guardian (MAS Initiative)**: Pilot program for tokenized assets (we should apply)
- **DPT Exemption**: Digital Payment Tokens (like utility tokens) are exempt from SFA if not representing ownership/debt
- **Transfer Restrictions**: Must implement smart contract whitelisting for investor accreditation checks

**Timeline & Risk Assessment**
- **Best Case**: 6 months (via sandbox)
- **Realistic**: 9-12 months (standard CMS license)
- **Risk Level**: 🟡 Medium (MAS is progressive but thorough)

**Compliance Costs (Annual)**
- License renewal: $10K
- Audit requirements: $30K (annual financial audit)
- Compliance officer salary: $80K-$120K
- **Total**: ~$150K/year

---

#### Hong Kong (Secondary Launch Market)

**Regulatory Bodies**
- **SFC (Securities and Futures Commission)**: Securities regulator
- **HKMA (Hong Kong Monetary Authority)**: Banking and payment systems
- **PCPD (Privacy Commissioner for Personal Data)**: Data protection

**Applicable Laws**
1. **Securities and Futures Ordinance (SFO)**: Governs securities offerings
2. **Anti-Money Laundering Ordinance (AMLO)**: KYC/AML requirements
3. **Personal Data (Privacy) Ordinance (PDPO)**: Data privacy

**Licensing Requirements**
- **Type 1 License (Dealing in Securities)**: Required for operating investment platform
  - **Application Timeline**: 6-9 months
  - **Costs**: $60K-$200K (higher than Singapore due to legal complexity)
  - **Paid-Up Capital**: Minimum $5M HKD (~$640K USD)
- **Type 6 License (Advising on Corporate Finance)**: If providing investment advice (optional for MVP)

**Key Regulations**
- **Prospectus Requirements**:
  - Offers to >50 investors require prospectus
  - Small-scale exemption: <50 investors in 12 months
- **Professional Investors Only (Initial Phase)**:
  - Recommend limiting to professional investors (net worth >$8M HKD) in Phase 1
  - Retail access in Phase 2 (after regulatory clarity)
- **Virtual Asset Regulations (June 2023 Update)**:
  - SFC issued guidelines for tokenized securities
  - Must comply with VATP (Virtual Asset Trading Platform) regime if offering secondary trading
- **Custody**: Must use SFC-licensed custodians (e.g., HashKey, OSL)

**Timeline & Risk Assessment**
- **Best Case**: 6 months (professional investors only)
- **Realistic**: 9-12 months
- **Risk Level**: 🟡 Medium (SFC is cautious but clear)

**Compliance Costs (Annual)**
- License renewal: $15K HKD (~$2K USD)
- Audit + compliance: $50K USD
- **Total**: ~$100K/year

---

#### UAE (Dubai VARA + Abu Dhabi ADGM)

**Regulatory Bodies (Two Options)**

**Option A: Dubai (VARA - Virtual Assets Regulatory Authority)**
- **Jurisdiction**: Dubai only
- **Focus**: Crypto-native, DeFi-friendly
- **Timeline**: 3-6 months (fastest in region)
- **Costs**: $50K-$100K

**Option B: Abu Dhabi (ADGM - Abu Dhabi Global Market)**
- **Jurisdiction**: Abu Dhabi + international passporting
- **Focus**: Traditional finance + tokenization
- **Timeline**: 6-9 months
- **Costs**: $100K-$200K

**Recommendation**: Start with **VARA (Dubai)** for speed, add ADGM in Phase 2 for institutional credibility.

**VARA Licensing (Dubai)**
- **License Type**: Virtual Asset Service Provider (VASP) — Broker-Dealer + Exchange
- **Requirements**:
  - Operational Readiness Assessment (ORA): 3-month review
  - AML/CFT compliance program
  - Cybersecurity audit (ISO 27001 recommended)
  - Minimum capital: $100K USD equivalent (AED 367K)

**Key Regulations**
- **Token Classification**:
  - Security tokens = "Qualifying Virtual Assets" (regulated)
  - Utility tokens = "Virtual Assets" (lighter regulation)
- **Investor Protection**:
  - Retail access allowed (no accreditation requirement)
  - Mandatory risk disclosures
  - Cooling-off period: 14 days for retail investors
- **Tax Benefits**: 0% corporate tax, 0% capital gains tax (major advantage)

**Timeline & Risk Assessment**
- **Best Case**: 3 months (VARA)
- **Realistic**: 6 months
- **Risk Level**: 🟢 Low (VARA is fast and clear)

**Compliance Costs (Annual)**
- License renewal: $20K
- Audit: $30K
- **Total**: ~$80K/year

---

#### Thailand

**Regulatory Bodies**
- **SEC Thailand**: Securities regulator
- **BOT (Bank of Thailand)**: Payment systems
- **PDPC (Personal Data Protection Commission)**: Data privacy

**Applicable Laws**
1. **Securities and Exchange Act B.E. 2535 (1992)**
2. **Emergency Decree on Digital Asset Businesses B.E. 2561 (2018)** — updated 2023
3. **Personal Data Protection Act (PDPA) B.E. 2562 (2019)**

**Licensing Requirements**
- **Digital Asset Business License**:
  - **Type**: Digital Asset Broker + Portal Operator
  - **Timeline**: 6-12 months
  - **Costs**: $40K-$80K
  - **Capital Requirement**: 5M THB (~$140K USD)

**Key Regulations**
- **Investment Limits (Retail)**:
  - ≤250K THB ($7K) per investor per project (without accreditation)
  - Unlimited for high-net-worth investors (>30M THB assets)
- **ICO Portal Rules**:
  - Must conduct due diligence on issuers
  - Smart contract audit required (SEC-approved auditors only)
  - Escrow with local bank mandatory
- **KYC/AML**: AMLO compliance (Thai AMLO Act B.E. 2542)

**Timeline & Risk Assessment**
- **Best Case**: 6 months
- **Realistic**: 9-12 months
- **Risk Level**: 🟡 Medium (bureaucratic but straightforward)

**Compliance Costs (Annual)**
- License renewal: $10K
- Audit: $25K
- **Total**: ~$60K/year

---

#### Malaysia

**Regulatory Bodies**
- **SC Malaysia (Securities Commission)**: Securities regulator
- **BNM (Bank Negara Malaysia)**: Central bank
- **PDPD (Personal Data Protection Department)**: Data privacy

**Applicable Laws**
1. **Capital Markets and Services Act 2007 (CMSA)**
2. **Guidelines on Digital Assets (Amended January 2024)**
3. **Personal Data Protection Act 2010 (PDPA)**

**Licensing Requirements**
- **IEO Operator License (Initial Exchange Offering)**:
  - New license category (introduced 2024)
  - **Timeline**: 6-9 months
  - **Costs**: $30K-$60K
  - **Capital**: 3M MYR (~$640K USD) — high barrier

**Key Regulations**
- **Shariah Compliance** (Optional but Recommended):
  - 40% of population is Muslim — Shariah-compliant tokenization unlocks larger market
  - SC Malaysia has Shariah Advisory Council (SAC)
  - Requirements: No interest (riba), no gambling (maisir), no uncertainty (gharar)
  - Solution: Profit-sharing structures instead of interest-bearing notes
- **Investor Limits**:
  - Sophisticated investors: >3M MYR income or >3M MYR net assets
  - Retail: ≤20K MYR per issuer per year
- **Token Custody**: Must use SC-licensed custodians

**Timeline & Risk Assessment**
- **Best Case**: 6 months
- **Realistic**: 9-12 months
- **Risk Level**: 🟡 Medium (high capital requirement)

**Compliance Costs (Annual)**
- License renewal: $8K
- Shariah audit (if applicable): $15K
- **Total**: ~$50K/year

---

#### Indonesia

**Regulatory Bodies**
- **OJK (Otoritas Jasa Keuangan)**: Financial Services Authority
- **Bappebti (Commodity Futures Trading Regulatory Agency)**: Crypto assets regulator
- **Kominfo**: Ministry of Communication and Informatics

**Applicable Laws**
1. **Law No. 4/2023 on Development and Strengthening of Financial Sector**
2. **Bappebti Regulation No. 8/2021 on Crypto Asset Trading**
3. **OJK Regulation on Equity Crowdfunding (POJK 57/2020)**

**Licensing Requirements (Dual Path)**

**Path 1: OJK Equity Crowdfunding License**
- **For**: Traditional equity offerings
- **Timeline**: 6-12 months
- **Costs**: $25K-$50K
- **Capital**: 2.5B IDR (~$160K USD)
- **Limitations**: No tokenization allowed (traditional shares only)

**Path 2: Bappebti Crypto Asset Trader License**
- **For**: Tokenized assets (treated as "crypto assets")
- **Timeline**: 12-18 months (slower, newer framework)
- **Costs**: $50K-$100K
- **Capital**: 100B IDR (~$6.4M USD) — **VERY HIGH BARRIER**
- **Limitations**: Crypto-native users only (limits mainstream adoption)

**Recommendation**: **Delay Indonesia to Phase 2** (Q2 2027) after regulatory clarity improves. Start with OJK ECF license (non-tokenized), add tokenization in Phase 3.

**Key Regulations**
- **Investment Limits (Retail)**:
  - ≤5M IDR (~$320) per investor per year (very restrictive)
  - High-net-worth: >10B IDR assets
- **Local Partner Requirement**: Must have Indonesian entity (PT PMA - foreign investment company)
- **Data Localization**: All user data must be stored on servers in Indonesia (AWS Jakarta region)

**Timeline & Risk Assessment**
- **Best Case**: 12 months (OJK ECF)
- **Realistic**: 18-24 months (tokenization path)
- **Risk Level**: 🔴 High (regulatory complexity, high capital requirements)

**Compliance Costs (Annual)**
- License renewal: $5K
- Audit + local compliance officer: $40K
- **Total**: ~$70K/year

---

**Regulatory Strategy Summary**

| Country | License Type | Timeline | Capital Req | Risk Level | Launch Priority |
|---------|--------------|----------|-------------|------------|----------------|
| **Singapore** | CMS License | 6-12 months | $250K | 🟡 Medium | 🔴 Q1 2026 |
| **Hong Kong** | Type 1 (SFO) | 6-9 months | $640K | 🟡 Medium | 🔴 Q2 2026 |
| **UAE (Dubai)** | VARA VASP | 3-6 months | $100K | 🟢 Low | 🔴 Q3 2026 |
| **Thailand** | DA Broker | 6-12 months | $140K | 🟡 Medium | 🟡 Q4 2026 |
| **Malaysia** | IEO Operator | 6-9 months | $640K | 🟡 Medium | 🟡 Q1 2027 |
| **Indonesia** | OJK ECF (+ Bappebti future) | 12-18 months | $160K ($6.4M crypto) | 🔴 High | 🟠 Q2 2027 |

**Total Regulatory Investment (Phase 1-2)**: ~$500K (licenses + legal) + $500K/year (compliance operations)

---

## 3. Product Vision & Strategy

### 3.1 Long-Term Vision (3-Year Outlook)

**2026: Foundation Year - "Prove the Model"**

**Theme**: Regulatory compliance, AI development, early adopter acquisition

**Key Milestones**:
- Secure MAS CMS license (Singapore) and VARA license (UAE)
- Launch with 10-20 pilot campaigns (handpicked, high-quality issuers)
- Build core AI recommendation engine (v1.0 → v2.0 → v3.0)
- Achieve $150M GMV with 100,000 registered users
- Establish proof-of-concept for tokenized equity in Asia

**Success Criteria**:
- 60%+ campaign success rate (funded vs. submitted)
- AI recommendation accuracy >70%
- <5% fraud/default rate
- Net Promoter Score (NPS) >50
- Break-even on operating expenses (not including AI R&D)

**Strategic Focus**:
- Quality over quantity (curated campaigns, not open marketplace)
- Regulatory relationships (become MAS's model citizen)
- AI data collection (every campaign = training data for AI)
- Thought leadership (position as "AI + blockchain experts" in Asia fintech)

---

**2027: Scaling Year - "Regional Dominance"**

**Theme**: Geographic expansion, product depth, institutional partnerships

**Key Milestones**:
- Expand to all 6 target markets (Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia)
- Launch secondary market (P2P trading post lock-up)
- Multi-chain expansion (Ethereum, Sui)
- Institutional investor tier with API access
- Achieve $750M GMV with 500,000 users

**Success Criteria**:
- 70%+ campaign success rate
- AI autonomy: 30% of deals auto-approved (up to $50K)
- Secondary market liquidity: $50M monthly trading volume
- 3+ institutional partnerships (family offices, VCs)
- Positive EBITDA (excluding growth marketing)

**Strategic Focus**:
- Horizontal scaling (more geographies, same product)
- Network effects (critical mass of investors → attracts better companies)
- AI enhancement (voice analysis, behavioral modeling, portfolio optimization)
- Ecosystem partnerships (accelerators, corporate VCs, tokenization providers)

---

**2028: Market Leadership Year - "Ecosystem Play"**

**Theme**: Platform economics, DAO governance, global expansion

**Key Milestones**:
- Launch Elevate Finance DAO (token holder governance)
- White-label platform for regional partners (SaaS revenue)
- Latin America + EU expansion (post-MiCA compliance)
- Elevate Finance token (utility: fee discounts, governance, staking rewards)
- Achieve $2.5B GMV with 2M users
- **Target: Profitability + Series B fundraising or strategic acquisition**

**Success Criteria**:
- 75%+ campaign success rate
- AI fully autonomous for <$100K deals
- Platform economics: 40% gross margin
- Top 3 market share in Asia tokenized securities
- Strategic acquisition offers from Coinbase, Binance, or traditional finance players

**Strategic Focus**:
- Vertical integration (custody, legal, tax services in-house)
- Platform monetization (API access, data licensing, white-label)
- Decentralization (transition from centralized platform → DAO)
- Exit strategy (IPO vs. strategic sale vs. remain independent)

---

### 3.2 Strategic Pillars

Elevate Finance's strategy rests on **four core pillars**, each reinforcing the others to create defensible competitive moats.

---

#### Pillar 1: AI as a Competitive Moat

**Thesis**: AI-powered investment analysis is our **only truly unique differentiator**. Competitors can copy our blockchain stack, regulatory playbook, or UX—but they cannot replicate our proprietary AI models trained on Asian startup data.

**AI Capabilities Roadmap**

| AI Feature | Phase 1 (2026) | Phase 2 (2027) | Phase 3 (2028) |
|------------|----------------|----------------|----------------|
| **Financial Analysis** | Rule-based + basic ML (revenue growth, burn rate, unit economics) | Deep learning models (predict 3-year revenue, bankruptcy risk) | Ensemble models (XGBoost + neural nets) calibrated to 95%+ accuracy |
| **Sentiment Analysis** | Web scraping (Twitter, LinkedIn, news) → sentiment score | Natural language processing (NLP) of founder communications, investor Q&A | Real-time sentiment tracking with causality analysis (what drives sentiment shifts) |
| **Founder Evaluation** | LinkedIn background check, education verification | Voice analysis from pitch videos (confidence, deception detection) | Psychometric profiling (Big Five personality traits, leadership potential) |
| **Market Analysis** | Industry benchmarking (vs. similar companies) | Competitive moat analysis (Porter's Five Forces automation) | Predictive market sizing (TAM/SAM/SOM for each campaign) |
| **Portfolio Optimization** | N/A (investors choose manually) | Diversification recommendations (sector, geography, stage) | Robo-advisor (auto-invest based on risk tolerance, rebalance quarterly) |
| **Fraud Detection** | KYC/AML checks, sanctions screening | Anomaly detection (unusual investment patterns, wash trading) | Graph neural networks (detect collusion, Sybil attacks) |

**Data Moat Strategy**

Our AI improves with every campaign, creating a **data flywheel**:

1. **More campaigns** → More training data (financials, outcomes, investor behavior)
2. **Better AI** → Higher recommendation accuracy
3. **Higher accuracy** → More investors trust the platform
4. **More investors** → Attracts better companies
5. **Better companies** → More campaigns (loop back to #1)

**Key Insight**: By Year 3, we'll have 1,750+ campaigns in our dataset—competitors starting from scratch cannot match this without years of operation.

**AI Ethics & Transparency**

- **Explainability**: Every AI recommendation includes:
  - Top 5 factors influencing the score (e.g., "Strong revenue growth: +15 points")
  - Comparison to similar campaigns ("This company is in the top 12% for its sector")
  - Confidence interval ("70-85% probability of funding success")

- **Human Oversight**:
  - Phase 1: 100% of AI recommendations reviewed by humans
  - Phase 2: 50% spot-check (all deals >$500K reviewed)
  - Phase 3: 10% random audit (AI fully autonomous for <$100K deals)

- **Bias Mitigation**:
  - Regular audits for demographic bias (founder gender, ethnicity, age)
  - Fairness constraints in model training (equal opportunity across protected classes)
  - Third-party audit annually (publish results publicly)

---

#### Pillar 2: Regulatory Leadership

**Thesis**: In securities markets, **regulatory compliance is the ultimate barrier to entry**. By being first-to-market with full licensing in 6 jurisdictions, we create a 12-18 month head start on competitors.

**Regulatory Moat Strategy**

**1. Regulatory Capture (Positive Connotation)**
- Become the "reference implementation" for regulators
- Participate in MAS Project Guardian, SFC innovation sandbox
- Co-author white papers with regulators on tokenized securities best practices
- **Goal**: When new regulations are drafted, they're designed around our existing model

**2. Compliance-as-a-Service (Future Revenue)**
- Our compliance infrastructure (KYC, AML, sanctions screening) is reusable
- Phase 3: License our compliance stack to other platforms (white-label SaaS)
- Potential revenue: $50K-$200K per client annually

**3. Multi-Jurisdictional Expertise**
- Most competitors focus on one country (e.g., Republic = US only)
- We'll have deep expertise in 6+ regulatory frameworks
- This expertise becomes consultative revenue (advise issuers on best jurisdiction for their raise)

**Regulatory Risk Mitigation**

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| MAS denies CMS license | 🟡 Medium (20%) | 🔴 Critical (delays launch 6-12 months) | **Mitigation**: Apply to MAS sandbox first (faster approval), hire ex-MAS compliance officer, engage external law firm with MAS relationship |
| Regulatory changes mid-operation | 🟡 Medium (30%) | 🟡 Medium (requires platform changes) | **Mitigation**: Modular compliance architecture (swap out KYC provider, adjust smart contract logic), maintain $500K regulatory reserve fund |
| Retroactive enforcement | 🟢 Low (10%) | 🔴 Critical (platform shutdown) | **Mitigation**: Over-comply from Day 1 (exceed minimum requirements), maintain audit trail, quarterly legal review |

---

#### Pillar 3: Blockchain Infrastructure (Multi-Chain Future)

**Thesis**: No single blockchain will dominate tokenized securities. We must be **chain-agnostic** to serve different user segments and regulatory environments.

**Multi-Chain Strategy**

| Blockchain | Launch Phase | Use Case | Target Users |
|------------|--------------|----------|--------------|
| **Solana** | Phase 1 (MVP) | Low-fee, fast finality for retail investors | Crypto-native users, small investments ($100-$5K) |
| **Ethereum** | Phase 2 (Month 19) | Institutional credibility, DeFi composability | Institutional investors, large deals (>$500K) |
| **Sui** | Phase 2 (Month 22) | Object-based ownership, programmable assets | RWA tokenization (real estate, IP, inventory) |
| **Polymesh** | Phase 3 (2028) | Purpose-built for securities, built-in compliance | Regulated markets (EU post-MiCA, US if SEC clarity) |

**Why Start with Solana?**

| Factor | Solana | Ethereum | Sui |
|--------|--------|----------|-----|
| **Transaction Cost** | $0.00025 | $2-$50 (depending on gas) | $0.001 |
| **Finality** | 400ms | 12-15 seconds | 500ms |
| **Throughput** | 65,000 TPS | 15-30 TPS (mainnet) | 120,000 TPS |
| **Developer Ecosystem** | Strong (Anchor framework) | Strongest (most tooling) | Growing (Move language) |
| **Retail Adoption (Asia)** | High (Phantom wallet popular) | Medium (MetaMask known) | Low (new chain) |
| **Institutional Perception** | Medium (improving post-FTX) | High (Ethereum = "safe choice") | Low (too new) |

**Decision**: Solana for MVP (retail focus, low fees), add Ethereum in Phase 2 (institutional credibility).

**Cross-Chain Architecture**

- **Unified Abstraction Layer**: Investors don't choose blockchain—system auto-selects based on:
  - Investment size (small = Solana, large = Ethereum)
  - User wallet (Phantom = Solana, MetaMask = Ethereum)
  - Gas price optimization (route to cheapest chain at transaction time)

- **Interoperability**: Use Wormhole or LayerZero for cross-chain messaging
  - Example: Investor on Ethereum can trade with investor on Solana (atomic swaps)

---

#### Pillar 4: Liquidity as a Service

**Thesis**: The #1 complaint about private equity is **illiquidity**. By solving liquidity through secondary markets, we attract both investors (who want exit options) and companies (who can offer "quasi-liquid equity" as a recruitment tool).

**Liquidity Strategy**

**Phase 1 (2026): No Secondary Market**
- 12-month hard lock-up enforced by smart contract
- Rationale: Focus on primary issuance, avoid regulatory complexity of exchange license

**Phase 2 (2027): P2P Secondary Market**
- After 12-month lock-up, investors can list tokens for sale
- Order book matching (limit orders, market orders)
- 0.5% transaction fee (split: 0.3% platform, 0.2% market maker incentive)
- **Target**: $50M monthly trading volume by end of 2027

**Phase 3 (2028): Automated Market Maker (AMM)**
- Liquidity pools for high-volume tokens
- Platform provides initial liquidity (use 10% of platform fees to seed pools)
- Yield for liquidity providers (earn fees + governance tokens)
- **Target**: $200M monthly trading volume, <2% price slippage

**Regulatory Considerations**

- Secondary trading may trigger "exchange" licensing requirements (e.g., SFC VATP, SEC ATS)
- **Mitigation**:
  - Phase 2: Launch in UAE first (VARA allows secondary trading under VASP license)
  - Phase 3: Apply for exchange licenses in Singapore, Hong Kong

**Market Making Incentives**

To solve the "cold start" problem (no liquidity → no traders → no liquidity):

1. **Platform-Backed Liquidity**: Platform commits to provide bid/ask quotes for top 20 tokens (0.5% spread)
2. **Market Maker Rebates**: External market makers earn 0.2% fee rebate + priority access to new listings
3. **Investor Incentives**: First 1,000 secondary market traders earn bonus governance tokens (airdrop)

---

### 3.3 Differentiation Strategy

**How We Win Against Competitors**

| Competitor Type | Their Advantage | Our Counter-Strategy |
|----------------|-----------------|---------------------|
| **Traditional Crowdfunding (Republic, StartEngine)** | Brand recognition, large user base | **Counter**: "AI-powered due diligence + blockchain liquidity" positioning—position as "next-generation" platform, not direct competitor. Target crypto-native users they can't serve. |
| **Blockchain Platforms (Securitize, Tokensoft)** | Multi-chain infrastructure, institutional relationships | **Counter**: "Retail-first, AI-assisted" positioning—they're B2B (serve issuers), we're B2C (serve investors). Partner with them for white-label tokenization, compete on investor acquisition. |
| **Crypto Launchpads (DAO Maker)** | Strong crypto community, high-volume trading | **Counter**: "Regulated, compliant, institutional-grade" positioning—we're for "serious investors," not speculators. Attract traditional finance users uncomfortable with DeFi's "Wild West" reputation. |
| **Regional Competitors (future)** | Local market knowledge, government connections | **Counter**: "First-mover advantage + multi-country scale"—by the time regional players emerge, we'll have network effects (investors and companies already on platform). Offer to acquire them or white-label our tech. |

**Unique Value Propositions (Ranked by Importance)**

1. **AI Investment Manager** (Unique, high differentiation)
   - **Claim**: "The only platform with institutional-grade AI that analyzes 50+ data points in seconds"
   - **Proof Points**: AI accuracy metrics, testimonials from investors who "made money following AI recommendations"

2. **Asia-First Regulatory Compliance** (High differentiation, medium uniqueness)
   - **Claim**: "Fully licensed in 6 Asian markets—only platform with MAS, SFC, and VARA approval"
   - **Proof Points**: Display license numbers, regulatory audit reports

3. **Built-in Liquidity** (Medium differentiation, medium uniqueness)
   - **Claim**: "Exit in 12 months, not 7 years—our secondary market ensures you're never locked in forever"
   - **Proof Points**: Secondary market trading volume, average time-to-exit stats

4. **Low Minimums** (Low differentiation, many competitors offer this)
   - **Claim**: "Start investing with just $100—no accreditation required"
   - **Proof Points**: Comparison table vs. competitors ($100 vs. $10,000+)

5. **Multi-Chain Flexibility** (Low differentiation, growing trend)
   - **Claim**: "Invest with Solana, Ethereum, or Sui—we support all major blockchains"
   - **Proof Points**: Chain logos, transaction cost comparison

---

### 3.4 Growth Strategy

**Three-Phase Growth Playbook**

---

#### Phase 1 (Months 1-6): Founder-Led Growth

**Strategy**: Handpick 10-20 exceptional companies, manually recruit investors from our networks.

**Tactics**:
1. **Company Sourcing**:
   - Partner with accelerators (Y Combinator, 500 Startups, Antler)
   - Attend demo days, pitch competitions
   - Outbound outreach to Crunchbase Top 100 Startups (Asia)

2. **Investor Acquisition**:
   - Founder's personal network (500+ LinkedIn connections)
   - Crypto Twitter influencers (paid partnerships: $5K-$20K per campaign)
   - Telegram/Discord communities (Web3 investor groups)

3. **Content Marketing**:
   - Thought leadership articles (Medium, LinkedIn): "The Future of Tokenized Equity in Asia"
   - Podcast appearances (crypto + startup podcasts)
   - Case studies (early successful campaigns)

**Target Metrics**:
- 10 campaigns live, 7 funded (70% success rate)
- 5,000 registered users (500 active investors)
- $20M GMV
- **CAC (Customer Acquisition Cost)**: $50/investor (mostly organic + influencer)

---

#### Phase 2 (Months 7-18): Scaled User Acquisition

**Strategy**: Paid marketing, partnerships, viral loops.

**Tactics**:
1. **Paid Advertising**:
   - Google Ads (search: "invest in startups," "equity crowdfunding Asia")
   - Facebook/Instagram (target: 25-45, $50K+ income, interests: crypto, investing, startups)
   - Twitter Ads (target: crypto influencers' followers)
   - TikTok (short-form content: "How I invested $100 and made $500")

2. **Referral Program**:
   - "Invite 3 friends, get $25 bonus credit"
   - Top referrers earn equity in platform (0.01% per 100 referrals)

3. **Strategic Partnerships**:
   - Phantom wallet integration (in-app investment flow)
   - CoinGecko/CoinMarketCap listings (for governance token)
   - Binance Labs partnership (co-marketing, shared deal flow)

4. **PR & Media**:
   - TechCrunch, Bloomberg, South China Morning Post coverage
   - Sponsorships (TOKEN2049, Consensus Asia)
   - Awards (Fintech Breakthrough Awards, The Asian Banker)

**Target Metrics**:
- 450 campaigns funded
- 150,000 active investors
- $750M GMV
- **CAC**: $30/investor (economies of scale, viral growth)

---

#### Phase 3 (Months 19-36): Product-Led Growth + Ecosystem

**Strategy**: Platform effects, API ecosystem, DAO governance.

**Tactics**:
1. **Developer Ecosystem**:
   - Public API (third-party apps can access campaign data)
   - Hackathons ($100K prize pool for best integrations)
   - Revenue share (developers earn 10% of fees from users they refer)

2. **B2B Expansion**:
   - White-label platform for regional partners (e.g., "Powered by Elevate Finance")
   - SaaS pricing: $10K/month + 0.5% of GMV

3. **DAO Governance**:
   - Issue governance tokens (ELEV token)
   - Token holders vote on: campaign approvals, fee changes, treasury allocation
   - Staking rewards (earn 5% APY + fee discounts)

4. **Geographic Expansion**:
   - Latin America (Brazil, Mexico): Partner with local VCs
   - EU (post-MiCA): Apply for EU-wide license
   - US (if regulatory clarity): Reg CF/Reg A+ compliance

**Target Metrics**:
- 1,750 campaigns funded
- 600,000 active investors
- $2.5B GMV
- **CAC**: $15/investor (organic + platform effects)

---

**Growth Metrics Dashboard (OKRs by Quarter)**

| Quarter | GMV Target | Active Investors | Campaigns Funded | CAC | Campaign Success Rate |
|---------|-----------|------------------|------------------|-----|----------------------|
| Q1 2026 | $10M | 2,000 | 5 | $60 | 60% |
| Q2 2026 | $30M | 8,000 | 15 | $55 | 65% |
| Q3 2026 | $60M | 20,000 | 30 | $50 | 70% |
| Q4 2026 | $100M | 40,000 | 50 | $45 | 70% |
| Q1 2027 | $180M | 80,000 | 100 | $40 | 72% |
| Q2 2027 | $320M | 150,000 | 180 | $35 | 73% |
| Q3 2027 | $550M | 280,000 | 320 | $32 | 74% |
| Q4 2027 | $900M | 500,000 | 550 | $30 | 75% |
| Q1 2028 | $1.3B | 750,000 | 800 | $25 | 75% |
| Q2 2028 | $1.8B | 1.1M | 1,100 | $22 | 76% |
| Q3 2028 | $2.2B | 1.5M | 1,400 | $20 | 76% |
| Q4 2028 | $2.6B | 2M | 1,750 | $18 | 77% |

---

### 3.5 Monetization Model

**Revenue Streams (Ranked by Contribution)**

---

#### 1. Platform Fees (60% of revenue)

**Structure**: 2% of total capital raised (paid by companies)

**Example**:
- Company raises $1M
- Platform fee: $20,000 (deducted from escrow at campaign close)

**Pricing Tiers** (Phase 2 - volume discounts):
- **Standard**: 2% (raises <$1M)
- **Growth**: 1.5% (raises $1M-$3M)
- **Enterprise**: 1% (raises >$3M, negotiable for marquee clients)

**Revenue Projection**:
- Year 1: $150M GMV × 2% = $3M
- Year 2: $750M GMV × 1.8% (avg due to discounts) = $13.5M
- Year 3: $2.5B GMV × 1.6% (avg) = $40M

---

#### 2. Performance Fees (30% of revenue)

**Structure**: 20% of profits above 8% hurdle rate (paid by pooled fund investors)

**Mechanics**:
1. Investor invests $10,000 in pooled fund
2. After 3 years, portfolio value = $15,000 (50% return)
3. Hurdle return (8% annually compounded) = $12,597
4. Excess profit = $15,000 - $12,597 = $2,403
5. Platform performance fee (20%) = $481
6. Investor net = $14,519 (45.2% return after fees)

**Revenue Projection** (assumes 15% average portfolio return):
- Year 1: $0 (no exits yet)
- Year 2: $50M AUM × 15% return × 20% carry = $1.5M
- Year 3: $300M AUM × 15% return × 20% carry = $9M

**Note**: This creates alignment—we only earn when investors make money above market rates.

---

#### 3. Transaction Fees (7% of revenue)

**Structure**: 0.5% on secondary market trades (paid by buyers and sellers, 0.25% each)

**Example**:
- Investor sells $10,000 worth of tokens
- Buyer pays 0.25% = $25
- Seller pays 0.25% = $25
- Total platform revenue = $50

**Revenue Projection** (assumes 30% of tokens trade annually):
- Year 1: $0 (no secondary market yet)
- Year 2: $750M GMV × 30% annual turnover × 0.5% = $1.125M
- Year 3: $2.5B GMV × 40% annual turnover × 0.5% = $5M

---

#### 4. Premium Features (2% of revenue)

**À la carte services**:
- **Enhanced Analytics** ($49/month): Advanced portfolio tracking, AI insights, custom alerts
- **Priority Support** ($99/month): Dedicated account manager, 24/7 support
- **API Access** ($499/month): Institutional investors get programmatic deal access
- **White-label Platform** ($10K/month + 0.5% GMV): Regional partners can rebrand our platform

**Revenue Projection**:
- Year 1: 500 premium subscribers × $49 × 12 = $294K
- Year 2: 5,000 premium subscribers × $60 (avg) × 12 = $3.6M
- Year 3: 20,000 premium subscribers × $70 (avg) × 12 = $16.8M

---

#### 5. Data Licensing (1% of revenue - Future)

**Product**: Anonymized investment data sold to VCs, researchers, market intelligence firms

**Use Cases**:
- "Which sectors are getting most retail investor interest in Southeast Asia?"
- "What's the average valuation multiple for B2B SaaS in Singapore?"
- "Founder demographic trends in funded vs. unfunded campaigns"

**Pricing**: $25K-$100K per dataset (annual subscription)

**Revenue Projection**:
- Year 1: $0 (too early, insufficient data)
- Year 2: 10 clients × $50K = $500K
- Year 3: 40 clients × $75K = $3M

---

**Total Revenue Projection Summary**

| Revenue Stream | Year 1 | Year 2 | Year 3 |
|----------------|--------|--------|--------|
| Platform Fees | $3M | $13.5M | $40M |
| Performance Fees | $0 | $1.5M | $9M |
| Transaction Fees | $0 | $1.125M | $5M |
| Premium Features | $0.294M | $3.6M | $16.8M |
| Data Licensing | $0 | $0.5M | $3M |
| **Total Revenue** | **$3.294M** | **$20.225M** | **$73.8M** |

**Unit Economics** (Year 3):
- Revenue per active investor: $73.8M / 600,000 = $123/year
- CAC (Year 3): $18
- Payback period: 1.8 months
- LTV (3-year): $370 (assumes 50% retention, average 5 investments/year)
- **LTV:CAC ratio**: 20.5x (excellent, target >3x)

---

## 4. Functional Requirements

This section provides detailed specifications for all user-facing features and system capabilities. Requirements are organized by user role and functional area.

---

### 4.1 User Authentication & Onboarding

**Overview**

The authentication system must support multiple registration methods while maintaining security, regulatory compliance, and a smooth user experience. All authentication flows must integrate with KYC/AML verification before users can invest or create campaigns.

---

#### 4.1.1 Registration Flows

**FR-AUTH-001: Email Registration**

**Description**: Users can register using email address and password

**Requirements**:
- Email validation must check format (RFC 5322 compliant)
- Password requirements:
  - Minimum 12 characters
  - At least 1 uppercase letter
  - At least 1 lowercase letter
  - At least 1 number
  - At least 1 special character (!@#$%^&*)
  - Must not be in common password breach databases (check against Have I Been Pwned API)
- Password strength indicator (weak/medium/strong) displayed in real-time
- Email confirmation link sent within 60 seconds
- Confirmation link expires after 24 hours
- User account marked as "unverified" until email confirmed
- Unverified users can browse campaigns but cannot invest or create campaigns

**UI Components**:
- Registration form (email, password, confirm password, terms checkbox)
- Password strength meter (visual indicator)
- Email sent confirmation page
- Email verification success/error pages

**Error Handling**:
- Email already registered: "This email is already associated with an account. Please sign in or use password recovery."
- Invalid email format: "Please enter a valid email address"
- Weak password: Display specific requirements not met
- Email delivery failure: "We couldn't send the confirmation email. Please check your email address and try again."

**Acceptance Criteria**:
- User can complete registration in <90 seconds (average)
- Email delivery rate >99.5%
- Confirmation link click-through rate >80%

---

**FR-AUTH-002: Social Login (OAuth 2.0)**

**Description**: Users can register/sign in using social accounts

**Supported Providers**:
1. Google (primary - highest adoption in Asia)
2. LinkedIn (professional verification for founders)
3. Apple (iOS users, privacy-focused)
4. Facebook (Phase 2 - optional)

**Requirements**:
- OAuth 2.0 authorization code flow (not implicit flow for security)
- Request minimal scopes:
  - Google: email, profile (name, photo)
  - LinkedIn: r_liteprofile, r_emailaddress
  - Apple: email, name
- Account linking: Users can connect multiple social accounts to same profile
- Deduplication: Check email address to prevent duplicate accounts
- Social profile data (name, photo) auto-populated but user can edit
- Social accounts marked as "verified email" immediately (no email confirmation needed)

**Security**:
- PKCE (Proof Key for Code Exchange) for mobile apps
- State parameter validation to prevent CSRF attacks
- Token storage in secure HTTP-only cookies (not localStorage)
- Automatic token refresh before expiration

**UI Components**:
- Social login buttons (branded according to provider guidelines)
- Account linking page (in user settings)
- Permission consent screen (show what data we access)

**Error Handling**:
- OAuth flow cancelled: Return to login page with message "Sign-in cancelled"
- Provider error: "We couldn't connect to [Provider]. Please try again or use another method."
- Email mismatch (if user tries to link account with different email): "This social account uses a different email. Please use [email] or contact support."

**Acceptance Criteria**:
- Social login success rate >95%
- Average login time <10 seconds
- Support for account linking without creating duplicates

---

**FR-AUTH-003: Wallet Connect (Web3 Authentication)**

**Description**: Users can register/sign in using blockchain wallets

**Supported Wallets**:
- Phase 1:
  - Phantom (Solana - primary)
  - Solflare (Solana - secondary)
- Phase 2:
  - MetaMask (Ethereum)
  - Coinbase Wallet (multi-chain)
  - Ledger (hardware wallet)
  - Trezor (hardware wallet)

**Authentication Flow**:
1. User clicks "Connect Wallet"
2. System detects installed wallets or shows QR code for mobile wallets
3. User selects wallet and approves connection
4. System generates challenge message: "Sign this message to verify you own this wallet: [nonce]"
5. User signs message with private key (no gas fees)
6. System verifies signature matches wallet address
7. If wallet address not in database: Create new account
8. If wallet address exists: Sign user in

**Requirements**:
- Challenge nonce must be:
  - Unique (UUID v4)
  - Single-use (invalidated after signature verification)
  - Time-limited (expires after 5 minutes)
- Support for multiple wallets per user account
- Primary wallet designated for receiving distributions
- Wallet address whitelisting for KYC compliance (only verified wallets can receive tokens)
- Wallet connection status displayed in header
- Auto-disconnect after 24 hours of inactivity

**Security**:
- Never request seed phrases or private keys
- Sign-in message must include:
  - Platform domain (prevent phishing)
  - Timestamp
  - Nonce
  - Purpose statement: "Sign this message to prove you own this wallet address. This will not trigger a transaction or cost any gas fees."
- Rate limiting: Max 5 signature requests per wallet per hour

**UI Components**:
- Wallet connection modal (list of supported wallets)
- QR code for mobile wallet apps
- Connected wallet indicator (truncated address: 0x1234...5678)
- Wallet management page (add/remove wallets, set primary)

**Error Handling**:
- Wallet not installed: Show installation instructions with link to wallet website
- Signature rejected: "Signature request was cancelled. Please try again to sign in."
- Wrong network: "Please switch your wallet to [Solana Mainnet/Devnet/Testnet]"
- Wallet connection timeout: "Connection timed out. Please ensure your wallet is unlocked and try again."

**Acceptance Criteria**:
- Wallet connection success rate >90%
- Average connection time <15 seconds
- Support for both browser extensions and mobile wallet apps
- Zero private key exposure or storage

---

#### 4.1.2 Multi-Factor Authentication (2FA)

**FR-AUTH-004: TOTP-Based 2FA**

**Description**: Time-based one-time password (TOTP) authentication for enhanced security

**Requirements**:
- Support standard TOTP apps:
  - Google Authenticator
  - Authy
  - Microsoft Authenticator
  - 1Password
- TOTP configuration:
  - Secret key length: 160 bits (32 characters, Base32 encoded)
  - Time step: 30 seconds
  - Code length: 6 digits
  - Hash algorithm: SHA-1 (for compatibility with all authenticator apps)
- 2FA enrollment flow:
  1. User navigates to Security Settings
  2. System generates secret key and QR code
  3. User scans QR code with authenticator app
  4. User enters current code to verify setup
  5. System displays backup codes (10 codes, single-use)
  6. 2FA marked as enabled
- 2FA enforcement:
  - Optional for all users initially
  - Mandatory for users investing >$10,000 cumulative
  - Mandatory for company accounts creating campaigns
  - Mandatory for admin accounts
- 2FA challenges triggered at:
  - Sign-in (every time)
  - Password change
  - Email address change
  - Wallet address change (adding new wallet)
  - Large withdrawals (>$5,000 USDC equivalent)
  - Admin actions (campaign approval, user suspension)

**Backup Codes**:
- 10 codes generated at 2FA enrollment
- Each code is 10 characters (alphanumeric, mixed case)
- Single-use (invalidated after one use)
- Regeneration: User can regenerate all codes (invalidates old ones)
- Download as text file or print option

**Recovery Process**:
- If user loses access to 2FA device:
  1. Enter backup code (if available)
  2. OR contact support with identity verification:
     - Government ID photo
     - Selfie with ID
     - Recent transaction details
     - Registered email and phone number verification
  3. Support disables 2FA after verification (48-72 hour process)
  4. User required to re-enable 2FA within 7 days

**UI Components**:
- 2FA setup wizard (QR code, manual entry option, backup codes)
- 2FA challenge screen (6-digit code input)
- Backup codes display and download
- 2FA management page (disable, regenerate backup codes)

**Error Handling**:
- Invalid code: "The code you entered is incorrect. Please try again." (max 5 attempts before temporary lock)
- Expired code: "This code has expired. Please enter the current code from your authenticator app."
- Too many failed attempts: "Too many failed attempts. Your account has been temporarily locked for 15 minutes. Please try again later or use a backup code."
- Lost device: Clear instructions to contact support with required verification documents

**Acceptance Criteria**:
- 2FA setup completion rate >85% (for mandatory users)
- Average setup time <3 minutes
- Code validation success rate >95%
- Backup code usage <2% (indicates good UX)

---

**FR-AUTH-005: SMS-Based 2FA (Phase 2)**

**Description**: SMS one-time password as alternative 2FA method

**Requirements**:
- Supported countries (SMS delivery reliability >98%):
  - Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia
- SMS OTP configuration:
  - Code length: 6 digits
  - Validity: 5 minutes
  - Rate limiting: Max 3 SMS per phone number per hour
- Phone number verification:
  - Must verify phone number before enabling SMS 2FA
  - Send test code during setup
  - Phone number stored in E.164 format (+[country code][number])
- SMS templates:
  - "Your Elevate Finance verification code is: [123456]. Valid for 5 minutes. Do not share this code."
  - Sender ID: "ElevateFi" (registered with SMS providers)
- SMS provider: Twilio (primary), AWS SNS (backup)
- Cost management: SMS 2FA considered less secure than TOTP, encouraged for TOTP adoption

**Security Considerations**:
- SIM swap attacks: Monitor for multiple failed SMS deliveries
- SMS interception: Display warning in settings: "SMS is less secure than authenticator apps. We recommend TOTP for better security."
- Fallback: Allow both TOTP and SMS simultaneously (user can choose which to use at sign-in)

**UI Components**:
- Phone number input with country code selector
- SMS verification code input
- Resend code button (disabled for 60 seconds after send)

**Error Handling**:
- SMS delivery failure: "We couldn't send the code. Please check your phone number and try again."
- Invalid phone number: "Please enter a valid phone number for [Country]"
- Too many requests: "You've requested too many codes. Please wait 1 hour before trying again."

**Acceptance Criteria**:
- SMS delivery rate >98% in supported countries
- Average delivery time <30 seconds
- User preference: 70% TOTP, 30% SMS (indicates good security awareness)

---

**FR-AUTH-006: Biometric Authentication (Mobile Apps - Phase 2)**

**Description**: Fingerprint and Face ID for mobile app authentication

**Requirements**:
- iOS: Face ID, Touch ID (using LocalAuthentication framework)
- Android: Fingerprint, Face Unlock (using BiometricPrompt API)
- Biometric authentication:
  - Only for unlocking app (initial sign-in still requires password/social/wallet)
  - Enabled by default if device supports it
  - User can disable in settings
  - Fallback to password if biometric fails 3 times
- Session management:
  - Biometric unlock valid for 24 hours
  - After 24 hours, require full re-authentication
  - Biometric data never leaves device (stored in secure enclave/keystore)

**Security**:
- Local biometric verification only (no server-side storage)
- Session token stored in secure storage (iOS Keychain, Android Keystore)
- Token encrypted with biometric-protected key
- Device registration: Max 3 devices per account

**UI Components**:
- Biometric prompt (native OS dialogs)
- Fallback to PIN/password option
- Device management page (list of registered devices, remove device option)

**Error Handling**:
- Biometric not enrolled: "Biometric authentication is not set up on this device. Please set up fingerprint/face unlock in your device settings."
- Hardware not available: Fall back to password automatically
- Biometric changed: If device biometric data changes, require full re-authentication

**Acceptance Criteria**:
- Biometric unlock success rate >95%
- Average unlock time <2 seconds
- User adoption rate >80% (on supported devices)

---

#### 4.1.3 Password Management

**FR-AUTH-007: Password Recovery**

**Description**: Self-service password reset for users who forget their password

**Recovery Flow**:
1. User clicks "Forgot Password?" on sign-in page
2. User enters email address
3. System sends password reset link to email (if account exists)
4. User clicks link in email (link expires after 1 hour)
5. User enters new password (same strength requirements as registration)
6. Password updated, user automatically signed in
7. Security notification email sent to user

**Security**:
- Rate limiting:
  - Max 3 password reset requests per email per hour
  - Max 10 password reset requests per IP per hour
- Reset tokens:
  - Single-use (invalidated after password change)
  - Expires after 1 hour
  - Cryptographically secure (256-bit random)
- Email privacy:
  - Always return "If an account exists with this email, you will receive a reset link" (prevents email enumeration)
  - Never reveal if email is registered or not
- Session invalidation:
  - All existing sessions terminated after password change
  - User must sign in again on all devices
- 2FA bypass prevention:
  - If 2FA is enabled, password reset DOES NOT disable 2FA
  - User must still enter 2FA code after password reset

**Notification Email**:
- Subject: "Your Elevate Finance password has been changed"
- Body: "Your password was recently changed. If you did not make this change, please contact support immediately at security@elevatefi.com"
- Include: Timestamp, IP address, browser/device info
- CTA: "Report unauthorized access" button

**UI Components**:
- Password recovery request form (email input)
- Check your email confirmation page
- Set new password form
- Success confirmation page

**Error Handling**:
- Expired link: "This password reset link has expired. Please request a new one."
- Invalid link: "This password reset link is invalid. Please request a new one."
- Used link: "This link has already been used. If you need to reset your password again, please request a new link."
- Network error: "We couldn't process your request. Please check your connection and try again."

**Acceptance Criteria**:
- Email delivery time <60 seconds (95th percentile)
- Reset completion rate >70% (users who click link and set new password)
- Zero successful account takeovers via password reset vulnerability
- Support response time <1 hour for "unauthorized password change" reports

---

**FR-AUTH-008: Password Change (Authenticated Users)**

**Description**: Allow signed-in users to change their password

**Requirements**:
- Accessible from Account Settings > Security
- User must enter:
  - Current password (verification)
  - New password (same strength requirements)
  - Confirm new password
- Current password verification:
  - Must match exactly
  - Max 5 failed attempts before temporary lock (15 minutes)
- Password change triggers:
  - All sessions invalidated (except current session - user stays signed in)
  - Security notification email sent
  - 2FA challenge (if enabled)
  - Audit log entry created
- Password history:
  - Cannot reuse last 5 passwords
  - Password age displayed (e.g., "Last changed 45 days ago")
- Forced password change:
  - Admins can flag accounts for mandatory password change at next sign-in
  - User cannot access platform until password changed
  - Use case: Security breach, suspicious activity detected

**UI Components**:
- Password change form (current, new, confirm)
- Password strength meter
- Success confirmation message
- Password history info (last changed date)

**Error Handling**:
- Wrong current password: "Current password is incorrect"
- Password reuse: "You cannot use one of your last 5 passwords"
- Passwords don't match: "New passwords do not match"
- 2FA failure: "Invalid verification code. Please try again."

**Acceptance Criteria**:
- Password change success rate >98%
- Zero sessions remain active after password change (security requirement)
- Email notification delivery rate >99.5%

---

#### 4.1.4 Account Settings

**FR-AUTH-009: User Profile Management**

**Description**: Users can view and edit their profile information

**Profile Fields**:

**Personal Information** (editable):
- Full name (required)
- Display name (optional, shown on platform, defaults to first name)
- Profile photo (optional, max 5MB, formats: JPG, PNG, WebP)
- Country of residence (required, dropdown)
- Phone number (optional, verified via SMS if provided)
- Date of birth (required for investors, 18+ validation)
- Language preference (English default, more languages in Phase 2)
- Timezone (auto-detected, editable)

**Account Information** (read-only or special handling):
- Email address (changeable with verification)
- Account created date
- User ID (UUID, displayed for support purposes)
- Account type (Investor, Company, Admin)
- Verification status (Unverified, Email Verified, KYC Verified)

**Privacy Settings**:
- Profile visibility (Public, Investors Only, Private)
- Show investment activity on profile (Yes/No)
- Allow other users to message me (Yes/No)
- Newsletter subscription (Yes/No)

**Investment Preferences** (Investor-specific):
- Preferred investment regions (multi-select: Singapore, Hong Kong, UAE, etc.)
- Preferred industries (multi-select: Fintech, Healthcare, E-commerce, etc.)
- Risk tolerance (Conservative, Moderate, Aggressive)
- Investment goals (Capital appreciation, Regular income, Both)
- Minimum AI score threshold for recommendations (1-10 scale)

**Notification Preferences**:
- Email notifications:
  - Campaign updates (new milestones, announcements)
  - Investment confirmations
  - Distribution received
  - New AI recommendations
  - Platform announcements
  - Marketing emails
- Push notifications (mobile app, Phase 2):
  - Campaign ending soon
  - Investment goal reached
  - New message from company
  - Portfolio alerts (significant gains/losses)

**Change Email Flow**:
1. User enters new email address
2. System sends verification link to NEW email
3. User clicks link to verify new email
4. System sends confirmation to OLD email (security notification)
5. Email updated after new email verified
6. Session NOT terminated (unlike password change)

**UI Components**:
- Profile edit form (tabbed: Personal, Privacy, Preferences, Notifications)
- Photo upload (drag & drop or click to browse)
- Country selector with flags
- Multi-select dropdowns for preferences
- Toggle switches for notifications
- Save/Cancel buttons
- Auto-save indicator for smoother UX

**Error Handling**:
- Invalid email format: "Please enter a valid email address"
- Email already in use: "This email is already associated with another account"
- Image too large: "Image must be under 5MB. Please choose a smaller file."
- Unsupported format: "Please upload a JPG, PNG, or WebP image"
- Under 18: "You must be 18 or older to invest on Elevate Finance"

**Acceptance Criteria**:
- Profile update success rate >99%
- Image upload success rate >95%
- Average time to update profile <2 minutes
- Email change completion rate >85%

---

**FR-AUTH-010: Session Management**

**Description**: Manage user sessions across devices and browsers

**Session Behavior**:
- Session duration:
  - Default: 7 days (remember me unchecked)
  - Extended: 30 days (remember me checked)
  - Mobile app: Indefinite (until manual sign-out or token revoked)
- Concurrent sessions: Unlimited (user can be signed in on multiple devices)
- Session storage: JWT (JSON Web Token)
  - Access token: Short-lived (15 minutes)
  - Refresh token: Long-lived (7 or 30 days)
  - Refresh token rotation: New refresh token issued on each refresh
- Secure cookie flags:
  - HttpOnly (prevent XSS attacks)
  - Secure (HTTPS only)
  - SameSite=Strict (prevent CSRF attacks)

**Session Invalidation** (automatic):
- Password change: All sessions except current
- 2FA disable: All sessions (force re-authentication)
- Email change: No invalidation
- Account suspension: All sessions immediately
- Security breach detected: All sessions immediately

**Active Sessions Page**:
- Display:
  - Device type (Desktop, Mobile, Tablet)
  - Browser (Chrome, Safari, Firefox, etc.)
  - Operating system (Windows, macOS, iOS, Android)
  - Location (City, Country) - based on IP geolocation
  - Last active timestamp
  - Current session indicator ("This device")
- Actions:
  - Sign out (individual session)
  - Sign out all other sessions (except current)
  - Sign out all sessions (including current)

**Security Monitoring**:
- Anomaly detection:
  - Sign-in from new country: Send email notification "Was this you?"
  - Sign-in from new device: Send email notification
  - Concurrent sessions from distant locations: Flag for review
- User actions:
  - "Yes, this was me" button (whitelist location/device)
  - "No, this wasn't me" button (invalidate session, force password change)

**UI Components**:
- Active sessions list (table with device info)
- Sign out buttons (per session and bulk)
- Location map (optional, visual representation of active sessions)
- Security alerts (new device, new location notifications)

**Error Handling**:
- Session expired: "Your session has expired. Please sign in again."
- Invalid token: "Invalid session. Please sign in again."
- Token refresh failure: "We couldn't refresh your session. Please sign in again."

**Acceptance Criteria**:
- Session management page load time <1 second
- Session invalidation effective within 5 seconds globally
- Zero unauthorized session access after password change
- 95% of users understand active sessions page without help docs

---

#### 4.1.5 Account Deletion & Data Export

**FR-AUTH-011: Account Deletion (PDPA/GDPR Compliance)**

**Description**: Users can request account deletion (right to be forgotten)

**Deletion Requirements**:
- Eligibility:
  - No active investments (all campaigns must be closed or exited)
  - No pending transactions
  - No outstanding distributions
  - Account age >30 days (prevents abuse)
- Deletion process:
  1. User requests deletion in Account Settings
  2. System checks eligibility (blocks if active investments)
  3. Warning modal: "This action is permanent and cannot be undone. All data will be deleted within 30 days."
  4. User enters password to confirm
  5. 2FA challenge (if enabled)
  6. Grace period: 30 days to cancel deletion
  7. Deletion email sent: "Your account will be deleted on [Date]. Click here to cancel."
  8. After 30 days: Account and associated data permanently deleted

**Data Retained** (legal/regulatory requirements):
- Transaction records: 7 years (MAS requirement)
- KYC documents: 7 years (AML requirement)
- Audit logs: 7 years (compliance requirement)
- Data anonymized: Personal identifiers removed, only transaction metadata kept

**Data Deleted** (within 30 days):
- Profile information (name, email, phone, photo)
- Login credentials (password hash, 2FA secrets)
- Session tokens (all sessions invalidated immediately)
- Preferences and settings
- Watchlist, favorites, messages
- AI recommendations history (not used for model training after deletion)

**Cancellation Flow**:
- User clicks "Cancel Deletion" in email or on website
- Deletion request cancelled
- Account restored to full functionality
- Confirmation email sent

**Blocked Deletion Scenarios**:
- Active investments: "You have active investments. Please wait until all campaigns are closed or exit your positions before deleting your account."
- Pending distributions: "You have pending distributions. Please wait to receive all payouts before deleting your account."
- Company with active campaign: "You have an active campaign. Please close or complete your campaign before deleting your account."

**UI Components**:
- Account deletion request page (warnings, eligibility check)
- Password confirmation modal
- Grace period countdown (in settings)
- Cancel deletion button (if within grace period)

**Error Handling**:
- Ineligible: Display specific reason (active investments, pending transactions, etc.)
- Wrong password: "Incorrect password. Please try again."
- Already deleted: "This account has already been deleted."

**Acceptance Criteria**:
- Deletion request completion rate >90% (users who start process)
- Cancellation rate <10% (indicates clear warnings)
- Zero data breaches of "deleted" accounts
- Compliance with PDPA/GDPR data deletion timelines (30 days)

---

**FR-AUTH-012: Data Export (PDPA/GDPR Compliance)**

**Description**: Users can request export of all personal data (right to data portability)

**Export Contents**:
- Account data (JSON):
  - Profile information
  - Email, phone, preferences
  - Account creation date, last sign-in
- Investment history (CSV):
  - All investments (campaign name, amount, date, tokens received)
  - Returns and distributions
  - Transaction IDs
- Documents (ZIP):
  - Uploaded KYC documents
  - Investment confirmations
  - Tax documents
- Messages (JSON):
  - All messages sent/received from companies
  - Timestamps, sender/recipient
- AI recommendations (JSON):
  - All recommendations received
  - Campaign details, AI scores, reasoning

**Export Process**:
1. User requests export in Account Settings > Privacy
2. System generates export file (async, can take 5-30 minutes)
3. Email sent with download link when ready
4. Download link valid for 7 days
5. File encrypted (password-protected ZIP)
6. Password sent in separate email (security)

**Security**:
- 2FA challenge before export request
- Rate limiting: Max 1 export per user per 24 hours
- Audit log entry created
- IP address logged
- Email notification sent after download

**File Formats**:
- Machine-readable: JSON (primary)
- Human-readable: CSV for financial data
- Documents: Original formats (PDF, JPG, PNG)
- Archive: ZIP with password protection

**UI Components**:
- Data export request button
- Export status page (processing, ready for download)
- Download button (with expiration countdown)
- Export history (past exports with dates)

**Error Handling**:
- Export in progress: "An export is already being generated. Please wait until it's ready."
- Export failed: "We couldn't generate your export. Please try again or contact support."
- Link expired: "This download link has expired. Please request a new export."

**Acceptance Criteria**:
- Export generation time <30 minutes (95th percentile)
- Export completeness: 100% of user data included
- Email delivery time <5 minutes after export ready
- Download success rate >98%

---

### 4.1.6 KYC/AML Integration (Onboarding Completion)

**FR-AUTH-013: KYC Verification Process**

**Description**: Know Your Customer verification for regulatory compliance

**Verification Levels**:

**Level 0: Unverified** (default)
- Can browse campaigns
- Can view AI recommendations
- Cannot invest
- Cannot create campaigns

**Level 1: Email Verified**
- Email confirmed
- Can add campaigns to watchlist
- Can message companies (rate limited)
- Cannot invest
- Cannot create campaigns

**Level 2: Basic KYC** (required for retail investors)
- Government ID uploaded and verified
- Selfie (liveness check) completed
- Personal details confirmed (name, DOB, address)
- Can invest up to $10,000 per campaign
- Can invest up to $50,000 per year (cumulative)
- Cannot create campaigns

**Level 3: Enhanced KYC** (required for high-value investors and companies)
- All Level 2 requirements
- Proof of address (utility bill, bank statement)
- Source of funds declaration
- Enhanced due diligence questionnaire
- Can invest unlimited amounts
- Can create campaigns (if company account)
- Required for investments >$10,000 per campaign

**KYC Provider Integration**:
- Primary: Sumsub (https://sumsub.com)
- Alternative: Onfido (backup)
- Features required:
  - ID document verification (passport, national ID, driver's license)
  - Liveness detection (selfie with blink, turn head)
  - Address verification (OCR on utility bills)
  - Sanctions screening (OFAC, UN, EU, local lists)
  - PEP (Politically Exposed Person) screening
  - Adverse media screening

**Supported Documents by Country**:

**Singapore**:
- NRIC (National Registration Identity Card)
- Passport
- Driver's License

**Hong Kong**:
- HKID (Hong Kong Identity Card)
- Passport

**UAE**:
- Emirates ID
- Passport
- Resident Visa

**Thailand**:
- National ID Card
- Passport
- Driver's License

**Malaysia**:
- MyKad (Malaysian Identity Card)
- Passport

**Indonesia**:
- KTP (Kartu Tanda Penduduk)
- Passport

**KYC Flow** (User Experience):
1. User signs up, creates account (Level 0)
2. User verifies email (Level 1)
3. User clicks "Verify Identity" (to invest)
4. User redirected to Sumsub embedded iframe
5. User selects country and document type
6. User uploads front and back of ID (or just front for passport)
7. User takes selfie (follow on-screen instructions: blink, turn head)
8. User uploads proof of address (if Enhanced KYC)
9. User submits for review
10. Sumsub performs automated checks (30 seconds - 5 minutes)
11. If passed: User promoted to Level 2 (or 3)
12. If failed: User receives email with reason and instructions to retry
13. If manual review needed: User notified (24-48 hour review time)

**Automated Checks** (Sumsub):
- Document authenticity (holograms, fonts, microprinting)
- Face match (selfie vs. ID photo, 95%+ similarity required)
- Liveness detection (not a photo of a photo)
- Data extraction (name, DOB, document number via OCR)
- Expiry date validation (documents must be valid for >90 days)
- Sanctions screening (real-time API checks)

**Manual Review Triggers**:
- Low quality images (blurry, dark, glare)
- Face match <95% confidence
- Document expiring soon (<90 days)
- Suspected tampering
- PEP or sanctions hit (requires compliance officer review)
- Address verification failure

**Admin Review Queue**:
- Dashboard showing pending KYC reviews
- Filters: Country, risk level, time waiting
- Each review shows:
  - User ID, name, email
  - Submitted documents (viewable in modal)
  - Sumsub AI scores and flags
  - Sanctions/PEP results
- Actions:
  - Approve (promote to Level 2 or 3)
  - Reject (with reason: "Blurry document", "Face mismatch", "Expired ID", etc.)
  - Request more information (send email to user with instructions)

**Data Privacy**:
- KYC documents stored in Sumsub's encrypted servers (not on Elevate Finance servers)
- Only metadata stored locally (verification status, document type, expiry date)
- Access to documents requires admin authentication + 2FA
- Document access logged in audit trail
- PDPA/GDPR compliant (data residency in Singapore/EU)

**Re-verification Requirements**:
- ID document expires: User must re-verify within 30 days or account downgraded
- Change of country: Requires new KYC (different regulatory requirements)
- Suspicious activity: Compliance officer can flag for re-verification
- Regulatory requirement: Periodic re-verification every 2 years (MAS guidance)

**UI Components**:
- KYC verification status badge (Unverified, Pending, Verified)
- Embedded Sumsub iframe (seamless UX)
- Progress indicator (steps: Document, Selfie, Address, Review)
- Rejection reasons and retry instructions
- Re-verification reminder (when ID expiring soon)

**Error Handling**:
- Camera access denied: "Please enable camera access to take a selfie. This is required for identity verification."
- Upload failed: "We couldn't upload your document. Please check your connection and try again."
- Document rejected: "Your [document type] was rejected: [reason]. Please upload a new document. Tips: [helpful tips based on rejection reason]"
- Sanctions hit: "We cannot verify your account at this time. Please contact support@elevatefi.com for assistance." (do not reveal sanctions reason to user)

**Acceptance Criteria**:
- KYC completion rate >80% (users who start process)
- Average verification time <5 minutes for auto-approved
- Manual review time <24 hours (business days)
- False positive rate <1% (legitimate users incorrectly rejected)
- False negative rate <0.1% (fraudulent users incorrectly approved)
- Sanctions screening accuracy 100% (zero false negatives tolerated)

---

**FR-AUTH-014: AML Transaction Monitoring**

**Description**: Anti-Money Laundering monitoring of all financial transactions

**Monitored Activities**:
- Deposits (fiat and stablecoin)
- Investments
- Withdrawals
- Secondary market trades (Phase 2)
- Distribution payouts

**AML Rules Engine**:

**Rule 1: Large Transactions**
- Trigger: Single transaction >$10,000 USD equivalent
- Action: Require Enhanced KYC (if not already completed)
- Additional: Request source of funds declaration

**Rule 2: Rapid Deposits/Withdrawals**
- Trigger: Deposit followed by withdrawal within 24 hours (>$5,000)
- Suspicion: Layering (money laundering technique)
- Action: Flag for manual review, delay withdrawal for 48 hours

**Rule 3: Smurfing (Structuring)**
- Trigger: Multiple deposits just below $10,000 threshold within 7 days
- Example: $9,500, $9,800, $9,900 over 3 days
- Action: Flag for manual review, aggregate to see if >$10,000 cumulative

**Rule 4: Geographic Risk**
- Trigger: Transaction from/to high-risk jurisdiction (FATF blacklist)
- Countries: Iran, North Korea, Myanmar, others per FATF updates
- Action: Block transaction, require Enhanced Due Diligence

**Rule 5: Unusual Pattern**
- Trigger: Significant deviation from user's historical behavior
- Example: User typically invests $500-$1,000, suddenly invests $50,000
- Action: Flag for manual review, verify source of funds

**Rule 6: Third-Party Payments**
- Trigger: Deposit from wallet/account not registered to user's name
- Action: Block transaction (prevent money laundering via third-party)
- Exception: User can register additional payment sources after verification

**Rule 7: Politically Exposed Persons (PEP)**
- Trigger: User flagged as PEP during KYC
- Action: Require Enhanced Due Diligence, manual approval for all transactions >$5,000
- Ongoing monitoring: Quarterly review of PEP accounts

**Transaction Screening**:
- Real-time screening against:
  - OFAC (US Office of Foreign Assets Control)
  - UN Consolidated List
  - EU Sanctions List
  - Local sanctions lists (MAS, HKMA, etc.)
- Fuzzy matching (to catch variations in names)
- 99.99% uptime requirement for screening API

**Suspicious Activity Reporting (SAR)**:
- Compliance officer dashboard shows flagged transactions
- Each flag includes:
  - User details
  - Transaction details (amount, timestamp, source, destination)
  - Rule(s) triggered
  - Risk score (1-10)
- Compliance officer actions:
  - Approve (whitelist for future)
  - Reject (block transaction, notify user)
  - Escalate (file SAR with MAS or local regulator)
- SAR filing:
  - Completed within 15 days of detection (MAS requirement)
  - Submitted via regulator's portal
  - User NOT notified (legal requirement: tipping off is prohibited)
  - Account may be frozen pending investigation

**Data Retention**:
- All transaction records: 7 years (regulatory requirement)
- AML flags and review notes: 7 years
- SARs filed: Permanent retention
- Stored in immutable audit log (blockchain-backed for tamper-evidence)

**UI Components** (Admin):
- AML dashboard (flagged transactions, pending reviews)
- Transaction detail modal (full context, user history, risk indicators)
- Approve/Reject/Escalate buttons
- SAR filing form (pre-populated with transaction details)
- Risk scoring visualizations (charts showing user's transaction patterns)

**Error Handling** (User-facing):
- Transaction blocked: "We cannot process this transaction at this time. Please contact support for assistance." (do not reveal AML reason)
- Delayed transaction: "Your withdrawal is being reviewed and will be processed within 48 hours."
- Account frozen: "Your account is temporarily restricted. Please contact support at compliance@elevatefi.com."

**Acceptance Criteria**:
- AML rule accuracy >98% (minimize false positives)
- Manual review time <24 hours for flagged transactions
- SAR filing compliance 100% (all required SARs filed on time)
- Zero regulatory fines for AML violations
- Transaction screening API uptime >99.99%

---

### 4.2 Company/Issuer Features

**Overview**

Companies (issuers) use the platform to raise capital by creating tokenized campaigns. The issuer features must balance ease of use with regulatory compliance, providing a comprehensive toolkit for campaign management, investor relations, and cap table administration.

---

#### 4.2.1 Campaign Creation Wizard

**FR-COMPANY-001: Multi-Step Campaign Creation**

**Description**: Guided 7-step wizard for creating fundraising campaigns

**Wizard Steps**:

**Step 1: Company Profile**
- Company name (required)
- Legal entity name (required, if different from display name)
- Company registration number (required)
- Country of incorporation (required, dropdown)
- Industry/sector (required, dropdown: Fintech, Healthcare, E-commerce, SaaS, Green Tech, etc.)
- Company website (optional, URL validation)
- Company description (required, 500-2000 characters)
  - Mission statement
  - Problem being solved
  - Solution overview
  - Target market
- Founded date (required)
- Company size:
  - Number of employees (dropdown: 1-10, 11-50, 51-200, 201-500, 500+)
  - Annual revenue (optional): <$100K, $100K-$1M, $1M-$10M, $10M+, Not disclosed
- Company logo (required, max 2MB, formats: PNG, SVG preferred)
- Banner image (optional, max 5MB, 1200x400px recommended)
- Social links (optional):
  - LinkedIn
  - Twitter
  - Facebook
  - Instagram
  - YouTube

**Step 2: Team Information**
- Add team members (min 2, max 10 for campaign display)
- For each team member:
  - Name (required)
  - Role/title (required)
  - Bio (required, 200-500 characters)
  - Photo (required, max 2MB)
  - LinkedIn URL (required for verification)
  - Twitter handle (optional)
  - Email (optional, for investor inquiries)
- Founder designations (mark at least 1 as founder/co-founder)
- Advisors section (optional, max 5):
  - Same fields as team members
  - Advisory capacity (Board member, Technical advisor, Industry expert, etc.)

**Step 3: Fundraising Details**
- Fundraising type (required):
  - Equity (Common shares, Preference shares)
  - Convertible note
  - SAFE agreement
  - Revenue share
  - Token sale (utility token, not security - Phase 2)
- Target raise amount (required):
  - Minimum: $50,000 USD
  - Maximum: $5,000,000 USD (Phase 1)
  - Currency: USD (USDC/USDT stablecoin backing)
- Minimum goal (all-or-nothing threshold):
  - Default: Same as target raise
  - Optional soft cap: 50-100% of target raise
- Overfunding allowed:
  - Yes/No toggle
  - If yes: Maximum overfunding (default: 150% of target)
- Valuation (required for equity):
  - Pre-money valuation (USD)
  - Post-money valuation (auto-calculated)
  - Equity being offered (percentage, auto-calculated or manual entry)
- Share price (for equity):
  - Price per share (USD)
  - Number of shares being issued
- Minimum investment per investor:
  - Default: $100 USD
  - Custom: $100-$10,000 range
- Maximum investment per investor (optional):
  - To prevent over-concentration
  - Recommended: 10-20% of total raise
- Campaign duration:
  - 30 days
  - 60 days (recommended)
  - 90 days
  - Custom (max 120 days with approval)
- Use of funds breakdown (required):
  - Must total 100%
  - Categories:
    - Product development (%)
    - Marketing & sales (%)
    - Operations & hiring (%)
    - Working capital (%)
    - Research & development (%)
    - Legal & compliance (%)
    - Other (specify, %)
  - Visual pie chart displayed

**Step 4: Financial Information**
- Upload financial documents (required):
  - Balance sheet (PDF, Excel)
  - Profit & loss statement (PDF, Excel)
  - Cash flow statement (PDF, Excel)
  - Last 3 years preferred, minimum 1 year
- Financial highlights (manual entry for display):
  - Monthly recurring revenue (MRR) or annual revenue
  - Revenue growth rate (% YoY)
  - Gross margin (%)
  - Burn rate (monthly)
  - Runway (months)
  - Customer count
  - Customer acquisition cost (CAC)
  - Lifetime value (LTV)
- Funding history (optional):
  - Previous rounds (Seed, Series A, etc.)
  - Amount raised
  - Lead investors
  - Valuation at each round
- Current investors (optional):
  - Investor names (notable angels, VCs)
  - Percentage ownership

**Step 5: Documents & Media**
- Pitch deck (required):
  - PDF format, max 20MB
  - Recommended: 10-15 slides
  - Must include: Problem, Solution, Market, Traction, Team, Financials, Ask
- Business plan (optional):
  - PDF format, max 50MB
- Legal documents (required):
  - Certificate of incorporation
  - Shareholder agreement (if applicable)
  - Term sheet for this fundraise
  - Any regulatory approvals (if applicable)
- Video pitch (required):
  - Upload or YouTube/Vimeo link
  - Recommended length: 2-5 minutes
  - Format: MP4, WebM, max 500MB for upload
  - Cover: Founder introduction, problem, solution, traction, ask
- Product demo (optional):
  - Video or live link to product
- Additional media (optional):
  - Product screenshots (max 10 images)
  - Press coverage (links)
  - Awards & recognition
  - Patents or IP documentation

**Step 6: Investor Perks & Terms**
- Investor benefits (optional but recommended):
  - Early access to product
  - Lifetime discount (specify %)
  - VIP support
  - Exclusive events/webinars
  - Custom perks (free-form text)
- Lock-up period:
  - Default: 12 months (enforced via smart contract)
  - Custom: 12-36 months (requires explanation)
- Distribution schedule (for revenue share):
  - Quarterly (recommended)
  - Semi-annually
  - Annually
- Voting rights (for equity):
  - Standard voting rights
  - Non-voting shares
  - Preference shares (specify preferences)
- Exit strategy (required):
  - IPO target timeline
  - Acquisition potential
  - Buyback terms (if applicable)
  - Secondary market trading (after lock-up)

**Step 7: Review & Submit**
- Campaign preview (read-only view as investors will see it)
- Sections displayed:
  - All previous steps summarized
  - AI-generated campaign score preview (estimated)
  - Compliance checklist:
    - ✓ All required documents uploaded
    - ✓ Team LinkedIn profiles verified
    - ✓ Financial statements provided
    - ✓ Legal entity verified
    - ✓ Terms of service agreed
- Edit buttons for each section
- Final declarations (checkboxes required):
  - "I confirm all information provided is accurate and up-to-date"
  - "I understand this campaign will be reviewed by Elevate Finance compliance team (3-7 business days)"
  - "I agree to pay the platform fee (2% of funds raised) upon successful campaign completion"
  - "I agree to the Terms of Service and Issuer Agreement"
- Submit for review button
- Save as draft button (can return later to complete)

**Draft Management**:
- Auto-save every 30 seconds
- Drafts stored for 90 days
- Resume draft from dashboard
- Share draft link with team members for collaboration (internal preview only)

**UI/UX Requirements**:
- Progress indicator (Step 1 of 7)
- Previous/Next navigation buttons
- Save & continue later option at any step
- Validation at each step (cannot proceed with incomplete required fields)
- Estimated time to complete: Display "~30-45 minutes" at start
- Help tooltips for complex fields (explain what info is needed)
- Character/word counters for text fields
- File upload drag & drop with preview
- Mobile-responsive (but recommend desktop for easier document upload)

**Error Handling**:
- Missing required fields: Highlight in red with specific error message
- Invalid file formats: "Please upload a PDF file. [filename] is not supported."
- File too large: "File size exceeds maximum of [X]MB. Please compress or split the file."
- Network error during auto-save: "Auto-save failed. Please check your connection. Your changes may not be saved."
- Duplicate campaign: "You already have a draft campaign for [Company Name]. Would you like to continue editing it or create a new campaign?"

**Acceptance Criteria**:
- Campaign creation completion rate >60% (users who start and submit)
- Average time to complete: 35-50 minutes
- Draft abandonment rate <30%
- Zero data loss from auto-save failures
- Mobile completion rate >20% (though desktop is preferred)

---

**FR-COMPANY-002: Campaign Preview Mode**

**Description**: Preview campaign as investors will see it before submission

**Preview Features**:
- Exact replica of live campaign page
- All sections visible:
  - Company profile with logo and banner
  - Fundraising progress bar (shown at 0%)
  - Team section with photos and bios
  - Financial highlights
  - Use of funds chart
  - Video pitch embedded
  - Documents downloadable (for preview user only)
  - AI score placeholder (will be calculated after approval)
  - Investment call-to-action (disabled in preview)
- Watermark: "PREVIEW MODE - Campaign not yet live"
- Share preview link:
  - Generate shareable link for team/advisors
  - Link expires after 7 days
  - Password protection option
  - No public indexing (noindex, nofollow meta tags)
- Preview analytics:
  - Track views on preview link
  - Time spent on page
  - Sections viewed
  - Devices used (helps optimize campaign for audience)

**UI Components**:
- Preview button (available in draft and after submission during review)
- Full-page preview (exit preview button to return to editor)
- Share preview modal (generate link, copy to clipboard, email to collaborators)
- Preview analytics dashboard (views, engagement metrics)

**Error Handling**:
- Missing required sections: Display placeholder text "This section is incomplete"
- Preview link expired: "This preview link has expired. Please request a new link from the campaign creator."
- Preview link access denied: "This preview link is password-protected. Please enter the password to view."

**Acceptance Criteria**:
- Preview accuracy 100% (matches live campaign exactly)
- Preview link generation time <2 seconds
- Share preview usage >40% of campaigns (indicates collaboration)
- Preview feedback collection: Optional survey "Is your campaign ready to publish?"

---

#### 4.2.2 Document Management

**FR-COMPANY-003: Document Upload & Version Control**

**Description**: Centralized document management for campaign materials

**Document Categories**:

**1. Legal Documents** (required for campaign approval):
- Certificate of incorporation
- Shareholder agreement
- Board resolutions approving fundraise
- Term sheet
- Subscription agreement template
- Regulatory filings (if applicable)

**2. Financial Documents** (required):
- Balance sheet (last 1-3 years)
- Profit & loss statement
- Cash flow statement
- Tax returns (if available)
- Bank statements (last 3-6 months)
- Cap table (current ownership structure)

**3. Marketing Materials** (required):
- Pitch deck
- Business plan
- Video pitch
- Product screenshots/images
- Company logo and branding assets

**4. Compliance Documents** (generated by system):
- KYC verification for company directors
- AML screening results
- Compliance approval letter
- Investor subscription agreements (signed)
- Tax forms (generated for investors)

**Document Upload Features**:
- Drag & drop interface
- Bulk upload (select multiple files)
- File formats accepted:
  - Documents: PDF, DOCX, XLSX, PPTX
  - Images: JPG, PNG, SVG, WebP
  - Videos: MP4, WebM, MOV (max 500MB)
  - Archives: ZIP (max 100MB, auto-extracted)
- File size limits:
  - Individual files: Max 50MB (except videos: 500MB)
  - Total campaign storage: 1GB (Phase 1), expandable on request
- Virus scanning (all uploads scanned before acceptance)
- OCR (Optical Character Recognition) for searchable PDFs

**Version Control**:
- Multiple versions of same document supported
- Version history:
  - Version number (auto-incremented: v1.0, v1.1, v2.0)
  - Upload date and time
  - Uploaded by (user name)
  - File size
  - Download count
- Compare versions (side-by-side view for PDFs)
- Revert to previous version
- Mark version as "Current" (displayed to investors)
- Delete old versions (admin only, after campaign approval)

**Access Control**:
- Public documents (visible to all investors):
  - Pitch deck
  - Business plan (if company chooses to make public)
  - Video pitch
  - Product images
- Private documents (visible to investors who invest):
  - Financial statements (detailed)
  - Legal agreements
  - Due diligence materials
- Admin-only documents (not visible to investors):
  - KYC/AML screening results
  - Internal compliance notes
  - Regulatory correspondence

**Document Expiry & Reminders**:
- Set expiry dates for time-sensitive documents (e.g., bank statements older than 6 months)
- Email reminders 30 days before expiry: "Your [document name] will expire soon. Please upload an updated version."
- Expired documents flagged in admin review queue

**Document Sharing**:
- Generate shareable links for individual documents
- Link expiry options: 24 hours, 7 days, 30 days, No expiry
- Password protection option
- Download count tracked
- Watermark applied to downloaded documents (company name, download date, "Confidential")

**UI Components**:
- Document library (categorized folders)
- Upload button (drag & drop area)
- Document list (table with name, version, size, upload date, actions)
- Version history modal (per document)
- Document preview (PDF viewer, image viewer, video player)
- Batch actions (delete selected, download selected as ZIP)

**Error Handling**:
- File too large: "File size exceeds maximum of [X]MB. Please compress the file or contact support for assistance."
- Unsupported format: "File format [.ext] is not supported. Please convert to PDF, DOCX, JPG, or PNG."
- Virus detected: "This file contains malware and cannot be uploaded. Please scan your file and try again."
- Storage limit reached: "You've reached your storage limit (1GB). Please delete old documents or contact support to upgrade."
- Upload failed: "Upload failed. Please check your connection and try again."

**Acceptance Criteria**:
- Upload success rate >99.5%
- Document preview load time <2 seconds
- Version control tracking accuracy 100%
- Zero malware uploaded to platform
- Average document access time (for investors) <1 second

---

**FR-COMPANY-004: Automated Document Verification**

**Description**: AI-powered verification of uploaded documents for completeness and accuracy

**Verification Checks**:

**1. Document Completeness**:
- Pitch deck must have:
  - Title slide
  - Problem slide
  - Solution slide
  - Market size slide
  - Business model slide
  - Team slide
  - Financials slide
  - Ask/funding slide
- AI scans PDF and flags missing sections
- Recommendations: "Your pitch deck is missing a [section name] slide. Consider adding one for completeness."

**2. Financial Statement Validation**:
- Balance sheet validation:
  - Assets = Liabilities + Equity (must balance)
  - Extract numbers using OCR + ML
  - Flag discrepancies: "Your balance sheet does not balance. Assets ($X) ≠ Liabilities + Equity ($Y). Please review."
- P&L validation:
  - Revenue - Expenses = Net Income
  - Flag if formulas don't match
- Cash flow validation:
  - Beginning cash + net cash flow = ending cash
  - Flag if not reconciled

**3. Data Extraction**:
- Auto-extract key figures from financial statements:
  - Revenue (latest year)
  - Net income/loss
  - Total assets
  - Total liabilities
  - Cash on hand
- Pre-populate "Financial Highlights" section
- User can review and edit extracted data

**4. Red Flag Detection**:
- Extremely high burn rate (>50% of cash on hand per month)
- Negative equity
- Declining revenue (YoY)
- Very low gross margins (<10%)
- Unsustainable runway (<3 months)
- Display warnings (not blockers): "Our AI detected [red flag]. This may raise concerns with investors. Please provide additional context in your campaign description."

**5. Legal Document Check**:
- Incorporation certificate:
  - Company name matches campaign
  - Incorporation date provided
  - Jurisdiction verified
- Term sheet:
  - Valuation mentioned
  - Share class specified
  - Investor rights outlined

**Admin Review**:
- All AI flags visible in admin review dashboard
- Compliance officer can:
  - Approve despite flags (with justification)
  - Request clarification from company
  - Reject campaign (if critical issues)

**UI Components**:
- Document verification status badges (Verified, Pending, Flagged)
- AI insights panel (warnings, recommendations, extracted data)
- Accept AI suggestions button (pre-fill fields with extracted data)

**Error Handling**:
- Extraction failed: "We couldn't extract data from this document. Please ensure the file is not password-protected or scanned at low resolution."
- Verification warnings: Displayed as non-blocking notifications (user can proceed but admins will review)

**Acceptance Criteria**:
- Data extraction accuracy >85% (for well-formatted documents)
- Red flag detection rate >90% (for known issues)
- False positive rate <15% (avoid over-flagging legitimate cases)
- Admin review time reduced by 40% (due to AI pre-screening)

---

#### 4.2.3 Investor Communications

**FR-COMPANY-005: Campaign Updates & Announcements**

**Description**: Communicate with investors throughout campaign lifecycle

**Update Types**:

**1. Campaign Progress Updates** (automated):
- Milestones reached:
  - 25% funded
  - 50% funded
  - 75% funded
  - 100% funded (goal reached)
  - Overfunding milestones (125%, 150%)
- Countdown reminders:
  - 7 days remaining
  - 3 days remaining
  - 24 hours remaining
  - 6 hours remaining
- New investors joined:
  - "[X] new investors joined today!"
  - "We're now at [Y] total investors"

**2. Manual Company Updates**:
- Rich text editor for announcements:
  - Text formatting (bold, italic, lists, headings)
  - Embed images (inline)
  - Embed videos (YouTube, Vimeo)
  - Attach documents (max 10MB)
- Update categories (tags):
  - Product development
  - Traction milestone (new customers, revenue growth)
  - Team expansion (new hires, advisors)
  - Partnership announcement
  - Media coverage
  - Fundraising progress
  - General news
- Visibility:
  - Public (visible to all platform users, good for SEO)
  - Investors only (only those who invested)
  - Private (draft, not yet published)
- Publish immediately or schedule for later (date/time picker)

**3. Q&A Feature**:
- Investors can post questions (comment thread)
- Company can reply publicly (visible to all)
- Upvote questions (most popular questions highlighted)
- Mark answer as "Official" (verified by company)
- Email notification to investor when question answered
- Q&A moderation:
  - Company can hide inappropriate questions (flagged for admin review)
  - Admins can remove spam or offensive content

**4. Investor Messages (1-to-1)**:
- Direct messaging between company and individual investors
- Use cases:
  - Follow-up on large investments
  - Answer private questions
  - Request additional documentation
- Message threading (conversation history)
- File attachments (max 5MB)
- Read receipts (message seen by recipient)
- Email notifications (new message received)

**5. Bulk Email Campaigns**:
- Send email to all investors or specific segments:
  - All investors
  - Investors who invested >$X
  - Investors from specific country
  - Investors who haven't completed KYC (reminder)
- Email templates:
  - Plain text
  - HTML (rich formatting, images, logos)
- Preview email before sending
- Track email metrics:
  - Delivery rate
  - Open rate
  - Click-through rate (for links in email)
- Unsubscribe option (required for marketing emails, not transactional)

**Communication Best Practices** (displayed in UI):
- Recommended: Post updates at least once every 2 weeks during campaign
- Respond to investor questions within 48 hours
- Be transparent about challenges and setbacks (builds trust)
- Celebrate milestones with investors (they're your biggest supporters)

**UI Components**:
- Updates tab (on campaign dashboard)
- "Post Update" button (opens rich text editor)
- Update feed (chronological, with filters by category)
- Q&A section (on campaign page, sorted by upvotes)
- Messages inbox (similar to email client)
- Bulk email composer (with segment selector and preview)

**Notification Settings** (Investor-side):
- Investors can customize notifications:
  - All updates from campaigns I invested in
  - Only major milestones (50%, 100% funded)
  - Q&A responses to my questions
  - Direct messages from companies
  - No notifications (opt-out)

**Error Handling**:
- Message send failed: "We couldn't send your message. Please check your connection and try again."
- Email delivery failed: "Some emails could not be delivered. [X] of [Y] emails failed. Please review the email addresses."
- Update publish failed: "We couldn't publish your update. Please try again."

**Acceptance Criteria**:
- Average company response time to Q&A: <48 hours
- Update frequency: >70% of campaigns post at least 1 update per week
- Email open rate: >40% (industry benchmark: 20-30%)
- Investor engagement: >50% of investors read at least 1 update

---

**FR-COMPANY-006: Investor Dashboard (Company View)**

**Description**: Real-time visibility into investor activity and campaign performance

**Dashboard Sections**:

**1. Campaign Performance Overview**:
- Key metrics (large, prominent display):
  - Total raised (USD)
  - Percentage of goal (progress bar)
  - Number of investors
  - Average investment size
  - Days remaining
  - Funding velocity ($ raised per day)
- Charts:
  - Fundraising timeline (line chart: cumulative $ raised over time)
  - Daily investment activity (bar chart: $ raised per day)
  - Investor growth (line chart: cumulative investors over time)
  - Investment size distribution (histogram: number of investors by investment amount)

**2. Investor List**:
- Table showing all investors:
  - Investor name (or "Anonymous" if privacy enabled)
  - Investment amount (USD)
  - Investment date
  - Country (flag icon)
  - KYC status (Verified, Pending)
  - Contact button (send message)
- Filters:
  - By country
  - By investment amount (>$1K, >$5K, >$10K)
  - By date (last 7 days, last 30 days, all time)
- Export to CSV (for internal records, cap table management)
- Sort by: Amount (high to low), Date (newest first), Name (A-Z)

**3. Geographic Distribution**:
- World map showing investor locations
- Color intensity based on number of investors per country
- Hover to see: [Country name]: [X] investors, $[Y] raised
- Top 5 countries by investment volume (list below map)

**4. Referral Tracking** (Phase 2):
- Track where investors came from:
  - Direct (typed URL or bookmark)
  - Social media (Twitter, LinkedIn, Facebook)
  - Email campaign
  - Referral from another investor
- Top referral sources (table with source, visits, conversions, $ raised)
- Referral links:
  - Generate custom referral links for company to share
  - Track performance per link

**5. Engagement Metrics**:
- Campaign page views (total, unique)
- Video pitch plays (total, completion rate)
- Document downloads (which docs are most popular)
- Q&A engagement (questions asked, answers provided, avg response time)
- Update views (which updates get most engagement)

**6. AI Performance Score**:
- AI campaign score (1-10 scale)
- Score breakdown:
  - Financial strength: [X]/10
  - Team credibility: [X]/10
  - Market opportunity: [X]/10
  - Sentiment analysis: [X]/10
  - Overall: [X]/10
- AI recommendation rate: "[Y]% of eligible investors received an AI recommendation for your campaign"
- Improvement suggestions:
  - "Add more traction metrics to improve your score"
  - "Respond to investor questions faster to boost sentiment"

**7. Alerts & Action Items**:
- Pending actions (highlighted in red/yellow):
  - [X] unanswered investor questions
  - [Y] days since last update (recommend posting update)
  - KYC verification needed for [Z] investors (blocking fund release)
  - Campaign ending in [N] days
- Milestone alerts:
  - "You reached 50% of your goal! 🎉"
  - "You're trending! 20% increase in daily investments this week"

**Real-time Updates**:
- Dashboard auto-refreshes every 30 seconds (when tab is active)
- Toast notifications for new investments:
  - "[Investor Name] just invested $[X]!"
  - Confetti animation for large investments (>$5,000)
- WebSocket integration for live updates (no page refresh needed)

**UI Components**:
- Dashboard (multi-section layout, cards for each metric)
- Interactive charts (using Chart.js or D3.js, with hover tooltips)
- Export buttons (CSV, PDF reports)
- Date range selector (last 7 days, 30 days, campaign lifetime)

**Error Handling**:
- Data load failed: "We couldn't load your dashboard data. Please refresh the page."
- Export failed: "Export failed. Please try again or contact support."
- Real-time connection lost: "Live updates paused. Reconnecting..." (auto-retry)

**Acceptance Criteria**:
- Dashboard load time <2 seconds (initial load)
- Real-time update latency <5 seconds (from investment to dashboard update)
- Data accuracy 100% (matches blockchain records)
- Export success rate >99%
- Mobile dashboard usability score >80% (though desktop is primary)

---

#### 4.2.4 Milestone Management

**FR-COMPANY-007: Milestone-Based Fund Release**

**Description**: Define milestones for escrow fund release, subject to investor voting

**Milestone Configuration** (during campaign creation):

**Default Milestones** (recommended):
1. Campaign successful completion: 20% of funds released immediately
2. Product development milestone (3 months): 25% released
3. Revenue target achieved (6 months): 25% released
4. Customer acquisition goal (9 months): 15% released
5. Final release (12 months): 15% released

**Custom Milestones** (company can define):
- Milestone name (e.g., "Beta launch completed")
- Description (what constitutes completion, evidence required)
- Percentage of funds to release (must total 100%)
- Target date (estimate)
- Evidence requirements:
  - Document upload (product screenshots, revenue reports, etc.)
  - Third-party verification (auditor, advisor, customer testimonial)
  - Investor vote (requires X% approval, configurable: 50%, 66%, 75%)

**Milestone Tracking**:
- Milestone dashboard (company view):
  - List of all milestones
  - Status: Upcoming, In Progress, Under Review, Approved, Rejected, Completed
  - Progress indicator (if milestone is quantifiable, e.g., "500/1000 customers acquired")
  - Evidence uploaded (documents, links)
  - Investor votes (if voting required)
- Timeline view:
  - Visual timeline showing all milestones and target dates
  - Color-coded by status (green=completed, yellow=in progress, gray=upcoming)

**Milestone Submission Flow** (company):
1. Company marks milestone as "Ready for Review"
2. Company uploads evidence (required documents, reports, screenshots)
3. Company writes update explaining milestone completion
4. Investors notified via email: "Vote required: [Company Name] has submitted [Milestone Name] for approval"
5. Voting period opens (default: 14 days)
6. Investors vote: Approve or Reject (with optional comment/reason)
7. Voting threshold:
   - Simple majority (>50% of investors by investment amount)
   - OR 66% supermajority (for critical milestones)
8. If approved: Funds released from escrow to company wallet (on-chain transaction)
9. If rejected: Company must address concerns and resubmit

**Investor Voting**:
- Voting weight: Proportional to investment amount
  - Investor with $10,000 investment has 10x voting power of investor with $1,000
- Voting interface:
  - Milestone details (name, description, evidence)
  - View evidence (documents, images, links)
  - Vote buttons: ✅ Approve, ❌ Reject
  - Comment box (optional: "Why I'm voting this way")
- Voting deadline countdown
- Abstain option (investor doesn't vote, not counted in total)
- Vote delegation (Phase 2): Allow investors to delegate votes to trusted proxy

**Dispute Resolution**:
- If milestone rejected:
  - Company can appeal (provide additional evidence, clarification)
  - Second vote (same threshold)
- If second vote also fails:
  - Escalation to platform mediator (neutral third-party)
  - Mediator reviews evidence and investor concerns
  - Mediator decision is binding (approve or reject)
  - If rejected: Funds remain in escrow, released at next milestone or refunded

**Emergency Fund Release**:
- Company can request emergency release (outside milestones):
  - Reason: Unexpected opportunity, critical expense, runway extension
  - Requires 75% supermajority approval (higher threshold for emergency)
  - Max 10% of remaining escrowed funds per request
  - Limited to 2 emergency requests per year

**Automated Milestone Tracking** (Phase 2+):
- Integration with company systems (e.g., Stripe for revenue tracking)
- Automatic milestone completion when criteria met:
  - "Revenue >$100K MRR" → Stripe API confirms MRR >$100K → Milestone auto-submitted
  - "1,000 customers acquired" → CRM API confirms customer count → Milestone auto-submitted
- Reduces manual work and increases trust (verifiable on-chain)

**UI Components**:
- Milestone creation form (during campaign setup)
- Milestone dashboard (company and investor views)
- Milestone detail page (evidence, voting, comments)
- Voting interface (investor-side)
- Timeline visualization (Gantt chart-style)

**Error Handling**:
- Milestone submission without evidence: "Please upload evidence before submitting for review"
- Fund release failure: "Fund release failed. Please contact support." (blockchain transaction error)
- Voting period expired: "Voting period has ended. [X]% voted in favor. Result: [Approved/Rejected]"

**Acceptance Criteria**:
- Milestone approval rate >70% (indicates realistic milestone-setting)
- Average voting participation >60% (by investment amount)
- Fund release time <24 hours after approval (blockchain finality)
- Dispute rate <10% of milestones
- Automated tracking accuracy >95% (Phase 2+)

---

**FR-COMPANY-008: Post-Campaign Investor Relations**

**Description**: Ongoing communication and updates after campaign closes

**Quarterly Reporting** (required):
- Quarterly reports due: March 31, June 30, Sept 30, Dec 31 (+15 days grace period)
- Report template (generated by platform):
  - Executive summary (what was accomplished this quarter)
  - Financial highlights:
    - Revenue (vs. previous quarter, vs. same quarter last year)
    - Expenses breakdown
    - Cash on hand
    - Burn rate
    - Runway
  - Key metrics:
    - Customer count
    - MRR/ARR
    - Gross margin
    - Customer acquisition cost (CAC)
    - Lifetime value (LTV)
  - Product development:
    - Features shipped
    - Product roadmap progress
  - Team updates:
    - New hires
    - Key departures
  - Challenges & risks:
    - Obstacles faced
    - Mitigation strategies
  - Next quarter goals:
    - Specific, measurable objectives
- Upload to platform (PDF or fill out web form)
- Investors notified via email when report published
- Historical reports archived (searchable by quarter/year)

**Annual General Meeting (AGM)**:
- Required for equity investors (regulatory compliance)
- AGM scheduling:
  - Company proposes date/time (within 6 months of fiscal year end)
  - Investors notified 30 days in advance
  - RSVP system (attending in person, attending virtually, not attending)
- Agenda items:
  - Financial results presentation
  - Board of directors election (if applicable)
  - Major corporate actions (mergers, acquisitions, amendments to articles)
  - Q&A session
- Virtual AGM support (Phase 2):
  - Live video streaming
  - Virtual voting (real-time)
  - Chat for Q&A
- Minutes published:
  - Meeting summary (decisions made, votes cast)
  - Uploaded within 14 days of AGM

**Distribution Payments**:
- Payment schedule (configured during campaign creation):
  - Quarterly (recommended for revenue share models)
  - Semi-annually
  - Annually
  - Milestone-based (e.g., after exit event)
- Distribution calculation:
  - Total distributable amount (profits, revenue share, etc.)
  - Investor allocation (proportional to ownership)
  - Automated calculation and payment (via smart contract)
- Distribution notification:
  - Email sent before distribution: "Your [Company Name] distribution of $[X] will be sent on [Date]"
  - On-chain transfer to investor's wallet (same stablecoin as investment)
  - Email confirmation after transfer: "Distribution received: $[X] USDC sent to your wallet [address]"
- Distribution history:
  - Table showing all past distributions (date, amount, transaction ID)
  - Total distributions received (lifetime)
  - Annualized return on investment (ROI)

**Exit Events**:
- IPO, acquisition, merger:
  - Company notifies investors immediately (via platform update)
  - Provide exit terms (price per share, timeline, process)
  - Investor options:
    - Accept exit terms (sell shares)
    - Hold shares (if applicable, e.g., publicly traded post-IPO)
  - Distribution of proceeds:
    - Automated calculation based on share ownership
    - Payment within 30 days of exit completion
- Buyback offers:
  - Company offers to buy back shares (provide price, deadline)
  - Investors can accept or decline
  - Buyback executed via smart contract (atomic swap)

**Secondary Market Trading** (Phase 2):
- After lock-up period ends, investors can trade tokens on secondary market
- Company can view secondary market activity:
  - Trading volume
  - Token price (last trade, 7-day average, 30-day average)
  - Liquidity (bid/ask spread)
- Company announcements impact token price:
  - Track price movements after updates, milestones, reports
  - Investor sentiment visible in real-time

**Investor Surveys** (optional):
- Company can send surveys to investors:
  - Product feedback
  - Strategic direction input
  - Investor satisfaction (NPS-style)
- Survey results aggregated and displayed
- Use insights to improve investor relations

**UI Components**:
- Post-campaign dashboard (distinct from active campaign dashboard)
- Quarterly report upload/form
- AGM scheduler and RSVP tracker
- Distribution history table
- Exit event announcement page
- Secondary market price chart (Phase 2)

**Error Handling**:
- Late quarterly report: Automated reminder emails at +7 days, +14 days overdue
- Distribution payment failed: "Distribution payment failed. Please check your wallet address and contact support."
- AGM scheduling conflict: "Some investors cannot attend on [Date]. Consider rescheduling or offering virtual attendance."

**Acceptance Criteria**:
- Quarterly report on-time rate >85%
- Distribution payment accuracy 100% (correct amounts to correct wallets)
- Investor satisfaction with post-campaign communication >75% (via surveys)
- AGM attendance rate >40% (in-person or virtual)
- Secondary market liquidity (Phase 2): >$10K daily trading volume for successful campaigns

---

#### 4.2.5 Cap Table Management

**FR-COMPANY-009: Automated Cap Table Tracking**

**Description**: Real-time cap table updated automatically based on on-chain transactions

**Cap Table Features**:

**1. Shareholder List**:
- Automatically populated from blockchain data:
  - Shareholder name (linked to verified KYC identity)
  - Number of shares/tokens held
  - Percentage ownership
  - Investment amount (USD equivalent)
  - Investment date
  - Wallet address (truncated for privacy: 0x1234...5678)
- Shareholder categories:
  - Founders (tagged manually by company)
  - Employees (ESOP shares)
  - Angels (early investors)
  - Crowdfund investors (from campaign)
  - VCs/Institutions (if applicable)
- Fully diluted calculation:
  - Current ownership
  - Fully diluted ownership (assuming all options/warrants exercised)

**2. Historical Transactions**:
- Complete transaction log (immutable, blockchain-backed):
  - Date
  - Transaction type (Initial issue, Transfer, Buyback, Exercise)
  - From (sender wallet)
  - To (recipient wallet)
  - Number of shares
  - Price per share (if applicable)
  - Transaction hash (link to blockchain explorer)
- Filters:
  - By shareholder
  - By date range
  - By transaction type

**3. Cap Table Versions**:
- Snapshot cap table at specific dates:
  - Pre-money (before current round)
  - Post-money (after current round)
  - Post-ESOP (after employee option pool allocation)
- Compare versions side-by-side

**4. Ownership Pie Chart**:
- Visual representation of ownership distribution
- Color-coded by shareholder category
- Hover to see: [Name]: [X]% ownership, [Y] shares

**5. Vesting Schedules** (for employee options):
- Track vesting schedules for ESOP shares:
  - Employee name
  - Total options granted
  - Vesting schedule (4-year with 1-year cliff, etc.)
  - Vested shares (to date)
  - Unvested shares
  - Next vesting date
- Automated vesting:
  - Smart contract enforces vesting schedule
  - Shares unlocked automatically on vesting dates
  - Email notifications to employees

**6. Option Pool Management**:
- Configure ESOP (Employee Stock Ownership Plan):
  - Total option pool size (% of company)
  - Options granted (to specific employees)
  - Options available (remaining in pool)
- Grant options (admin action):
  - Select employee
  - Number of options
  - Exercise price
  - Vesting schedule
  - Generate option grant letter (PDF)

**7. Cap Table Export**:
- Export formats:
  - CSV (for Excel)
  - PDF (for board meetings, investor reports)
  - Carta import format (Phase 2, if company uses Carta for equity management)
- Export scope:
  - Full cap table
  - Filtered (e.g., only crowdfund investors)
  - Historical snapshot (as of specific date)

**8. Compliance Checks**:
- Ownership concentration alerts:
  - Single investor owns >25% (may trigger regulatory requirements)
  - Foreign ownership >50% (if restricted by local laws)
- Regulatory limits:
  - Singapore: Max 50 non-accredited investors per offer (check before campaign approval)
  - Hong Kong: Prospectus required if >50 investors (alert if approaching limit)
- Transfer restrictions:
  - Lock-up period enforcement (shares cannot be transferred on-chain)
  - Whitelist-only transfers (only KYC-verified wallets can receive shares)

**9. Corporate Actions**:
- Stock splits:
  - Forward split (1 share → 2 shares, halve price per share)
  - Reverse split (2 shares → 1 share, double price per share)
  - Execute via smart contract (automatic adjustment for all shareholders)
- Dividends/distributions:
  - Calculate amount per share
  - Distribute proportionally to all shareholders
  - Automated on-chain payment
- Share buybacks:
  - Company buys back shares from shareholders
  - Price per share offered
  - Acceptance period (shareholders opt in)
  - Execute buyback (on-chain transfer to company treasury)

**10. Scenario Modeling** (Phase 2):
- Model future fundraising rounds:
  - Input: New investment amount, pre-money valuation
  - Output: Post-money cap table (dilution for each shareholder)
  - Compare scenarios (raising $1M at $10M vs. $2M at $15M valuation)
- Exit value calculator:
  - Input: Exit valuation, exit type (acquisition, IPO)
  - Output: Payout per shareholder (after preferences, liquidation waterfalls)

**Real-time Blockchain Sync**:
- Cap table updates automatically when on-chain transactions occur:
  - New investment → Add shareholder
  - Share transfer → Update shareholder ownership
  - Vesting event → Unlock shares
- Sync frequency: Every 5 minutes (check blockchain for new transactions)
- Manual sync button (for immediate update)

**UI Components**:
- Cap table dashboard (table view with shareholder list)
- Ownership pie chart
- Historical transactions log
- Vesting schedule manager
- Export buttons (CSV, PDF)
- Scenario modeling tool (Phase 2)

**Error Handling**:
- Blockchain sync failed: "Cap table sync failed. Retrying... [Last synced: 5 minutes ago]"
- Export failed: "Export failed. Please try again or contact support."
- Invalid corporate action: "Stock split ratio must be a positive number (e.g., 2 for 2:1 split)"

**Acceptance Criteria**:
- Cap table accuracy 100% (matches on-chain data exactly)
- Sync latency <5 minutes (from blockchain transaction to cap table update)
- Export success rate >99%
- Compliance check accuracy >95% (flag potential regulatory issues)
- Vesting automation accuracy 100% (shares unlocked on correct dates)

---

### 4.3 Investor Features

This section defines the retail and institutional investor experience, including campaign discovery, AI-powered recommendations, investment flows, and portfolio management.

---

#### 4.3.1 Campaign Browsing & Discovery

**Purpose**: Enable investors to discover investment opportunities through intuitive browsing, filtering, and search.

**User Story**: As an investor, I want to browse active campaigns with powerful filtering so that I can discover opportunities matching my investment criteria.

**Functional Requirements**:

**Campaign Listing View**:
- Display active campaigns as cards (grid view default, list view optional)
- Each campaign card shows:
  - Company logo and name
  - Campaign title (e.g., "Series A - Expand to 3 New Markets")
  - Industry/sector tag
  - Funding progress bar (e.g., "$125,000 / $500,000 - 25%")
  - Days remaining (e.g., "45 days left")
  - AI Investment Score (0-100, color-coded: 0-40 red, 41-70 yellow, 71-100 green)
  - Minimum investment (e.g., "$100 USDC")
  - Expected annual return (company-provided estimate)
  - "Featured" badge (admin-curated, max 3 campaigns)
  - "New" badge (campaigns live <7 days)
- Default sort: AI Score (highest first)
- Pagination: 12 campaigns per page
- Infinite scroll option (user preference in settings)

**Filtering System**:
- **Region/Country**: Multi-select dropdown
  - Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia, "All Regions"
- **Industry/Sector**: Multi-select checkboxes
  - Technology, FinTech, HealthTech, E-commerce, Manufacturing, Real Estate, F&B, Education, Logistics, Other
- **Funding Goal**: Range slider
  - $50K-$100K, $100K-$250K, $250K-$500K, $500K-$1M, $1M-$3M, $3M-$5M
- **AI Investment Score**: Range slider (0-100)
- **Asset Type**: Radio buttons
  - Equity (Common Shares, Preference Shares, Convertible Notes, SAFE)
  - RWA (Real Estate, Inventory, IP, Revenue Streams)
- **Campaign Stage**: Checkboxes
  - Active (accepting investments)
  - Closing Soon (<7 days remaining)
  - Recently Funded (within last 30 days, for browsing only)
- **Minimum Investment**: Range slider ($100-$10,000)
- **Expected Returns**: Range slider (5%-30% annual)

**Saved Filters**:
- "Save Current Filters" button → Name and save filter preset
- Saved filter dropdown (max 5 presets per user)
- Example presets: "Singapore FinTech", "High AI Score (80+)", "Low Entry (<$500)"

**Search Functionality**:
- Search bar (top of page, always visible)
- Search by: Company name, campaign title, industry keywords
- Real-time suggestions (autocomplete dropdown)
- Search history (last 5 searches, user-specific)
- Advanced search toggle:
  - Boolean operators (AND, OR, NOT)
  - Exact phrase matching (quotes)
  - Wildcard search (asterisk)

**Sort Options** (dropdown):
- AI Score: High to Low (default)
- AI Score: Low to High
- Funding Progress: High to Low
- Funding Progress: Low to High
- Days Remaining: Ending Soon
- Days Remaining: Most Time Left
- Minimum Investment: Low to High
- Minimum Investment: High to Low
- Recently Added (newest first)
- Alphabetical (A-Z)

**UI Components**:
- Filter sidebar (left side, collapsible on mobile)
- Campaign card grid (responsive: 3 columns desktop, 2 tablet, 1 mobile)
- Active filters display (chips/tags, dismissible)
- "Clear All Filters" button
- Results count (e.g., "Showing 24 of 147 campaigns")
- Loading skeleton screens (while fetching)

**Performance Requirements**:
- Initial page load: <2s (desktop), <3s (mobile)
- Filter application: <500ms
- Search results: <300ms (real-time suggestions)
- Image loading: Lazy load campaign logos/thumbnails

**Error Handling**:
- No campaigns found: "No campaigns match your filters. Try adjusting your criteria or [Clear All Filters]"
- Search no results: "No results for '[search query]'. Try different keywords or browse [All Campaigns]"
- Network error: "Unable to load campaigns. [Retry] or check your connection."
- Invalid filter combination: Auto-adjust (e.g., if min investment > max goal, reset min investment)

**Acceptance Criteria**:
- Filter application updates results in <500ms (p95)
- Search autocomplete latency <100ms (p95)
- Campaign card rendering <50ms per card
- Mobile responsiveness (perfect display on 360px width)
- Accessibility: WCAG 2.1 AA compliant (keyboard navigation, screen reader support)

---

#### 4.3.2 Campaign Detail Page

**Purpose**: Provide comprehensive information about a campaign to help investors make informed decisions.

**User Story**: As an investor, I want to view detailed campaign information including financials, team, AI analysis, and Q&A so that I can perform due diligence before investing.

**Functional Requirements**:

**Page Structure** (tabbed interface):
1. Overview
2. Financials
3. Team & Company
4. AI Analysis
5. Documents
6. Updates
7. Q&A
8. Comments

**Tab 1: Overview**

**Hero Section**:
- Company logo (high-resolution)
- Campaign title and tagline
- Funding progress meter (visual bar + percentage)
- Key metrics grid (4 columns):
  - Target Amount (e.g., "$500,000 USDC")
  - Amount Raised (e.g., "$125,000 - 25%")
  - Days Remaining (countdown timer)
  - Number of Investors (e.g., "47 investors")
- AI Investment Score (large badge, color-coded, click for details)
- Primary CTA: "Invest Now" button (sticky on scroll)
- Secondary CTAs: "Add to Watchlist" (heart icon), "Share" (link icon)

**Campaign Description**:
- Problem statement (markdown support)
- Solution overview
- Business model
- Market opportunity
- Use of funds breakdown (pie chart):
  - Product Development: X%
  - Marketing & Sales: X%
  - Operations: X%
  - Working Capital: X%
  - Other: X%
- Milestones timeline (visual roadmap with dates)

**Investment Terms**:
- Asset type (Equity/RWA)
- Security type (Common Shares, Preference Shares, etc.)
- Valuation (pre-money, post-money)
- Share price or token price
- Minimum investment ($100 default, company can set higher)
- Maximum investment per investor (if any)
- Lock-up period (12 months minimum, displayed prominently)
- Expected returns (company-provided estimate with disclaimer)
- Distribution schedule (quarterly, semi-annual, annual)

**Risk Factors**:
- Company-provided risk disclosures (mandatory)
- Standardized risk warnings:
  - "Investing in early-stage companies is high risk. You may lose your entire investment."
  - "Tokens are subject to a 12-month lock-up period and cannot be transferred or sold."
  - "Past performance does not guarantee future results."
  - "This is not financial advice. Conduct your own due diligence."

**Tab 2: Financials**

**Financial Statements** (uploaded by company, verified by admin):
- Balance Sheet (most recent + 2 prior years)
- Profit & Loss Statement (most recent + 2 prior years)
- Cash Flow Statement (most recent + 2 prior years)
- Financial projections (3-year forward-looking, company-provided)

**Key Financial Metrics** (calculated automatically):
- Revenue (last 12 months)
- Revenue growth rate (YoY %)
- Gross margin (%)
- Net profit/loss (last 12 months)
- Burn rate (monthly, for pre-revenue companies)
- Runway (months of cash remaining)
- Customer acquisition cost (CAC)
- Lifetime value (LTV)
- LTV:CAC ratio
- Unit economics (if applicable)

**Data Visualization**:
- Revenue trend chart (line graph, 3 years historical + 3 years projected)
- Profitability chart (bar graph, quarterly)
- Cash flow waterfall chart
- Key metrics comparison table (industry benchmarks, if available)

**Download Options**:
- PDF export (all financial statements)
- CSV export (financial data)
- Excel export (with formulas intact)

**Data Verification Badge**:
- "Financials Verified by Admin" badge (if admin-approved)
- "Audited by [Firm Name]" badge (if externally audited)
- Last updated date

**Tab 3: Team & Company**

**Company Profile**:
- Full legal name
- Registration number (company registry)
- Incorporation date
- Headquarters location
- Number of employees
- Website (clickable link)
- Social media links (LinkedIn, Twitter, Facebook, Instagram)
- Industry classification (primary and secondary)

**Founders & Key Team**:
- Team member cards (photo, name, title, bio)
- For each team member:
  - LinkedIn profile link
  - Educational background
  - Work experience (prior companies, roles)
  - Notable achievements
  - Equity ownership (optional, company-provided)
- Advisors section (if applicable)
- Board of directors (if applicable)

**Company Traction** (metrics dashboard):
- Customers (total count)
- Active users (if applicable)
- Revenue (last 12 months)
- Partnerships (logos of key partners)
- Awards & recognition
- Media mentions (links to articles)

**Company History Timeline**:
- Founding date
- Major milestones (product launches, funding rounds, partnerships)
- Visual timeline (horizontal, scrollable)

**Tab 4: AI Analysis**

**AI Investment Score Breakdown**:
- Overall score (0-100, large display)
- Score components (weighted breakdown):
  1. Financial Health (30% weight): Score + explanation
  2. Founder Quality (25% weight): Score + explanation
  3. Market Opportunity (20% weight): Score + explanation
  4. Traction & Growth (15% weight): Score + explanation
  5. Risk Assessment (10% weight): Score + explanation

**Top 5 Positive Factors**:
- Bulleted list with confidence percentages
- Example: "Strong revenue growth (127% YoY) - 92% confidence"

**Top 5 Risk Factors**:
- Bulleted list with severity ratings (Low, Medium, High, Critical)
- Example: "High customer concentration risk (top 3 customers = 67% revenue) - High severity"

**Comparable Campaigns**:
- "Similar campaigns you may like" section
- Display 3 comparable campaigns (cards with basic info)
- Similarity factors: Industry, funding goal, AI score range

**AI Confidence Interval**:
- "This recommendation has a confidence interval of 70-85%"
- Explanation tooltip: "The AI model predicts this campaign's performance will fall within this range with 90% probability."

**Explainability Dashboard**:
- "How was this score calculated?" expandable section
- Feature importance chart (bar graph)
- Data sources used (list with timestamps)
- Model version (e.g., "AI Model v2.3.1 - Last trained: March 15, 2026")

**Human Oversight Badge**:
- "AI Recommendation Reviewed by Investment Team" (if Phase 1 human approval completed)
- Date of last review

**Disclaimer**:
- "AI analysis is for informational purposes only and does not constitute investment advice. Investors should conduct their own due diligence."

**Tab 5: Documents**

**Document Library**:
- All campaign-related documents uploaded by company
- Document types:
  - Pitch deck (PDF)
  - Business plan (PDF)
  - Financial statements (PDF, Excel)
  - Legal documents (Term sheet, Subscription agreement, Shareholder agreement)
  - Compliance certificates (registration, licenses)
  - Other supporting documents

**Document Cards**:
- Document name
- File type (PDF, DOCX, XLSX, PNG, etc.)
- File size (MB)
- Upload date
- Version number (if multiple versions)
- "Download" button
- "Preview" button (for PDFs, opens in-browser viewer)

**Document Versioning**:
- If multiple versions exist, show dropdown to select version
- "View Change History" link (shows upload dates and admin approval status)

**Document Security**:
- Watermark PDFs with investor name and timestamp (anti-leak measure)
- Track downloads (audit log: who downloaded what, when)
- Disable right-click and copy/paste in preview mode (basic DRM)

**Document Search**:
- Search within documents (full-text search for PDFs)
- Filter by document type

**Data Room Access**:
- Locked documents (for accredited investors only, Phase 2+)
- "Request Access" button if locked
- Admin approval required to unlock

**Tab 6: Updates**

**Campaign Updates Feed**:
- Chronological list of updates posted by company
- Each update shows:
  - Update title
  - Date posted
  - Content (markdown support, images, videos)
  - "Read More" (if long update)
  - Comment count (click to view comments)

**Update Types** (visual badges):
- Milestone Achieved (green badge)
- Financial Update (blue badge)
- Team Update (purple badge)
- Product Update (orange badge)
- General Announcement (gray badge)

**Posting Updates** (company view):
- Rich text editor (bold, italic, lists, links, images)
- Image upload (max 5MB per image)
- Video embed (YouTube, Vimeo links)
- "Preview" before publishing
- "Notify Investors" checkbox (sends email to all investors)

**Update Notifications**:
- Email notification to investors (if company checked "Notify Investors")
- In-app notification (bell icon, unread badge)
- Push notification (mobile app, Phase 2+)

**Update Engagement**:
- Like button (investors can like updates)
- Comment section (threaded comments)
- Share button (copy link to update)

**Tab 7: Q&A**

**Question & Answer Forum**:
- Investors can ask questions about the campaign
- Company responds (or designates team member to respond)
- Questions are public (all investors can see)

**Posting Questions**:
- Text input box (max 500 characters)
- "Post Question" button
- Real-time validation (no profanity, no personal attacks)
- Spam prevention (rate limit: 5 questions per user per day)

**Question Cards**:
- Question text
- Asker name (or "Anonymous" if user opts for anonymity)
- Date posted
- Upvote button (other investors can upvote questions)
- Answer section (company's response)
- "Answered" badge (green checkmark if company responded)
- Response time (e.g., "Answered in 2 hours")

**Sorting & Filtering**:
- Sort by: Most Upvoted, Newest, Oldest, Answered, Unanswered
- Filter by: Answered Only, Unanswered Only, All Questions

**Company Response SLA**:
- Target response time: 24 hours for questions with >10 upvotes
- Overdue indicator (red badge if >48 hours with no response)

**Moderation**:
- Admin can hide inappropriate questions (spam, offensive content)
- Flag button (users can report inappropriate questions)
- Auto-moderation (AI filters for profanity, personal attacks)

**Tab 8: Comments**

**Public Comment Section**:
- Investors can leave comments about the campaign
- Threaded comments (replies to comments)
- Moderation (admin can hide/delete inappropriate comments)

**Comment Features**:
- Rich text (bold, italic, links)
- Character limit: 1,000 per comment
- "Edit" button (editable for 15 minutes after posting)
- "Delete" button (deletable by author or admin)
- Like button (other users can like comments)
- Reply button (threaded replies, max 3 levels deep)

**Sorting**:
- Sort by: Newest, Oldest, Most Liked

**Spam Prevention**:
- Rate limit: 10 comments per user per day
- CAPTCHA if user posts >5 comments in 1 hour
- Auto-flag comments with excessive links (potential spam)

**Acceptance Criteria**:
- Page load time <2s (all tabs lazy-loaded)
- AI analysis tab loads in <1s (data pre-fetched)
- Document preview opens in <2s
- Q&A response rate >80% (companies respond to 80%+ of questions within 48 hours)
- Comment moderation latency <1 hour (flagged comments reviewed within 1 hour)

---

#### 4.3.3 AI-Powered Recommendations

**Purpose**: Provide personalized campaign recommendations to help investors discover opportunities aligned with their investment preferences and risk profile.

**User Story**: As an investor, I want AI-powered recommendations based on my portfolio and preferences so that I can discover high-quality opportunities without manually browsing hundreds of campaigns.

**Functional Requirements**:

**Recommendation Dashboard** (dedicated page):
- "Recommended for You" section (top of investor homepage)
- Display 6-12 recommended campaigns (card format, similar to browsing page)
- Each recommendation includes:
  - Campaign card (same format as browsing page)
  - "Why recommended?" tooltip (hover/click for explanation)
  - Match score (0-100%, color-coded)
  - "Not Interested" button (remove from recommendations, improve future recommendations)

**Recommendation Algorithm Inputs**:
- **Investment History**: Past investments (industries, funding stages, amounts, outcomes)
- **Portfolio Composition**: Current holdings (diversification needs)
- **Risk Profile**: User-selected risk tolerance (Conservative, Moderate, Aggressive)
- **Investment Preferences** (user-configurable):
  - Preferred regions (multi-select)
  - Preferred industries (multi-select)
  - Preferred asset types (Equity, RWA, both)
  - Minimum AI score threshold (slider, 0-100)
  - Investment amount range ($100-$10,000+)
  - Expected return range (5%-30%+)
- **Behavioral Signals**: Campaigns viewed, watchlist additions, Q&A participation
- **Social Signals** (Phase 2+): Investments by similar investors, trending campaigns

**Recommendation Types**:

1. **Personalized Matches** (primary recommendation type):
   - Based on user's investment preferences and history
   - Example: "FinTech campaigns in Singapore (your preferred region)"

2. **Portfolio Diversification**:
   - Recommend campaigns in industries/regions user has not invested in
   - Example: "Diversify into HealthTech (0% of your portfolio)"

3. **Similar to Your Holdings**:
   - Recommend campaigns similar to user's existing investments
   - Example: "Similar to [Company X] you invested in"

4. **High AI Score**:
   - Recommend top-rated campaigns regardless of preferences
   - Example: "Top-rated campaigns this week (AI Score 90+)"

5. **Closing Soon**:
   - Recommend campaigns ending within 7 days (urgency factor)
   - Example: "Last chance: Ending in 3 days"

6. **Recently Funded Success Stories** (social proof):
   - Recommend campaigns that recently reached funding goals
   - Example: "Just funded: 150% of goal in 30 days"

**Recommendation Explanation** (transparency):
- Each recommendation shows top 3 reasons why it was recommended:
  - Example: "Matches your preference for Singapore FinTech (95% match)"
  - Example: "High AI Score (87/100) - similar to your top holdings"
  - Example: "Diversification opportunity: Real Estate (0% of your portfolio)"

**User Feedback Loop** (improve recommendations over time):
- "Not Interested" button → Remove from recommendations, log reason
- "Why?" button → User can optionally provide feedback
  - Dropdown reasons: "Already invested", "Not my industry", "Risk too high", "Other"
- Track clicks, views, and investments from recommendations (measure recommendation quality)

**Recommendation Refresh**:
- Recommendations update daily (new campaigns added, old campaigns removed)
- Manual refresh button ("Show me new recommendations")
- Email digest (weekly, opt-in): "Top 5 Recommendations for You This Week"

**Filtering Recommendations**:
- Apply filters to recommendations (same filters as browsing page)
- Sort recommendations (AI Score, Match Score, Funding Progress, Closing Soon)

**Onboarding Quiz** (new users):
- 5-question quiz to set initial preferences:
  1. "What regions are you interested in?" (multi-select)
  2. "What industries excite you?" (multi-select)
  3. "What's your risk tolerance?" (Conservative, Moderate, Aggressive)
  4. "How much do you plan to invest per campaign?" ($100-$500, $500-$2K, $2K-$10K, $10K+)
  5. "What's your investment goal?" (Income, Growth, Impact, Diversification)
- Quiz results seed initial recommendation algorithm
- Users can retake quiz anytime (Settings → Investment Preferences)

**No Recommendations Available**:
- If no recommendations match user's preferences:
  - Message: "No recommendations match your current preferences. Try adjusting your filters or [Browse All Campaigns]"
  - Suggest broadening filters (e.g., "Try expanding to more regions or industries")

**A/B Testing** (Phase 2):
- Test different recommendation algorithms (collaborative filtering, content-based, hybrid)
- Measure conversion rate (recommendations → investments)
- Track user satisfaction (thumbs up/down feedback)

**Privacy & Transparency**:
- Clear explanation: "We use your investment history and preferences to recommend campaigns. We never share your data with third parties."
- Opt-out option: "Turn off personalized recommendations" (show top campaigns instead)
- Export preferences: "Download My Recommendation Settings" (GDPR compliance)

**Acceptance Criteria**:
- Recommendation accuracy >70% (user invests or adds to watchlist)
- Recommendation load time <1s
- Daily refresh (new recommendations available every 24 hours)
- Feedback loop latency <5 minutes (dismissed recommendations immediately removed)
- A/B test conversion lift >15% (personalized vs. random recommendations)

---

#### 4.3.4 Investment Flow

**Purpose**: Enable investors to commit funds to campaigns through a seamless, secure, and compliant investment process.

**User Story**: As an investor, I want to invest in campaigns with a simple, secure flow so that I can complete my investment in under 5 minutes.

**Functional Requirements**:

**Entry Points** (multiple ways to start investment):
- "Invest Now" button on campaign detail page (primary CTA)
- "Invest" button on campaign cards (browsing page, recommendations)
- Direct link (shareable investment link for referrals, Phase 2)

**Step 1: Investment Amount Selection**

**Investment Amount Input**:
- Text input field (numeric only, USD)
- Suggested amounts (chips/buttons):
  - Minimum investment (e.g., $100)
  - $250, $500, $1,000, $2,500, $5,000 (common amounts)
  - Maximum investment (if set by company or regulatory limit)
- Custom amount option (text input for any amount)
- Currency display: USDC or USDT (user selects)

**Investment Validation**:
- Minimum investment check (e.g., "Minimum investment is $100")
- Maximum investment check (if applicable, e.g., "Maximum investment is $10,000 per investor")
- Regulatory limit check (country-specific):
  - Thailand: ≤250K THB (~$7K) per investor per project
  - Malaysia: ≤20K MYR per issuer per year
  - Indonesia: ≤5M IDR (~$320) per investor per year
- Available balance check (if wallet/account has insufficient funds, prompt to deposit)

**Investment Calculator** (real-time display):
- Investment amount: $X,XXX
- Platform fee (2%): $XX (deducted from company, not investor)
- Your investment: $X,XXX (no change, investors pay face value)
- Expected shares/tokens: XXX (calculated based on share price)
- Expected ownership: X.XX% (post-money valuation)

**Risk Acknowledgment** (mandatory checkbox):
- "I understand that investing in early-stage companies is high risk and I may lose my entire investment."
- "I have read and understood the campaign's risk disclosures."
- "I confirm I am investing with funds I can afford to lose."

**Step 2: Payment Method Selection**

**Payment Options**:
1. **Stablecoin Wallet** (primary method, lowest friction):
   - Connect wallet (Phantom for Solana)
   - Select stablecoin: USDC or USDT
   - Display wallet balance (e.g., "Balance: 1,234.56 USDC")
   - "Pay with Wallet" button

2. **Credit/Debit Card** (fiat on-ramp via Stripe):
   - Card number, expiry, CVV (PCI-compliant form)
   - Billing address (country, postal code)
   - 3D Secure authentication (if required by bank)
   - Conversion: Fiat → USDC (automatic, real-time exchange rate displayed)
   - Processing fee: 3% (standard Stripe fee, investor pays)
   - "Pay with Card" button

3. **Bank Transfer** (fiat on-ramp via Transak):
   - Select bank (dropdown of supported banks in user's country)
   - Redirect to bank login (secure bank authentication)
   - Authorize transfer (bank's interface)
   - Conversion: Fiat → USDC (automatic)
   - Processing fee: 1.5% (Transak fee, investor pays)
   - Processing time: 1-3 business days (slower than card)

**Payment Processing Flow**:

**For Wallet Payments**:
1. User clicks "Pay with Wallet"
2. Wallet prompt opens (Phantom): "Approve transaction to send [X] USDC to escrow address"
3. User approves transaction in wallet
4. Transaction submitted to Solana blockchain
5. Wait for confirmation (average 400ms finality)
6. Display confirmation message: "Transaction confirmed! Your investment is complete."

**For Card/Bank Payments**:
1. User enters payment details
2. Payment processor (Stripe/Transak) processes payment
3. Fiat converted to USDC (on-ramp)
4. USDC sent to user's platform wallet (auto-created if first investment)
5. USDC automatically transferred to escrow (same flow as wallet payment)
6. Display confirmation message: "Payment processed! Your investment is complete."

**Step 3: Investment Confirmation**

**Confirmation Screen**:
- Success message: "Congratulations! You've successfully invested in [Company Name]"
- Investment summary:
  - Campaign name
  - Investment amount: $X,XXX USDC
  - Shares/tokens received: XXX
  - Ownership percentage: X.XX%
  - Transaction ID (blockchain hash, clickable link to explorer)
  - Transaction date and time
- Next steps:
  - "View Your Portfolio" button (go to portfolio dashboard)
  - "View Campaign" button (return to campaign page)
  - "Share Your Investment" button (social sharing, optional)

**Email Confirmation**:
- Send email to investor with investment summary
- Include PDF receipt (downloadable, branded)
- Email content:
  - Investment details (same as confirmation screen)
  - Next steps (portfolio dashboard link)
  - Support contact (if questions)

**Smart Contract Interaction** (backend process):
- Transfer USDC from investor wallet to escrow smart contract
- Mint shares/tokens to investor's wallet (locked for 12 months)
- Update campaign funding total (on-chain state)
- Update investor's portfolio (database record)
- Log transaction in audit log (immutable record)

**Error Handling**:

**Payment Failures**:
- Insufficient wallet balance: "Insufficient USDC balance. You have [X] USDC, but need [Y] USDC. [Deposit Funds]"
- Card declined: "Card payment failed. Please check your card details or try a different payment method."
- Transaction failed (blockchain): "Transaction failed. Please try again. [Retry Payment]"
- Escrow full (campaign overfunding limit reached): "This campaign has reached its funding limit. You cannot invest at this time."

**Network Issues**:
- Slow transaction: "Transaction pending... This may take a few minutes. [View Transaction Status]"
- Blockchain congestion: "Network is busy. Your transaction may take longer than usual. [Check Status]"
- Timeout: "Transaction timed out. Please check your wallet for pending transactions. [Support]"

**Validation Errors**:
- Amount below minimum: "Investment amount must be at least $100."
- Amount above maximum: "Investment amount exceeds the maximum allowed ($10,000)."
- Regulatory limit exceeded: "Investment exceeds your country's regulatory limit. Maximum allowed: $7,000."
- Campaign inactive: "This campaign is no longer accepting investments."

**Security Features**:

**Anti-Fraud Measures**:
- CAPTCHA (if suspicious activity detected)
- Rate limiting (max 5 investment attempts per hour)
- Wallet verification (confirm wallet address before transaction)
- Email confirmation required (for large investments >$5,000)
- 2FA verification (if user has 2FA enabled)

**Transaction Encryption**:
- All payment data encrypted (TLS 1.3)
- PCI-DSS compliant (for card payments)
- Wallet signatures verified (Solana Ed25519)

**Audit Logging**:
- Log all investment attempts (successful, failed, abandoned)
- Track user journey (entry point → amount selection → payment → confirmation)
- Record IP address, device, browser (fraud detection)

**Investor Protection**:

**Cooling-Off Period** (regulatory requirement in some countries):
- Singapore: 7-day cooling-off period (investor can cancel within 7 days)
- Display notice: "You have 7 days to cancel this investment. [Learn More]"
- "Cancel Investment" button (available for 7 days post-investment)
- Refund process: Automatic USDC refund to wallet (minus gas fees)

**Refund Policy** (if campaign fails to reach goal):
- Automatic refund (USDC returned to investor's wallet)
- Email notification: "Campaign did not reach its funding goal. Your investment has been refunded."
- Refund timeline: Within 48 hours of campaign end date
- No fees deducted (investors receive 100% refund)

**Performance Requirements**:
- Investment flow completion time: <5 minutes (target: <3 minutes)
- Wallet transaction confirmation: <5s (Solana finality)
- Card payment processing: <30s (Stripe)
- Bank transfer processing: 1-3 business days
- Confirmation email delivery: <1 minute

**Acceptance Criteria**:
- Investment completion rate >80% (users who start flow complete it)
- Payment success rate >95% (successful transactions / attempted transactions)
- Wallet transaction finality <5s (p95)
- Error handling coverage 100% (all error scenarios handled gracefully)
- Fraud detection false positive rate <1% (legitimate transactions incorrectly flagged)
- Regulatory compliance 100% (investment limits enforced correctly)

---

#### 4.3.5 Portfolio Dashboard

**Purpose**: Provide investors with a comprehensive view of their holdings, performance, distributions, and portfolio analytics.

**User Story**: As an investor, I want to track my portfolio performance and see all my investments in one place so that I can monitor my returns and make informed decisions.

**Functional Requirements**:

**Portfolio Overview** (homepage for logged-in investors):

**Key Metrics** (top of page, card grid):
1. **Total Portfolio Value**: $XX,XXX.XX
   - Current value of all holdings (marked to latest valuation)
   - Change indicator (+/- $XXX, +/- X.X% since last update)
   - Color-coded (green if positive, red if negative)

2. **Total Invested**: $XX,XXX.XX
   - Sum of all investments made (principal amount)
   - Number of campaigns invested in (e.g., "12 campaigns")

3. **Total Returns**: +$X,XXX.XX (+XX.XX%)
   - Unrealized gains/losses (paper returns)
   - Realized gains/losses (distributions received)
   - Combined return percentage

4. **Distributions Received**: $X,XXX.XX
   - Total distributions/dividends received to date
   - Next distribution date (if any scheduled)

**Portfolio Allocation Charts**:

**By Industry** (pie chart):
- Technology: XX%
- FinTech: XX%
- HealthTech: XX%
- Real Estate: XX%
- Other: XX%

**By Region** (pie chart):
- Singapore: XX%
- Hong Kong: XX%
- UAE: XX%
- Other: XX%

**By Asset Type** (bar chart):
- Equity: XX% ($X,XXX)
- RWA: XX% ($X,XXX)

**By Stage** (bar chart):
- Active Campaigns (still raising): XX%
- Funded Campaigns (fully funded): XX%
- Performing (generating returns): XX%

**Holdings Table** (detailed view):

**Table Columns**:
1. **Company Name** (logo + name, clickable link to campaign page)
2. **Investment Date** (YYYY-MM-DD)
3. **Amount Invested** ($X,XXX USDC)
4. **Shares/Tokens** (XXX shares, ownership percentage)
5. **Current Value** ($X,XXX, marked to latest valuation)
6. **Return** (+/- $XXX, +/- XX.XX%, color-coded)
7. **Status** (badge: Active, Funded, Performing, Closed)
8. **Lock-up Status** (badge: Locked, Unlocked in X days, Unlocked)
9. **Actions** (dropdown: View Campaign, View Documents, View Distributions)

**Table Features**:
- Sort by: Date, Amount, Return (%, $), Status
- Filter by: Status, Industry, Region, Lock-up Status
- Search (by company name)
- Pagination (20 holdings per page)
- Export to CSV/Excel (all holdings)

**Performance Trends** (line chart):
- X-axis: Time (daily, weekly, monthly, all-time)
- Y-axis: Portfolio value ($)
- Two lines:
  - Total Portfolio Value (current value of holdings)
  - Total Invested (cumulative investments over time)
- Annotations: Investment dates (markers), distribution dates (markers)

**Performance Filters**:
- Time period: 1W, 1M, 3M, 6M, 1Y, All Time, Custom (date range picker)
- Display type: Absolute ($), Relative (%), Both

**Portfolio Health Score** (AI-powered):
- Score (0-100, color-coded)
- Components:
  - Diversification: X/100 (industry, region, asset type diversity)
  - Risk Level: Low/Medium/High (based on campaign AI scores)
  - Performance: X/100 (vs. benchmark, e.g., S&P 500, MSCI Asia)
  - Liquidity: X/100 (% of holdings with lock-up expired)
- Recommendations:
  - "Consider diversifying into HealthTech (0% of portfolio)"
  - "3 holdings will unlock in the next 30 days (worth $X,XXX)"
  - "Your portfolio is underperforming the benchmark by 5%. Consider rebalancing."

**Investment Activity Timeline**:
- Chronological feed of all portfolio events:
  - Investments made (date, campaign, amount)
  - Distributions received (date, amount, campaign)
  - Valuations updated (date, new value, change)
  - Lock-up expiries (date, shares unlocked)
  - Milestones achieved (by companies in portfolio)
- Filter by: Event type, Date range, Campaign
- Export to PDF (investor report)

**Watchlist Integration**:
- "Watchlist" tab (separate from Holdings)
- List of campaigns added to watchlist (same format as Holdings table)
- Columns: Company Name, AI Score, Funding Progress, Days Remaining, Added Date
- Actions: Invest, Remove from Watchlist
- Email alerts (opt-in):
  - Watchlist campaign closing soon (7 days remaining)
  - Watchlist campaign reached funding goal
  - Watchlist campaign AI score changed significantly (±10 points)

**Portfolio Analytics** (advanced metrics, Phase 2):

**Risk Metrics**:
- Portfolio beta (vs. benchmark)
- Standard deviation (volatility)
- Sharpe ratio (risk-adjusted returns)
- Max drawdown (largest peak-to-trough decline)

**Performance Metrics**:
- IRR (Internal Rate of Return)
- MOIC (Multiple on Invested Capital)
- TWR (Time-Weighted Return)
- MWR (Money-Weighted Return)

**Comparison to Benchmarks**:
- S&P 500 (US equities)
- MSCI Asia (Asian equities)
- Platform average (all investors)
- Top 10% investors (aspirational benchmark)

**Mobile Optimization**:
- Responsive design (perfect display on mobile devices)
- Swipeable cards (for portfolio holdings)
- Collapsible sections (hide/show charts, tables)
- Pull-to-refresh (update portfolio data)

**Accessibility**:
- Screen reader support (all charts have text descriptions)
- Keyboard navigation (tab through holdings table)
- High contrast mode (for visually impaired users)
- Font size adjustment (user preference)

**Error Handling**:
- No holdings: "You haven't invested yet. [Browse Campaigns] to get started."
- Data sync error: "Unable to load portfolio data. [Retry] or check your connection."
- Valuation not available: "Valuation pending. Last updated: [date]"

**Acceptance Criteria**:
- Portfolio dashboard load time <2s (desktop), <3s (mobile)
- Data refresh latency <5s (pull-to-refresh)
- Chart rendering time <1s
- Export success rate >99% (CSV/Excel/PDF exports)
- Mobile responsiveness (perfect display on 360px width)
- Accessibility: WCAG 2.1 AA compliant

---

#### 4.3.6 Transaction History

**Purpose**: Provide investors with a complete, auditable record of all financial transactions.

**User Story**: As an investor, I want to see all my transactions (investments, distributions, refunds) so that I can track my cash flows and reconcile my records.

**Functional Requirements**:

**Transaction List** (table format):

**Table Columns**:
1. **Date & Time** (YYYY-MM-DD HH:MM:SS, sortable)
2. **Transaction Type** (badge: Investment, Distribution, Refund, Withdrawal)
3. **Campaign/Company** (clickable link)
4. **Amount** ($X,XXX USDC, color-coded: green for inflows, red for outflows)
5. **Status** (badge: Completed, Pending, Failed)
6. **Transaction ID** (blockchain hash, clickable link to Solana Explorer)
7. **Actions** (dropdown: View Receipt, Download PDF, View on Blockchain)

**Transaction Types**:

1. **Investment**:
   - Outflow (debit): -$X,XXX USDC
   - Shares/tokens received: XXX shares
   - Campaign linked
   - Investment date

2. **Distribution**:
   - Inflow (credit): +$X,XXX USDC
   - Campaign linked
   - Distribution date
   - Distribution type (Dividend, Profit Share, Interest)

3. **Refund**:
   - Inflow (credit): +$X,XXX USDC
   - Reason: Campaign did not reach funding goal
   - Original investment date
   - Refund date

4. **Withdrawal** (Phase 2, secondary market):
   - Outflow (debit): Shares transferred
   - Inflow (credit): +$X,XXX USDC
   - Buyer information (anonymized)
   - Sale price and gain/loss

**Filtering & Search**:
- **Date Range**: Date picker (from/to), presets (Last 7 days, Last 30 days, Last 90 days, This Year, All Time)
- **Transaction Type**: Multi-select (Investment, Distribution, Refund, Withdrawal)
- **Campaign**: Dropdown (all campaigns user invested in)
- **Status**: Checkboxes (Completed, Pending, Failed)
- **Amount Range**: Min/max amount slider
- **Search**: Transaction ID, campaign name

**Sorting**:
- Sort by: Date (newest first, oldest first), Amount (high to low, low to high), Type

**Pagination**:
- 25 transactions per page
- Infinite scroll option (user preference)

**Transaction Details** (expandable row or modal):
- Full transaction ID (blockchain hash)
- From address (wallet address)
- To address (escrow or distribution wallet)
- Gas fees (if applicable)
- Network confirmation time
- Blockchain explorer link (Solana Explorer, SolScan)
- Receipt download (PDF)

**Export Options**:
- **CSV Export**: All transaction data (for spreadsheet analysis)
- **Excel Export**: Formatted workbook with charts
- **PDF Report**: Branded investor report (for tax filing)
  - Include: All transactions for selected date range
  - Include: Summary totals (total invested, total distributions, net cash flow)
  - Include: Tax information (capital gains, dividend income, if applicable)

**Tax Reporting** (Phase 2, jurisdiction-specific):
- **Singapore**: Exempt (capital gains not taxed)
- **Hong Kong**: Exempt (no capital gains tax)
- **UAE**: Exempt (no personal income tax)
- **Thailand**: 15% capital gains tax (platform generates tax forms)
- **Malaysia**: Tax-free for individuals (platform confirms)
- **Indonesia**: 0.1% transaction tax (platform auto-calculates)

**Transaction Notifications**:
- Email notification for every transaction (opt-in)
- In-app notification (bell icon)
- Push notification (mobile app, Phase 2)

**Transaction Receipt** (PDF download):
- Transaction date and time
- Transaction type
- Campaign name
- Amount (USDC)
- Shares/tokens received (for investments)
- Transaction ID (blockchain hash)
- Platform branding and contact info

**Performance Requirements**:
- Transaction list load time <2s (100 transactions)
- Export generation time <10s (CSV), <20s (PDF)
- Search results <500ms

**Acceptance Criteria**:
- Transaction accuracy 100% (matches blockchain records exactly)
- Export success rate >99%
- Tax calculation accuracy 100% (for supported jurisdictions)

---

#### 4.3.7 Distribution Tracking

**Purpose**: Enable investors to track profit distributions, dividends, and payouts from their investments.

**User Story**: As an investor, I want to see when and how much I've been paid by companies I've invested in so that I can track my investment income.

**Functional Requirements**:

**Distribution Dashboard**:

**Summary Metrics** (top of page):
1. **Total Distributions Received**: $XX,XXX.XX (lifetime)
2. **Distributions This Year**: $X,XXX.XX (YTD)
3. **Distributions Last Quarter**: $X,XXX.XX (Q1, Q2, Q3, Q4)
4. **Average Distribution Yield**: X.X% (annual, across all holdings)

**Upcoming Distributions** (calendar view):
- List of scheduled distributions (next 90 days)
- Each entry shows:
  - Company name
  - Distribution date (YYYY-MM-DD)
  - Estimated amount ($X,XXX USDC, company-provided estimate)
  - Distribution type (Dividend, Profit Share, Interest)
  - "Add to Calendar" button (iCal, Google Calendar)

**Distribution History** (table format):

**Table Columns**:
1. **Date** (YYYY-MM-DD, sortable)
2. **Company Name** (clickable link to campaign page)
3. **Distribution Type** (badge: Dividend, Profit Share, Interest, Redemption)
4. **Amount** ($X,XXX USDC)
5. **Payment Method** (Stablecoin, Bank Transfer - Phase 2)
6. **Transaction ID** (blockchain hash, clickable link)
7. **Status** (badge: Paid, Pending, Processing)

**Distribution Types**:

1. **Dividend**: Profit distribution from company earnings
2. **Profit Share**: Revenue-sharing agreement (for RWA investments)
3. **Interest**: Fixed-income payments (for debt instruments, Phase 2)
4. **Redemption**: Principal repayment (loan maturity, exit event)

**Filtering**:
- **Date Range**: Presets (Last Quarter, This Year, All Time)
- **Company**: Multi-select dropdown
- **Distribution Type**: Checkboxes
- **Status**: Completed, Pending, Failed

**Distribution Trends** (line chart):
- X-axis: Time (quarterly, annually)
- Y-axis: Distribution amount ($)
- Stacked area chart (by company, color-coded)
- Show cumulative distributions over time

**Distribution Notifications**:
- Email notification 7 days before distribution date (reminder)
- Email notification when distribution is paid (confirmation)
- In-app notification (bell icon)

**Distribution Details** (per holding):
- Navigate from portfolio dashboard to distribution history for specific holding
- Shows only distributions from that campaign
- Compare to projections (company-provided estimates vs. actual payouts)

**Tax Information** (Phase 2):
- Annual distribution summary (for tax filing)
- Breakdown by distribution type (dividends, interest, capital gains)
- Downloadable tax forms (jurisdiction-specific)

**Acceptance Criteria**:
- Distribution accuracy 100% (matches on-chain payouts)
- Notification delivery <1 hour (before and after distribution)
- Distribution dashboard load time <2s

---

#### 4.3.8 Watchlist

**Purpose**: Enable investors to save campaigns they're interested in for later review.

**User Story**: As an investor, I want to save campaigns I'm interested in so that I can review them later and track their progress.

**Functional Requirements**:

**Adding to Watchlist**:
- "Add to Watchlist" button (heart icon, clickable)
- Available on: Campaign cards, campaign detail page
- Visual feedback: Heart icon fills (solid heart when added)
- Confirmation toast: "Added to Watchlist"
- One-click remove: Click filled heart to remove

**Watchlist Page** (dedicated page):

**Watchlist Metrics** (top of page):
- Total campaigns watched: X
- Campaigns closing soon: X (within 7 days)
- Campaigns reached goal: X (fully funded)

**Watchlist Table**:

**Table Columns**:
1. **Company Name** (logo + name, clickable link)
2. **AI Score** (0-100, color-coded)
3. **Funding Progress** (progress bar + percentage)
4. **Amount Raised / Target** ($X,XXX / $XXX,XXX)
5. **Days Remaining** (countdown)
6. **Status** (badge: Active, Closing Soon, Funded)
7. **Date Added** (when user added to watchlist)
8. **Actions**: Invest Now, Remove from Watchlist

**Sorting & Filtering**:
- Sort by: AI Score, Funding Progress, Days Remaining, Date Added
- Filter by: Status, Industry, Region, AI Score Range
- Search: Company name, keywords

**Watchlist Alerts** (email notifications, opt-in):
- Campaign closing soon (7 days remaining)
- Campaign reached 50% funding goal
- Campaign reached 100% funding goal (fully funded)
- Campaign AI score changed significantly (±10 points)
- Campaign posted new update

**Alert Preferences** (user-configurable):
- Enable/disable alerts per campaign (individual control)
- Global alert preferences (enable/disable all watchlist alerts)
- Alert frequency: Immediate, Daily Digest, Weekly Digest

**Watchlist Limits**:
- Max 50 campaigns per user (prevent spam)
- Warning at 45 campaigns: "You're approaching the watchlist limit (45/50)"
- When full: "Your watchlist is full. Remove campaigns to add more."

**Empty Watchlist**:
- Message: "Your watchlist is empty. [Browse Campaigns] to find opportunities."
- Suggested campaigns (AI-powered recommendations)

**Acceptance Criteria**:
- Watchlist add/remove latency <200ms
- Alert delivery within 1 hour of trigger event
- Watchlist sync across devices (same account)

---

#### 4.3.9 Secondary Market Trading (Phase 2+)

**Purpose**: Enable investors to trade locked tokens before lock-up expiry through a peer-to-peer marketplace.

**User Story**: As an investor, I want to sell my locked tokens to other investors so that I can exit my position before the lock-up period ends (with appropriate discounts).

**Functional Requirements**:

**Market Overview**:
- List of available tokens for sale (secondary market listings)
- Each listing shows:
  - Company name
  - Number of shares/tokens for sale
  - Original purchase price
  - Current asking price (may be discounted)
  - Discount percentage (e.g., "-20% from original price")
  - Lock-up expiry date
  - Seller rating (trust score, Phase 2+)

**Listing Your Tokens** (seller flow):
1. Select holding from portfolio
2. Enter number of shares to sell
3. Set asking price (with suggested discount based on time remaining)
4. Review listing (preview)
5. Confirm listing (pay listing fee: 0.5%)
6. Listing goes live (visible to all investors)

**Buying Tokens** (buyer flow):
1. Browse secondary market listings
2. View listing details (company info, lock-up terms, seller info)
3. Click "Buy Now" or "Make Offer" (negotiation, Phase 3)
4. Complete payment (USDC via wallet)
5. Tokens transferred to buyer's wallet (on-chain)
6. Seller receives payment (minus 0.5% platform fee)

**Transaction Fees**:
- Buyer fee: 0.25% (of transaction value)
- Seller fee: 0.25% (of transaction value)
- Total platform fee: 0.5%

**Compliance & Restrictions**:
- KYC required (both buyer and seller)
- Transfer restrictions enforced (whitelist-based)
- Lock-up terms transfer to buyer (buyer inherits remaining lock-up period)
- Securities law compliance (no public solicitation, accredited investor requirements in some jurisdictions)

**Acceptance Criteria** (Phase 2):
- Secondary market launch in Q3 2026 (after primary market stable)
- Trading volume target: 10% of total platform GMV
- Average discount: 15-25% (function of time remaining in lock-up)

---

**Section 4.3 Summary**:

Section 4.3 covers all investor-facing features:
- 4.3.1: Campaign Browsing & Discovery (filtering, search, sorting)
- 4.3.2: Campaign Detail Page (8 tabs: Overview, Financials, Team, AI Analysis, Documents, Updates, Q&A, Comments)
- 4.3.3: AI-Powered Recommendations (personalized matches, diversification suggestions, feedback loop)
- 4.3.4: Investment Flow (3-step flow: amount selection, payment, confirmation)
- 4.3.5: Portfolio Dashboard (holdings, performance, analytics, health score)
- 4.3.6: Transaction History (all transactions, filtering, export, tax reporting)
- 4.3.7: Distribution Tracking (upcoming distributions, history, trends, notifications)
- 4.3.8: Watchlist (save campaigns, alerts, tracking)
- 4.3.9: Secondary Market Trading (Phase 2+, peer-to-peer token sales)

**Total lines added**: ~800 lines (4.3.1 to 4.3.9)
**Estimated implementation time**: 8-12 weeks (for MVP, Phase 1 features only)

---

### 4.4 AI Investment Manager

This section defines the AI-powered investment analysis system that evaluates campaigns, generates investment scores, and provides personalized recommendations.

**Strategic Context**: The AI Investment Manager is Elevate Finance's key differentiator. It democratizes institutional-grade investment analysis for retail investors while maintaining transparency and human oversight.

---

#### 4.4.1 Data Ingestion Pipeline

**Purpose**: Systematically collect, validate, and prepare data from multiple sources for AI analysis.

**User Story**: As the AI system, I need to ingest diverse data sources so that I can perform comprehensive investment analysis across financial, social, and qualitative dimensions.

**Functional Requirements**:

**Data Sources & Collection Frequency**:

1. **Financial Data** (collected once per campaign submission, updated quarterly):
   - Balance Sheet (most recent + 2 prior years)
   - Profit & Loss Statement (most recent + 2 prior years)
   - Cash Flow Statement (most recent + 2 prior years)
   - Financial projections (3-year forward-looking)
   - Unit economics (CAC, LTV, churn rate)
   - Source: Company-uploaded documents (PDF, Excel)
   - Extraction method: OCR (Tesseract) + structured parsing

2. **Social Sentiment Data** (collected daily):
   - Twitter mentions, replies, likes (Twitter API v2)
   - LinkedIn posts and engagement (LinkedIn API)
   - News articles mentioning company (News API, Google News)
   - Reddit discussions (Reddit API)
   - Source: Public APIs, web scraping (Puppeteer)
   - Storage: Time-series data (7-day rolling window)

3. **Founder/Team Data** (collected once per campaign submission):
   - LinkedIn profiles (education, experience, network size)
   - Previous ventures (exits, funding raised)
   - GitHub activity (for tech founders: commits, repos, stars)
   - Patent filings (Google Patents API)
   - Media mentions and speaking engagements
   - Source: LinkedIn API, Crunchbase API, GitHub API
   - Storage: Structured JSON in NeonDB

4. **Market Data** (updated weekly):
   - Industry trends (market size, growth rate)
   - Competitor analysis (funding, valuation, traction)
   - Regulatory changes affecting industry
   - Macroeconomic indicators (GDP growth, interest rates)
   - Source: Crunchbase API, PitchBook API (Phase 2), web scraping
   - Storage: Time-series data (historical + current)

5. **Platform Behavior Data** (real-time):
   - Campaign views, time spent, bounce rate
   - Investor engagement (Q&A, comments, watchlist additions)
   - Investment velocity (funding progress over time)
   - Source: Internal analytics (PostHog, Mixpanel)
   - Storage: Event stream (Kafka/SQS)

**Data Pipeline Architecture**:

```
Data Sources → ETL Pipeline → Data Warehouse → Feature Store → AI Models
```

**ETL (Extract, Transform, Load) Process**:

1. **Extract**:
   - Scheduled jobs (cron): Daily for social data, weekly for market data
   - Event-driven: Campaign submission triggers financial data extraction
   - API integrations: REST APIs with rate limiting (respect quotas)
   - Fallback: Manual upload if API unavailable

2. **Transform**:
   - Data cleaning: Remove duplicates, fix encoding issues, normalize formats
   - Data validation: Schema validation (Zod), range checks, outlier detection
   - Feature engineering: Calculate derived metrics (e.g., revenue growth rate, burn rate)
   - Anonymization: Remove PII before storing in AI training datasets (GDPR compliance)

3. **Load**:
   - Primary storage: NeonDB (structured data)
   - Time-series storage: InfluxDB or TimescaleDB (Phase 2, for social sentiment over time)
   - Feature store: Redis or Feast (Phase 2, for real-time features)
   - Blob storage: S3/R2 (raw documents, images)

**Data Quality Checks**:

- **Completeness**: All required fields present (e.g., financial statements must have revenue, expenses, profit/loss)
- **Accuracy**: Cross-check financials against external sources (e.g., company registry)
- **Consistency**: Ensure data matches across sources (e.g., LinkedIn employee count vs. company-reported)
- **Timeliness**: Flag stale data (e.g., financials older than 12 months)
- **Validity**: Range checks (e.g., revenue growth rate between -100% and +10,000%)

**Error Handling**:

- **API failures**: Retry with exponential backoff (3 attempts), log failure, alert admin
- **Data parsing errors**: Log error, mark data as "incomplete", request manual review
- **Missing data**: Use imputation (industry averages) or flag for human review
- **Rate limiting**: Queue requests, spread over time, use cached data if available

**Data Refresh Strategy**:

- **Financial data**: Manual trigger when company uploads new financials
- **Social sentiment**: Daily batch job (run at 2 AM UTC)
- **Founder data**: Monthly refresh (detect job changes, new ventures)
- **Market data**: Weekly refresh (Monday 6 AM UTC)
- **Platform behavior**: Real-time streaming (event-driven)

**Performance Requirements**:

- Data ingestion latency: <5 minutes (from API call to database storage)
- ETL job completion time: <30 minutes (for daily social sentiment batch)
- Data freshness: Social data <24 hours old, financial data <3 months old
- Storage efficiency: Compress historical data (gzip), archive data older than 3 years

**Acceptance Criteria**:

- Data ingestion success rate >95% (successful API calls / total attempts)
- Data quality score >90% (completeness + accuracy + consistency)
- Zero PII leaks (all data anonymized before training)
- Audit trail 100% (every data change logged with timestamp and source)

---

#### 4.4.2 Financial Analysis Module

**Purpose**: Analyze company financials to assess financial health, growth potential, and sustainability.

**User Story**: As the AI system, I need to analyze financial statements so that I can evaluate a company's revenue model, profitability, and runway.

**Functional Requirements**:

**Key Financial Metrics Calculated**:

1. **Revenue Metrics**:
   - Total revenue (last 12 months)
   - Revenue growth rate (YoY %): `(Revenue_current - Revenue_prior) / Revenue_prior * 100`
   - Revenue per employee: `Total_revenue / Number_of_employees`
   - Revenue concentration: % from top 3 customers (risk metric)

2. **Profitability Metrics**:
   - Gross profit margin: `(Revenue - COGS) / Revenue * 100`
   - Operating profit margin: `Operating_income / Revenue * 100`
   - Net profit margin: `Net_income / Revenue * 100`
   - EBITDA margin: `EBITDA / Revenue * 100`

3. **Burn Rate & Runway** (for pre-revenue or unprofitable companies):
   - Monthly burn rate: `(Cash_beginning - Cash_ending) / Months`
   - Runway (months): `Current_cash_balance / Monthly_burn_rate`
   - Cash efficiency ratio: `Revenue / Cash_burned` (measures capital efficiency)

4. **Unit Economics**:
   - Customer Acquisition Cost (CAC): `Sales_and_marketing_expenses / New_customers`
   - Lifetime Value (LTV): `ARPU * Gross_margin / Churn_rate`
   - LTV:CAC ratio: `LTV / CAC` (target >3 for healthy business)
   - Payback period (months): `CAC / (ARPU * Gross_margin)`

5. **Balance Sheet Strength**:
   - Current ratio: `Current_assets / Current_liabilities` (liquidity measure)
   - Debt-to-equity ratio: `Total_debt / Total_equity` (leverage measure)
   - Quick ratio: `(Current_assets - Inventory) / Current_liabilities`

6. **Growth Efficiency**:
   - Rule of 40: `Revenue_growth_rate + Profit_margin` (target >40 for SaaS)
   - Burn multiple: `Net_burn / Net_new_ARR` (capital efficiency, target <1.5)
   - Magic number: `Net_new_ARR / Sales_and_marketing_spend` (GTM efficiency, target >0.75)

**Analysis Algorithms**:

**1. Financial Health Score (0-100)**:

```
Financial_health = 0.25 * Revenue_score +
                   0.25 * Profitability_score +
                   0.20 * Liquidity_score +
                   0.15 * Growth_efficiency_score +
                   0.15 * Balance_sheet_score
```

Each component scored 0-100 based on industry benchmarks.

**2. Red Flag Detection**:

Automatically flag campaigns with:
- Negative gross margin (unsustainable unit economics)
- Runway <6 months (imminent cash crunch)
- Revenue decline >20% YoY (business deterioration)
- Customer concentration >50% (single customer risk)
- Debt-to-equity ratio >3 (over-leveraged)
- LTV:CAC ratio <1 (losing money on each customer)

**3. Industry Benchmarking**:

Compare company metrics to industry averages:
- FinTech: Avg revenue growth 80%, gross margin 70%, LTV:CAC 4.5
- SaaS: Avg revenue growth 50%, gross margin 75%, Rule of 40 = 45
- E-commerce: Avg revenue growth 40%, gross margin 30%, CAC payback 12 months
- Manufacturing: Avg revenue growth 15%, gross margin 35%, current ratio 1.8

Source: Public datasets (Crunchbase, SaaS Capital Index), manually curated by industry

**4. Trend Analysis**:

Analyze financial trends over time:
- Improving: Revenue growth accelerating, margins expanding, burn rate decreasing
- Stable: Consistent performance quarter-over-quarter
- Declining: Revenue growth decelerating, margins compressing, burn rate increasing

**Explainability Features**:

For each financial score, provide:
- Top 3 positive factors (e.g., "Strong revenue growth (127% YoY)")
- Top 3 risk factors (e.g., "High burn rate ($150K/month, runway 8 months)")
- Industry comparison (e.g., "Revenue growth above industry average (127% vs. 80%)")
- Visual charts: Revenue trend, profitability trend, burn rate over time

**Error Handling**:

- Missing financial data: Use industry averages, flag as "incomplete analysis"
- Inconsistent data: Flag for manual review (e.g., revenue in P&L doesn't match cash flow)
- Outliers: Cap extreme values (e.g., revenue growth >1000% likely data error)

**Acceptance Criteria**:

- Financial analysis completion rate >95% (for campaigns with financials)
- Calculation accuracy 100% (verified against manual calculations)
- Benchmark data freshness <3 months (industry averages updated quarterly)
- Explainability: Every score backed by at least 3 factors

---

#### 4.4.3 Sentiment Analysis Module

**Purpose**: Gauge public perception and social proof through sentiment analysis of online conversations.

**User Story**: As the AI system, I need to analyze social media and news mentions so that I can understand public perception and detect early warning signs.

**Functional Requirements**:

**Sentiment Data Sources**:

1. **Twitter** (X):
   - Company mentions, replies, retweets
   - Founder's personal tweets and engagement
   - Hashtag tracking (e.g., #CompanyName, #Product)
   - Volume: Last 30 days of tweets

2. **LinkedIn**:
   - Company page posts and engagement (likes, comments, shares)
   - Employee posts mentioning company
   - Follower growth rate
   - Volume: Last 90 days of posts

3. **News Articles**:
   - Media mentions (TechCrunch, Bloomberg, local press)
   - Press releases
   - Industry publications
   - Volume: Last 12 months of articles

4. **Reddit**:
   - Relevant subreddit discussions (r/startups, r/investing, industry-specific)
   - Upvotes, downvotes, comment sentiment
   - Volume: Last 30 days of posts/comments

**Sentiment Analysis Techniques**:

**1. NLP Models**:

- **BERT-based model** (fine-tuned on financial news):
  - Input: Text (tweet, article, Reddit comment)
  - Output: Sentiment score (-1 to +1: negative, neutral, positive)
  - Confidence score (0-1)

- **FinBERT** (specialized for financial sentiment):
  - Better at detecting nuanced financial language (e.g., "bearish", "bullish")
  - Higher accuracy for news articles

**2. Sentiment Scoring**:

```
Sentiment_score = (Positive_mentions - Negative_mentions) / Total_mentions

Weighted_sentiment = Σ(Sentiment_i * Weight_i)
  where Weight_i = Source_credibility * Engagement_score
```

Source credibility:
- Tier 1 media (Bloomberg, Reuters): Weight 10
- Tier 2 media (TechCrunch, VentureBeat): Weight 5
- Social media (Twitter, LinkedIn, Reddit): Weight 1

Engagement score:
- Twitter: Likes + Retweets + Replies
- LinkedIn: Reactions + Comments + Shares
- Reddit: Upvotes - Downvotes

**3. Trend Detection**:

- Momentum: Is sentiment improving or declining?
  - Calculate 7-day moving average of sentiment
  - Compare to 30-day moving average
  - Trend = "Improving" if 7-day MA > 30-day MA

- Viral indicators:
  - Sudden spike in mentions (>3x average)
  - High engagement rate (>10% of followers engaging)
  - Influencer mentions (accounts with >10K followers)

**4. Topic Modeling**:

Extract key themes from conversations:
- Product features (e.g., "AI-powered", "user-friendly")
- Concerns (e.g., "privacy", "expensive", "buggy")
- Competitive mentions (e.g., "better than X", "worse than Y")
- Techniques: LDA (Latent Dirichlet Allocation), BERTopic

**Sentiment Score Components**:

1. **Overall Sentiment** (0-100):
   - 0-30: Overwhelmingly negative
   - 31-50: Mostly negative
   - 51-70: Mixed or neutral
   - 71-90: Mostly positive
   - 91-100: Overwhelmingly positive

2. **Mention Volume** (relative to industry):
   - Low: <10 mentions/month
   - Medium: 10-100 mentions/month
   - High: >100 mentions/month

3. **Sentiment Momentum**:
   - Improving: +10 points in last 30 days
   - Stable: ±5 points
   - Declining: -10 points in last 30 days

**Red Flag Detection**:

Automatically flag campaigns with:
- Sentiment score <30 (overwhelmingly negative)
- Recent crisis: Sentiment drop >20 points in 7 days
- Controversy: High-volume negative mentions (>50 negative mentions/week)
- Fraud indicators: Keywords like "scam", "fraud", "ponzi" in high-engagement posts

**Explainability Features**:

For each sentiment score, provide:
- Sample positive mentions (top 3 most-liked tweets/posts)
- Sample negative mentions (top 3 most-engaged criticisms)
- Topic breakdown (e.g., "60% of mentions praise product, 30% complain about pricing")
- Sentiment trend chart (30-day rolling sentiment)

**Limitations & Disclaimers**:

- Sentiment analysis is indicative, not definitive (e.g., bots can manipulate social media)
- Low mention volume = unreliable sentiment (flag as "insufficient data")
- Sarcasm and nuance may be misclassified (confidence score reflects this)

**Acceptance Criteria**:

- Sentiment analysis accuracy >75% (validated against human-labeled test set)
- Processing latency <5 seconds per campaign
- False positive rate <10% (flagging legitimate companies as negative)
- Data coverage: >80% of campaigns have social data (rest flagged as "no data")

---

#### 4.4.4 Founder/Team Analysis Module

**Purpose**: Evaluate the quality, experience, and track record of founders and key team members.

**User Story**: As the AI system, I need to analyze founder backgrounds and team composition so that I can assess the team's ability to execute their business plan.

**Functional Requirements**:

**Data Points Collected** (per founder/key team member):

1. **Educational Background**:
   - University attended (Tier 1, Tier 2, Other)
   - Degree level (PhD, Master's, Bachelor's, None)
   - Field of study (relevant to industry or not)
   - Academic achievements (honors, publications)

2. **Work Experience**:
   - Years of experience (total)
   - Years in relevant industry
   - Previous roles (founder, executive, manager, IC)
   - Companies worked at (FAANG, unicorn, startup, corporate)
   - Tenure at each company (job-hopping indicator)

3. **Entrepreneurial Track Record**:
   - Number of previous ventures
   - Outcomes: Successful exit (acquisition, IPO), Failed (shut down), Ongoing
   - Funding raised in previous ventures
   - Time to exit (speed of execution)

4. **Domain Expertise**:
   - Years in target industry
   - Deep expertise indicators (patents, publications, speaking engagements)
   - Industry certifications or licenses
   - Awards and recognition

5. **Network & Social Proof**:
   - LinkedIn connections (size of network)
   - LinkedIn followers (thought leadership)
   - Endorsements and recommendations
   - Mutual connections with successful entrepreneurs or investors

6. **Technical Skills** (for tech founders):
   - GitHub profile (commits, repos, stars, followers)
   - Stack Overflow reputation (for developers)
   - Open-source contributions
   - Technical publications or patents

**Founder Quality Score Components**:

**1. Education Score (0-100)**:
- Tier 1 university (Stanford, MIT, Harvard): 100 points
- Tier 2 university (top 50 globally): 70 points
- Other: 40 points
- Advanced degree in relevant field: +20 points

**2. Experience Score (0-100)**:
- Years of experience: 10 points per year (capped at 100)
- Industry relevance: +30 points if >5 years in target industry
- Previous executive roles: +20 points
- Worked at FAANG or unicorn: +15 points

**3. Track Record Score (0-100)**:
- Successful exit (acquisition >$10M or IPO): 100 points
- Successful exit (<$10M): 70 points
- Previous venture raised >$5M: 50 points
- Previous venture raised >$1M: 30 points
- No previous ventures: 10 points (first-time founder)
- Failed ventures: -10 points each (max -30)

**4. Domain Expertise Score (0-100)**:
- >10 years in industry: 100 points
- 5-10 years: 70 points
- 2-5 years: 40 points
- <2 years: 10 points
- Patents or publications: +20 points
- Industry awards: +15 points

**5. Network Score (0-100)**:
- LinkedIn connections >5,000: 100 points
- LinkedIn connections 1,000-5,000: 70 points
- LinkedIn connections 500-1,000: 40 points
- LinkedIn connections <500: 10 points
- Endorsements from investors or successful founders: +20 points

**6. Technical Skills Score (0-100, for tech founders)**:
- GitHub stars >1,000: 100 points
- GitHub stars 100-1,000: 70 points
- GitHub stars 10-100: 40 points
- Active contributor (commits in last 30 days): +20 points
- Notable open-source contributions: +15 points

**Overall Founder Quality Score**:

```
Founder_score = 0.20 * Education_score +
                0.25 * Experience_score +
                0.30 * Track_record_score +
                0.15 * Domain_expertise_score +
                0.10 * Network_score +
                (0.10 * Technical_skills_score if tech founder)
```

**Team Composition Analysis**:

1. **Team Completeness** (0-100):
   - CEO/Founder: Required (50 points)
   - CTO/Technical co-founder: +25 points (for tech startups)
   - CFO/Finance lead: +15 points
   - CMO/Marketing lead: +10 points
   - Full C-suite: 100 points

2. **Team Diversity**:
   - Gender diversity (at least 30% women): +10 points
   - Background diversity (different universities, companies): +10 points
   - Skill diversity (technical + business + domain): +10 points

3. **Co-founder Dynamics**:
   - Number of co-founders: 2-3 optimal (100 points), 1 or >4 (70 points)
   - Prior working relationship (worked together before): +20 points
   - Complementary skills (technical + business): +20 points

4. **Team Stability**:
   - Average tenure at current company: >2 years (100 points), 1-2 years (70 points), <1 year (40 points)
   - Employee turnover rate: <10% (good), 10-20% (acceptable), >20% (red flag)

**Red Flag Detection**:

Automatically flag founders with:
- Zero industry experience (domain expert critical)
- Multiple failed ventures with no successful exits (pattern of failure)
- Short tenures at previous jobs (average <1 year = job-hopping)
- No co-founder (solo founder risk)
- Legal issues (fraud, securities violations) - requires manual verification
- Negative social media presence (controversial statements, unprofessional behavior)

**Data Sources & Collection**:

- **LinkedIn API**: Profile data, connections, endorsements
- **Crunchbase API**: Previous ventures, funding raised, exits
- **GitHub API**: Code contributions, repos, stars
- **Google Scholar**: Academic publications
- **News API**: Media mentions, awards
- **Manual entry**: Company-provided bios, resumes

**Explainability Features**:

For each founder score, provide:
- Top 3 strengths (e.g., "Serial entrepreneur with 2 successful exits")
- Top 3 concerns (e.g., "Limited industry experience (1 year in FinTech)")
- Comparison to successful founders (e.g., "Education background similar to 73% of successful FinTech founders")
- Team composition assessment (e.g., "Strong technical team but missing marketing expertise")

**Acceptance Criteria**:

- Data collection success rate >90% (LinkedIn + Crunchbase coverage)
- Scoring accuracy validated against historical outcomes (founder scores vs. campaign success)
- No demographic bias (gender, ethnicity) - regular audits
- Explainability: Every founder score backed by at least 3 factors

---

#### 4.4.5 Market Analysis Module

**Purpose**: Assess market opportunity, competitive landscape, and industry trends.

**User Story**: As the AI system, I need to analyze market size and competition so that I can evaluate whether the company is targeting a large, growing market with defensible positioning.

**Functional Requirements**:

**Market Data Points**:

1. **Total Addressable Market (TAM)**:
   - Industry market size (current, in USD)
   - Industry growth rate (CAGR %, 5-year projection)
   - Source: Industry reports (Gartner, IDC), company-provided estimates

2. **Serviceable Addressable Market (SAM)**:
   - Target geography market size
   - Target customer segment size
   - Calculation: TAM × Geography_penetration × Segment_penetration

3. **Serviceable Obtainable Market (SOM)**:
   - Realistic market share (Year 3 projection)
   - Calculation: SAM × Realistic_penetration (typically 1-5%)

4. **Competitor Landscape**:
   - Number of direct competitors
   - Competitor funding raised (average, total)
   - Competitor valuations (average)
   - Market concentration (Herfindahl index)
   - New entrants (last 12 months)

5. **Industry Trends**:
   - Industry maturity stage (Emerging, Growth, Mature, Declining)
   - Regulatory environment (Supportive, Neutral, Restrictive)
   - Technology trends (AI, blockchain, etc.)
   - Consumer behavior shifts

**Market Opportunity Score (0-100)**:

**1. Market Size Score (0-100)**:
- TAM >$10B: 100 points
- TAM $1B-$10B: 70 points
- TAM $100M-$1B: 40 points
- TAM <$100M: 10 points

**2. Market Growth Score (0-100)**:
- Growth rate >30% CAGR: 100 points
- Growth rate 15-30%: 70 points
- Growth rate 5-15%: 40 points
- Growth rate <5%: 10 points
- Declining market (negative growth): 0 points (red flag)

**3. Competition Intensity Score (0-100)**:
- Fragmented market (no dominant player): 100 points
- Oligopoly (3-5 major players): 70 points
- Duopoly (2 dominant players): 40 points
- Monopoly (1 dominant player): 10 points

**4. Competitive Position Score (0-100)**:
- Unique product/service (no direct competitor): 100 points
- Better product than competitors (validated by users): 80 points
- At parity with competitors: 50 points
- Inferior to competitors: 20 points

**5. Regulatory Environment Score (0-100)**:
- Government support (subsidies, incentives): 100 points
- Neutral regulatory environment: 70 points
- Some regulatory hurdles (licensing, compliance): 40 points
- Heavy regulation (banking, healthcare): 20 points
- Regulatory uncertainty (crypto, AI): 10 points

**Overall Market Opportunity Score**:

```
Market_score = 0.30 * Market_size_score +
               0.25 * Market_growth_score +
               0.20 * Competition_intensity_score +
               0.15 * Competitive_position_score +
               0.10 * Regulatory_environment_score
```

**Competitive Analysis**:

**Competitive Differentiation Assessment**:
- Product/service features (10+ unique features: strong differentiation)
- Technology moat (patents, proprietary algorithms: defensible)
- Network effects (platform becomes more valuable with users: strong moat)
- Switching costs (high cost to switch to competitor: sticky)
- Brand strength (brand recognition, trust: defensible)

**Competitive Threats**:
- Well-funded competitors (raised >$50M): High threat
- Established incumbents (market share >30%): High threat
- New entrants with innovative products: Medium threat
- Substitutes (different solution to same problem): Medium threat

**Industry Benchmarking**:

Compare company's metrics to industry averages:
- Average funding raised by competitors
- Average time to profitability
- Average CAC and LTV for industry
- Typical growth rates and churn rates

Source: Crunchbase, PitchBook, industry reports

**Market Trend Analysis**:

**Technology Trends**:
- Emerging tech adoption (AI, blockchain, IoT): Tailwind or headwind?
- Platform shifts (mobile, cloud, SaaS): Aligned with company's product?

**Consumer Behavior Trends**:
- Preference shifts (sustainability, privacy, convenience)
- Generational changes (Gen Z, Millennials)
- Economic factors (recession, inflation, interest rates)

**Regulatory Trends**:
- New laws or regulations (GDPR, crypto regulations)
- Government initiatives (green energy, digital transformation)
- Compliance requirements (KYC/AML, data protection)

**Red Flag Detection**:

Automatically flag campaigns with:
- Declining market (negative CAGR)
- Tiny market (TAM <$100M for equity crowdfunding)
- Saturated market (>10 well-funded competitors)
- No competitive differentiation (product identical to competitors)
- High regulatory risk (awaiting critical license approval)

**Data Sources**:

- **Industry Reports**: Gartner, IDC, Forrester (purchased or free summaries)
- **Crunchbase API**: Competitor funding, valuations
- **PitchBook API** (Phase 2): Detailed market intelligence
- **News API**: Industry news, regulatory changes
- **Company-provided**: TAM/SAM/SOM estimates (validated by AI)

**Explainability Features**:

For each market score, provide:
- Market size and growth rate (with sources)
- Top 3 competitors (name, funding, positioning)
- Key market trends (e.g., "Industry growing at 40% CAGR driven by AI adoption")
- Competitive advantages (e.g., "Company has 3 patents vs. 0 for competitors")

**Acceptance Criteria**:

- Market data coverage >80% (at least TAM + growth rate for every campaign)
- Market size estimates within ±20% of third-party sources
- Competitor identification accuracy >90% (validated by manual review)
- Trend detection accuracy >75% (validated against actual industry developments)

---

#### 4.4.6 Recommendation Engine & Scoring Algorithm

**Purpose**: Synthesize all analysis modules into a single AI Investment Score and generate personalized recommendations.

**User Story**: As the AI system, I need to combine financial, sentiment, founder, and market analysis into an overall investment score so that investors can make informed decisions.

**Functional Requirements**:

**AI Investment Score (0-100)**:

The overall score is a weighted combination of 5 analysis modules:

```
AI_Investment_Score = 0.30 * Financial_health_score +
                      0.25 * Founder_quality_score +
                      0.20 * Market_opportunity_score +
                      0.15 * Sentiment_score +
                      0.10 * Traction_score
```

**Weights Rationale**:
- **Financial (30%)**: Most objective, quantifiable data (revenue, burn rate, unit economics)
- **Founder (25%)**: Team execution is critical for early-stage companies
- **Market (20%)**: Large, growing market essential for big returns
- **Sentiment (15%)**: Social proof and perception matter for growth
- **Traction (10%)**: Early validation of product-market fit

**Traction Score (0-100)**:

Calculated from platform behavior data:
- Users/customers: 10 points per 1,000 users (capped at 50 points)
- Revenue traction: 50 points if revenue >$100K ARR
- Growth velocity: 20 points if month-over-month growth >10%
- Engagement: 30 points if campaign receives >100 views/day, >10 comments

**Score Interpretation**:

- **90-100**: Exceptional opportunity (recommend to all investors)
- **80-89**: Strong opportunity (recommend to risk-tolerant investors)
- **70-79**: Good opportunity (recommend to investors with matching preferences)
- **60-69**: Average opportunity (neutral, let investors decide)
- **50-59**: Below-average opportunity (flag concerns, but don't block)
- **0-49**: Poor opportunity (recommend against investment)

**Score Confidence Interval**:

Every score includes a confidence range (e.g., "75 ± 10 points"):
- Narrow range (±5): High confidence (complete data, no red flags)
- Medium range (±10): Moderate confidence (some missing data)
- Wide range (±20): Low confidence (significant data gaps, many assumptions)

Confidence calculation:
```
Confidence = 1 - (Missing_data_penalty + Data_quality_penalty)

Missing_data_penalty = (Missing_required_fields / Total_required_fields) * 0.5
Data_quality_penalty = (1 - Data_quality_score) * 0.5
```

**Personalized Recommendations**:

Adjust base AI score based on investor preferences:

```
Personalized_score = Base_AI_score * Preference_match_multiplier

Preference_match_multiplier = (Region_match + Industry_match + Risk_tolerance_match) / 3

Region_match = 1.2 if campaign region in investor's preferred regions, else 0.8
Industry_match = 1.2 if campaign industry in investor's preferred industries, else 0.8
Risk_tolerance_match = 1.2 if campaign risk matches investor's tolerance, else 0.8
```

**Example**:
- Base AI score: 75
- Investor prefers: Singapore FinTech, high risk tolerance
- Campaign: Singapore FinTech, moderate risk
- Preference match: (1.2 + 1.2 + 0.8) / 3 = 1.07
- Personalized score: 75 × 1.07 = 80

**Recommendation Types**:

1. **Strong Buy** (AI score 85+, matches investor preferences):
   - Display: "Highly Recommended for You"
   - Badge color: Green
   - Explanation: "This campaign aligns perfectly with your investment preferences and has a high AI score."

2. **Buy** (AI score 70-84, matches some preferences):
   - Display: "Recommended"
   - Badge color: Light green
   - Explanation: "This is a solid opportunity that matches some of your criteria."

3. **Hold** (AI score 60-69):
   - Display: "Consider"
   - Badge color: Yellow
   - Explanation: "This campaign has potential but may not fully align with your preferences."

4. **Avoid** (AI score <60 or major red flags):
   - Display: "Not Recommended"
   - Badge color: Red
   - Explanation: "Our AI identified significant concerns with this campaign."

**Real-time Score Updates**:

Scores recalculated when:
- New financial data uploaded (quarterly updates)
- Sentiment shifts significantly (>10 point swing in 7 days)
- Major news event (funding round, product launch, scandal)
- Platform behavior changes (sudden spike in investments or withdrawals)

Update frequency: Daily batch job (2 AM UTC) for all active campaigns

**Explainability (Top 5 Factors)**:

For every score, provide the top 5 contributing factors:

**Positive Factors** (ranked by impact):
1. "Strong revenue growth (127% YoY)" - Financial
2. "Experienced founder (2 successful exits)" - Founder
3. "Large, growing market ($5B TAM, 40% CAGR)" - Market
4. "Positive social sentiment (88/100)" - Sentiment
5. "Strong traction (50K users, 15% MoM growth)" - Traction

**Risk Factors** (ranked by severity):
1. "High burn rate ($150K/month, 8-month runway)" - Financial
2. "Intense competition (5 well-funded competitors)" - Market
3. "Limited marketing expertise (no CMO)" - Founder
4. "Low mention volume (insufficient social data)" - Sentiment
5. "First-time founder (no prior exits)" - Founder

**Acceptance Criteria**:

- Score generation latency <2 seconds per campaign
- Score accuracy >70% (campaigns with score >80 perform better than score <60)
- Calibration: 80% of campaigns with score 80 should achieve positive returns
- Explainability: Every score backed by top 5 factors (positive + negative)
- Personalization lift: Personalized recommendations increase investment rate by >15%

---

#### 4.4.7 Learning System & Human Feedback Loop

**Purpose**: Continuously improve AI models through reinforcement learning and human oversight.

**User Story**: As the AI system, I need to learn from outcomes and human feedback so that my predictions become more accurate over time.

**Functional Requirements**:

**Phase 1: Human-in-the-Loop (100% Human Approval)**

All AI recommendations reviewed by investment team before being shown to investors:

1. **AI Generates Score**:
   - System calculates AI Investment Score for new campaign
   - Score displayed in admin review queue with full explainability

2. **Human Review**:
   - Investment team member reviews AI score and reasoning
   - Options: Approve (agree with AI), Override (disagree), Request More Data
   - If Override: Human provides new score and reasoning

3. **Feedback Collection**:
   - Log: Original AI score, Human decision (approve/override), Human score (if override)
   - Feedback form: Why did you override? (dropdown: Missing data, Wrong calculation, Domain knowledge, Other)
   - Feedback stored in training dataset

4. **Display to Investors**:
   - If Approved: Show AI score
   - If Override: Show human-adjusted score with badge "Reviewed by Investment Team"

**Phase 2: Semi-Automated (50% Spot-Check)**

AI recommendations shown directly to investors, with random human audits:

1. **AI Score Published**:
   - 50% of campaigns: AI score published immediately
   - 50% of campaigns: Flagged for human review (random selection)

2. **Spot-Check Review**:
   - Investment team reviews flagged campaigns within 24 hours
   - If disagreement: Override score, log feedback, notify users of score change

3. **Disagreement Threshold**:
   - If human override rate >20% (AI frequently wrong), revert to Phase 1
   - If override rate <5% (AI very accurate), progress to Phase 3

**Phase 3: Fully Automated (10% Random Audit)**

AI operates autonomously for most campaigns, with minimal human oversight:

1. **Automatic Publishing**:
   - 90% of campaigns: AI score published immediately, no human review
   - 10% of campaigns: Random audit (post-publication review)

2. **Continuous Monitoring**:
   - Weekly performance review (AI accuracy vs. actual outcomes)
   - Monthly model retraining with new data
   - Quarterly external audit (third-party ML experts)

3. **Exception Handling**:
   - Red flags (score <50): Always human review before publishing
   - High-value campaigns (>$1M): Always human review
   - Investor complaints: Trigger immediate human review

**Reinforcement Learning Pipeline**:

**1. Outcome Data Collection**:

Track actual campaign outcomes (ground truth):
- Campaign success: Reached funding goal (binary: yes/no)
- Investor returns: ROI at 12 months, 24 months (if available)
- Exit events: Acquisition, IPO, shutdown (if applicable)
- Investor satisfaction: Survey ratings (1-5 stars)

**2. Reward Function**:

Calculate reward for each AI prediction:
```
Reward = Success_bonus + ROI_bonus + Calibration_bonus - False_positive_penalty

Success_bonus = +10 if campaign succeeded and AI score >70
ROI_bonus = +5 per 10% ROI if positive returns
Calibration_bonus = +5 if actual outcome within AI confidence interval
False_positive_penalty = -20 if campaign failed and AI score >80 (overconfident)
```

**3. Model Retraining**:

- Frequency: Monthly (or when 100+ new outcomes available)
- Training data: Historical campaigns with known outcomes
- Validation split: 80% train, 20% test
- Performance metrics: Accuracy, Precision, Recall, AUC-ROC, Calibration error

**4. A/B Testing**:

Test new models against production model:
- 90% traffic: Production model (current best)
- 10% traffic: Challenger model (new, experimental)
- Comparison metrics: Investor conversion rate, campaign success rate, user satisfaction
- Promotion: If challenger outperforms by >5% for 2 weeks, promote to production

**Feedback Channels**:

1. **Admin Overrides** (structured feedback):
   - Captured during Phase 1 human review
   - High signal quality (domain experts)

2. **Investor Feedback** (implicit signals):
   - Investments made (positive signal for high-scored campaigns)
   - Watchlist additions (moderate positive signal)
   - Dismissals (negative signal: "Not Interested" button)
   - Bounce rate (opened campaign but left immediately = negative)

3. **Campaign Outcomes** (ground truth):
   - Funding success rate
   - Time to funding goal
   - Post-funding performance (if available)

4. **User Surveys** (explicit feedback):
   - "Was this recommendation helpful?" (thumbs up/down)
   - "Why did you invest in this campaign?" (multiple choice)
   - "What would improve our recommendations?" (open text)

**Model Versioning & Rollback**:

- All models versioned (v1.0, v1.1, v2.0, etc.)
- Track model lineage (which dataset, hyperparameters, features used)
- Instant rollback if new model degrades performance
- Blue-green deployment (zero-downtime model swaps)

**Performance Monitoring**:

- Real-time metrics dashboard (admin panel):
  - AI accuracy (last 7 days, 30 days, 90 days)
  - Override rate (human disagreement %)
  - Prediction calibration (predicted vs. actual success rate)
  - Model latency (inference time)

- Alerts triggered if:
  - Accuracy drops >10% (model drift)
  - Override rate >30% (model unreliable)
  - Latency >5 seconds (performance issue)
  - Bias detected (disparate impact on demographic groups)

**Acceptance Criteria**:

- Phase 1 → Phase 2 transition: Override rate <10% for 3 consecutive months
- Phase 2 → Phase 3 transition: Override rate <5% for 6 consecutive months
- Model accuracy improvement: +5% per year (measured on holdout test set)
- Retraining success rate >95% (successful training runs / total attempts)
- Feedback loop latency <24 hours (outcome data → model retraining)

---

#### 4.4.8 Explainability Dashboard

**Purpose**: Provide transparent, human-readable explanations for AI decisions.

**User Story**: As an investor, I want to understand how the AI calculated its score so that I can trust the recommendation and make informed decisions.

**Functional Requirements**:

**Dashboard Location**:

- Accessible from campaign detail page (tab: "AI Analysis")
- Dedicated explainability page for power users (Settings → AI Insights)

**Core Components**:

**1. Overall AI Score Display**:

```
┌─────────────────────────────────────────────────┐
│          AI Investment Score: 82/100            │
│              (Confidence: ± 8 points)           │
│                                                 │
│  ████████████████████████░░░░░░  82%           │
│                                                 │
│  Recommendation: Strong Buy ✓                   │
│  "This campaign aligns with your preferences    │
│   and shows strong fundamentals."               │
└─────────────────────────────────────────────────┘
```

**2. Score Breakdown (Visual Pie/Bar Chart)**:

```
Financial Health:     █████████░ 88/100  (30% weight = 26.4 pts)
Founder Quality:      ████████░░ 78/100  (25% weight = 19.5 pts)
Market Opportunity:   █████████░ 85/100  (20% weight = 17.0 pts)
Sentiment:            ███████░░░ 75/100  (15% weight = 11.3 pts)
Traction:             ████████░░ 80/100  (10% weight = 8.0 pts)
                                         ─────────────────
                                         Total: 82.2/100
```

**3. Top 5 Positive Factors** (expandable):

```
✓ Strong revenue growth (127% YoY)
  Financial Health | Confidence: 95%
  "Revenue increased from $500K to $1.1M, outpacing industry average of 80%."

✓ Experienced founder (2 successful exits)
  Founder Quality | Confidence: 90%
  "Founder previously exited StartupX ($15M acquisition) and StartupY (IPO)."

✓ Large, growing market ($5B TAM, 40% CAGR)
  Market Opportunity | Confidence: 85%
  "AI-powered FinTech market projected to grow from $5B to $27B by 2028."

✓ Positive social sentiment (88/100)
  Sentiment | Confidence: 70%
  "Media coverage overwhelmingly positive (15 articles, 92% positive tone)."

✓ Strong traction (50K users, 15% MoM growth)
  Traction | Confidence: 95%
  "User base growing 15% month-over-month, above industry median of 10%."
```

**4. Top 5 Risk Factors** (expandable):

```
⚠ High burn rate ($150K/month, 8-month runway)
  Financial Health | Severity: High
  "Current cash ($1.2M) will last 8 months at current burn rate. Requires new funding by Q3 2026."
  Mitigation: "Campaign funding extends runway to 18 months."

⚠ Intense competition (5 well-funded competitors)
  Market Opportunity | Severity: Medium
  "5 direct competitors raised $200M+ combined. Differentiation critical."
  Competitors: CompetitorA ($50M), CompetitorB ($80M), CompetitorC ($40M)

⚠ Limited marketing expertise (no CMO)
  Founder Quality | Severity: Medium
  "Team strong on product/engineering, but lacks dedicated marketing leader."
  Mitigation: "Company hiring CMO (job posting active)."

⚠ Low social mention volume (25 mentions/month)
  Sentiment | Severity: Low
  "Limited social media presence may indicate low brand awareness."
  Industry Average: 75 mentions/month

⚠ First-time founder (no prior exits)
  Founder Quality | Severity: Low
  "Founder has no previous startup exits, though 8 years in FinTech industry."
```

**5. Confidence Interval Explanation**:

```
Confidence Range: 74 - 90 points (±8)

Why this range?
• Complete financial data: High confidence (+)
• Limited social data: Reduces confidence (-)
• Industry benchmarks available: High confidence (+)
• First-time founder: Moderate uncertainty (-)

Interpretation:
"We are 90% confident the true score falls between 74 and 90.
 Lower end if risks materialize, upper end if company executes well."
```

**6. Similar Campaigns Comparison**:

```
How does this compare to similar campaigns?

This Campaign:   82/100  ████████████████████░░
Industry Average: 68/100  ██████████████░░░░░░░░
Top 10% Campaigns: 87/100 ████████████████████░

This campaign scores higher than 73% of similar campaigns
in the FinTech industry.
```

**7. Model Information (Transparency)**:

```
AI Model Details:

Model Version: v2.3.1
Last Trained: March 15, 2026
Training Data: 1,247 campaigns (2023-2026)
Accuracy: 76% (on holdout test set)
Calibration: 0.82 (good calibration = 1.0)

Human Oversight:
✓ Reviewed by Investment Team on April 3, 2026
✓ No adjustments made (AI score approved)
```

**8. Interactive "What If?" Scenarios** (Phase 2):

Allow users to explore how score changes with different assumptions:

```
What if...?

[Slider] Revenue growth rate: 127% → 80%
  Impact: Score drops to 78/100 (-4 points)

[Toggle] Founder had 1 successful exit (instead of 2)
  Impact: Score drops to 79/100 (-3 points)

[Input] Burn rate reduced to $100K/month
  Impact: Score increases to 85/100 (+3 points)
```

**User Interactions**:

1. **Expand/Collapse Sections**:
   - Default: Show top 3 positive + top 3 negative factors
   - Click "Show More" to expand to top 5 each

2. **Hover for Details**:
   - Hover over any metric to see definition, calculation method, data source

3. **Click Through to Data**:
   - Click "Revenue growth (127% YoY)" → Navigate to Financials tab
   - Click "2 successful exits" → Navigate to Founder profile

4. **Feedback Buttons**:
   - "Was this helpful?" (thumbs up/down)
   - "Report an issue" (form: incorrect data, biased analysis, other)

**Mobile Optimization**:

- Responsive design (stacked vertically on mobile)
- Swipeable cards for factors (swipe left/right)
- Collapsible sections (default collapsed on mobile)

**Accessibility**:

- Screen reader support (all charts have text descriptions)
- Keyboard navigation (tab through factors)
- High contrast mode (for visually impaired)
- Color-blind friendly palette (not relying solely on color)

**Acceptance Criteria**:

- Explainability dashboard load time <1s
- 100% of scores have at least 5 positive and 5 negative factors
- User comprehension >70% (validated via user testing: "Do you understand how the score was calculated?")
- User trust >60% (survey: "Do you trust the AI recommendation?")

---

#### 4.4.9 AI Governance & Oversight

**Purpose**: Ensure responsible AI development, deployment, and monitoring with proper governance frameworks.

**User Story**: As a platform admin, I need governance mechanisms to ensure the AI operates fairly, transparently, and in compliance with regulations.

**Functional Requirements**:

**Governance Structure**:

**1. AI Ethics Committee**:
- Composition: 5 members (CTO, Legal, Compliance, External AI ethicist, User representative)
- Responsibilities:
  - Review and approve AI model changes
  - Investigate bias complaints
  - Set ethical guidelines for AI development
  - Publish annual AI transparency report
- Meeting frequency: Monthly (or ad-hoc for urgent issues)

**2. Model Review Board**:
- Composition: 3 senior engineers + 2 investment team members
- Responsibilities:
  - Approve new models for production deployment
  - Review A/B test results
  - Investigate model failures or anomalies
  - Recommend rollbacks if needed
- Meeting frequency: Before every major model deployment

**3. External Audit** (annual):
- Third-party AI audit firm reviews:
  - Model fairness (bias detection across demographics)
  - Data privacy (PII handling, GDPR compliance)
  - Model performance (accuracy, calibration)
  - Governance processes (documented procedures)
- Audit report published publicly (summary version)

**Bias Detection & Mitigation**:

**Protected Attributes** (monitored for disparate impact):
- Founder gender (male, female, non-binary)
- Founder ethnicity (Asian, White, Black, Hispanic, Other)
- Founder age (<30, 30-45, >45)
- Company location (developed vs. emerging markets)

**Fairness Metrics**:

1. **Demographic Parity**:
   - AI scores should have similar distributions across demographic groups
   - Test: Compare average score for male-founded vs. female-founded companies
   - Threshold: Difference <5 points (acceptable), >10 points (unacceptable bias)

2. **Equal Opportunity**:
   - True positive rate should be equal across groups (among successful campaigns)
   - Test: Of campaigns that succeeded, did AI score them equally high across groups?
   - Threshold: True positive rate difference <10% across groups

3. **Predictive Parity**:
   - Precision should be equal across groups (among high-scored campaigns)
   - Test: Of campaigns scored >80, do they succeed at equal rates across groups?
   - Threshold: Success rate difference <10% across groups

**Bias Mitigation Strategies**:

If bias detected:
1. **Immediate**: Add fairness constraints to model (e.g., equal error rates across groups)
2. **Short-term**: Collect more training data for underrepresented groups
3. **Long-term**: Re-engineer features to remove proxy variables (e.g., university prestige may proxy for socioeconomic status)

**Data Privacy & Security**:

1. **PII Protection**:
   - All personally identifiable information encrypted (AES-256)
   - PII removed before model training (anonymized datasets)
   - Access logs: Who accessed PII, when, why (audit trail)

2. **Data Minimization**:
   - Collect only necessary data for AI analysis
   - Delete data older than 7 years (regulatory retention period)
   - Users can request data deletion (GDPR "right to be forgotten")

3. **Model Security**:
   - Model files encrypted at rest
   - Access control: Only authorized systems can query model API
   - Rate limiting: Prevent model extraction attacks (too many queries)

**Regulatory Compliance**:

**1. Singapore MAS Compliance** (primary jurisdiction):
- Fairness, Ethics, Accountability, Transparency (FEAT) principles
- Explainable AI required (✓ Implemented in 4.4.8)
- Human oversight required for high-risk decisions (✓ Phase 1 human-in-loop)
- Regular audits (✓ Annual external audit)

**2. EU AI Act Compliance** (if expanding to Europe):
- High-risk AI system classification (investment advice = high-risk)
- Conformity assessment required
- Post-market monitoring required (✓ 4.4.7 continuous monitoring)
- Transparency obligations (✓ Model information disclosed)

**3. US SEC Compliance** (future, if expanding to US):
- Investment Advisers Act registration (if AI provides investment advice)
- Disclosure of AI use in marketing materials
- Recordkeeping requirements (7 years)

**Incident Response Plan**:

**Trigger Events**:
- AI generates extremely inaccurate score (>30 points off actual outcome)
- Bias complaint filed by user
- Model performance degrades >10%
- Security breach (model stolen, data leaked)
- Regulatory inquiry

**Response Procedure**:
1. Immediate: Pause AI system (revert to human-only review)
2. Investigate: Root cause analysis (24-48 hours)
3. Remediate: Fix issue (model retrain, data correction, process change)
4. Communicate: Notify affected users, publish incident report
5. Prevent: Update processes to prevent recurrence

**Transparency Reporting**:

**Quarterly Internal Report** (for management):
- AI performance metrics (accuracy, calibration, latency)
- Human override rate (Phase 1/2)
- Bias metrics (fairness across demographics)
- User feedback summary (satisfaction, complaints)

**Annual Public Report** (for users and regulators):
- How AI works (high-level, non-technical)
- Key performance metrics (accuracy, etc.)
- Bias detection results and mitigation actions
- External audit summary
- Governance structure and processes

**User Rights**:

1. **Right to Explanation**:
   - Users can request detailed explanation for any AI decision
   - Provided via explainability dashboard (4.4.8)

2. **Right to Human Review**:
   - Users can challenge AI score and request human review
   - Investment team reviews within 48 hours
   - If overridden, user notified with explanation

3. **Right to Opt-Out**:
   - Users can opt out of AI recommendations
   - Instead see campaigns sorted by funding progress or date
   - No penalty for opting out

**Acceptance Criteria**:

- AI Ethics Committee meets monthly (12 meetings/year)
- Bias audit performed quarterly (4 audits/year)
- External audit completed annually (1 audit/year, published)
- Incident response time <24 hours (from detection to remediation)
- User complaints resolved within 48 hours
- Zero major AI incidents (defined as causing user harm or regulatory fine)

---

**Section 4.4 Summary**:

Section 4.4 covers the complete AI Investment Manager system:

- **4.4.1**: Data Ingestion Pipeline (5 data sources, ETL process, quality checks)
- **4.4.2**: Financial Analysis Module (6 metric categories, scoring algorithm, benchmarking)
- **4.4.3**: Sentiment Analysis Module (4 social data sources, NLP models, trend detection)
- **4.4.4**: Founder/Team Analysis Module (6 data points, team composition analysis)
- **4.4.5**: Market Analysis Module (TAM/SAM/SOM, competitive landscape, trends)
- **4.4.6**: Recommendation Engine (overall scoring algorithm, personalization, explainability)
- **4.4.7**: Learning System (3-phase human oversight, reinforcement learning, feedback loops)
- **4.4.8**: Explainability Dashboard (transparent score breakdowns, interactive UI)
- **4.4.9**: AI Governance (ethics committee, bias detection, regulatory compliance)

**Total lines added**: ~1,200 lines
**Estimated implementation time**: 16-20 weeks (for MVP, Phase 1 features)

**Key Differentiators**:
- Transparent, explainable AI (every score backed by data)
- Progressive automation (human-in-loop → semi-automated → fully automated)
- Continuous learning (improves from outcomes and feedback)
- Bias detection and mitigation (fairness across demographics)
- Regulatory compliant (MAS FEAT, EU AI Act ready)

---

### 4.5 Admin Panel

The Admin Panel is the command center for platform operations, compliance, and oversight. It provides platform administrators with tools to manage users, review campaigns, monitor compliance, configure system settings, and oversee AI operations.

**User Roles**:
- **Super Admin**: Full access to all features, system configuration
- **Compliance Officer**: KYC/AML review, audit logs, regulatory reports
- **Campaign Reviewer**: Campaign approval, content moderation
- **Support Agent**: User support, basic user management (view-only for sensitive data)
- **Finance Officer**: Fee configuration, treasury management, financial reports
- **AI Auditor**: AI model monitoring, performance audits, bias detection

---

#### 4.5.1 User Management

**Overview**:
Comprehensive user management system allowing admins to view, search, edit, suspend, and delete user accounts. Includes role management, activity monitoring, and security controls.

**User List View**:

**Display Columns**:
- User ID (UUID)
- Name (First + Last)
- Email
- Role (Investor, Company, Admin)
- KYC Status (Verified, Pending, Rejected, Not Started)
- Account Status (Active, Suspended, Deleted)
- Registration Date
- Last Login
- Total Invested (for investors) / Campaigns Created (for companies)
- Actions (View, Edit, Suspend, Delete)

**Filters**:
- Role: Investor, Company, Admin, All
- KYC Status: Verified, Pending, Rejected, Not Started, All
- Account Status: Active, Suspended, Deleted, All
- Registration Date Range: From - To
- Country: Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia, All
- Investment Range: $0-$1K, $1K-$10K, $10K-$100K, $100K+, All

**Search**:
- Search by: Name, Email, User ID, Wallet Address
- Autocomplete suggestions
- Real-time results (updates as you type)

**Sorting**:
- Sort by: Registration Date, Last Login, Total Invested, Name (A-Z, Z-A)
- Default: Registration Date (newest first)

**Pagination**:
- 25, 50, 100, 200 users per page
- Default: 50 per page
- Total count displayed: "Showing 1-50 of 12,345 users"

---

**User Detail View**:

**When admin clicks "View" on a user, display:**

**Section 1: Basic Information**:
- Full Name
- Email (with verification status: ✓ Verified or ✗ Not Verified)
- Phone Number (if provided)
- Country
- Registration Date
- Last Login
- Account Status (Active, Suspended, Deleted)
- Role (Investor, Company, Admin)

**Section 2: KYC Information**:
- KYC Status: Verified, Pending, Rejected, Not Started
- KYC Provider: Sumsub, Onfido
- Verification Date (if verified)
- KYC Documents Submitted:
  - ID Document (Passport, National ID, Driver's License)
  - Proof of Address (Utility bill, Bank statement)
  - Selfie (liveness check)
- Review Notes (from KYC reviewer)
- Actions:
  - View KYC Documents (button)
  - Approve KYC (button, if pending)
  - Reject KYC (button, with reason modal)
  - Request Re-submission (button, with instructions)

**Section 3: Investment Activity** (for Investors):
- Total Invested: $50,000 USDC
- Number of Campaigns Invested: 12
- Portfolio Value: $55,000 (10% gain)
- Distributions Received: $2,500
- Average Investment Size: $4,167
- Largest Investment: $10,000 (Campaign XYZ)
- First Investment Date: March 15, 2026
- Recent Investments (last 5):
  - Table: Campaign Name, Amount, Date, Status (Active, Exited, Refunded)

**Section 4: Campaign Activity** (for Companies):
- Campaigns Created: 3
- Active Campaigns: 1
- Funded Campaigns: 1
- Failed Campaigns: 1
- Total Raised: $250,000
- Average Campaign Size: $83,333
- Success Rate: 33% (1 of 3 funded)
- Recent Campaigns (all):
  - Table: Campaign Name, Status, Goal, Raised, Created Date

**Section 5: Wallet Information**:
- Connected Wallet Address: 5Xw8...9Kp2 (truncated)
- Wallet Type: Phantom, Solflare, Ledger, MetaMask
- Wallet Balance: 1,234.56 USDC
- Last Transaction: April 12, 2026
- Actions:
  - View Full Address (button)
  - Copy Address (button)

**Section 6: Security Information**:
- MFA Enabled: Yes / No
- MFA Type: TOTP, SMS, Biometric
- Failed Login Attempts (last 30 days): 0
- Password Last Changed: March 10, 2026
- Sessions: 2 active sessions
  - Device 1: Chrome on Windows (Singapore, last active 2 hours ago)
  - Device 2: Safari on iPhone (Singapore, last active 1 day ago)
- Actions:
  - Force Logout All Sessions (button)
  - Require Password Reset (button)

**Section 7: Activity Log** (last 50 actions):
- Table: Timestamp, Action Type, Description, IP Address, Device
- Actions: Login, Logout, Investment, Campaign Created, KYC Submitted, Password Changed, etc.
- Export: CSV, JSON

**Section 8: Admin Actions**:
- Edit User (button) → Opens edit modal
- Suspend Account (button) → Requires reason + confirmation
- Delete Account (button) → Requires confirmation + audit log entry
- Send Email (button) → Opens email composer
- Add Note (button) → Internal admin note (not visible to user)

---

**Edit User Modal**:

**Editable Fields**:
- First Name, Last Name
- Email (with email verification re-send option)
- Phone Number
- Country
- Role (Investor, Company, Admin) - Super Admin only
- Account Status (Active, Suspended) - Super Admin only
- KYC Status Override (Super Admin only, requires reason)

**Actions**:
- Save Changes (button) → Saves to database, logs to audit trail
- Cancel (button) → Closes modal without saving

---

**Suspend Account Modal**:

**Fields**:
- Reason (required): Dropdown
  - Fraudulent Activity
  - AML/Sanctions Hit
  - Terms of Service Violation
  - Regulatory Request
  - User Request
  - Other (requires text input)
- Additional Notes (optional): Text area
- Suspension Duration:
  - Permanent
  - Temporary (specify end date)

**Effects of Suspension**:
- User cannot login
- All active sessions terminated
- Investments frozen (no new investments)
- Campaigns paused (if company)
- User notified via email (unless "Do not notify" checkbox is checked)

**Actions**:
- Confirm Suspension (button) → Suspends account, logs to audit trail
- Cancel (button) → Closes modal

---

**Delete Account Modal**:

**Warning Message**:
"⚠️ WARNING: This action is IRREVERSIBLE. User data will be anonymized and marked as deleted. Investment and transaction records will be retained for 7 years per regulatory requirements."

**Confirmation Steps**:
1. Reason for Deletion (required): Dropdown
   - User Requested (GDPR/PDPA right to be forgotten)
   - Fraudulent Account
   - Duplicate Account
   - Legal Request
   - Other
2. Type "DELETE" to confirm (input field)
3. Re-enter your admin password (for security)

**Actions**:
- Confirm Deletion (button, disabled until all steps completed)
- Cancel (button)

**Deletion Process**:
1. Anonymize personal data (name → "Deleted User", email → hashed)
2. Remove wallet address
3. Remove KYC documents
4. Retain transaction records (7-year retention)
5. Mark account as deleted
6. Log to audit trail
7. Send confirmation email to user (if user requested)

---

**Bulk Actions**:

**When admin selects multiple users (checkboxes), display:**

**Bulk Actions Dropdown**:
- Export Selected (CSV, JSON)
- Send Bulk Email
- Tag Users (custom tags for segmentation)
- Suspend Selected (requires reason)

---

**User Analytics Dashboard** (top of User Management page):

**Metrics Cards**:
- Total Users: 12,345 (↑ 15% vs last month)
- Active Users (logged in last 30 days): 8,234 (67%)
- KYC Verified: 9,123 (74%)
- Suspended Accounts: 23 (0.2%)

**Charts**:
- User Growth (line chart, last 12 months)
- User Breakdown by Role (pie chart: Investors 85%, Companies 14%, Admins 1%)
- User Breakdown by Country (bar chart)
- KYC Status Distribution (pie chart)

---

**Acceptance Criteria**:

- Admin can view all users with filters and search
- Admin can view detailed user profile with all information
- Admin can edit user details (logs to audit trail)
- Admin can suspend account (requires reason, logs to audit trail)
- Admin can delete account (requires confirmation, anonymizes data)
- Bulk actions work for selected users
- User analytics dashboard displays key metrics
- All admin actions logged to audit trail (who, what, when, why)
- Role-based permissions enforced (e.g., Support Agent cannot delete accounts)
- UI loads in <2s with 10,000 users, pagination for performance

---

#### 4.5.2 Campaign Approval Workflow

**Overview**:
Multi-step approval process for campaign submissions. Ensures all campaigns meet platform standards, comply with regulations, and have complete documentation before going live.

**Campaign Review Queue**:

**Display Columns**:
- Campaign ID
- Company Name
- Campaign Title
- Status (Submitted, Under Review, Approved, Rejected, Changes Requested)
- Submission Date
- Assigned Reviewer (if any)
- Priority (High, Medium, Low)
- Review Deadline (SLA: 5 business days)
- Actions (Review, Assign, Escalate)

**Filters**:
- Status: Submitted, Under Review, Approved, Rejected, Changes Requested, All
- Submission Date Range: From - To
- Assigned Reviewer: Dropdown (list of Campaign Reviewers)
- Priority: High, Medium, Low, All
- Industry: Technology, Real Estate, Healthcare, etc., All

**Sorting**:
- Sort by: Submission Date, Priority, Deadline, Company Name
- Default: Submission Date (oldest first) + Priority (high first)

**Auto-Assignment**:
- When campaign submitted, auto-assign to next available reviewer (round-robin)
- High-priority campaigns (>$1M goal) auto-assigned to senior reviewer

---

**Campaign Review Page**:

**When admin clicks "Review" on a campaign, display:**

**Section 1: Campaign Overview**:
- Campaign Title
- Company Name
- Tagline
- Industry / Sector
- Funding Goal: $500,000 USDC
- Minimum Investment: $100
- Campaign Duration: 60 days
- Submission Date: April 10, 2026
- Status: Under Review
- Assigned Reviewer: John Doe

**Section 2: Review Checklist**:

**Admin must verify each item:**

**☐ Company Information Complete**:
- Company Name: ✓
- Registration Number: ✓
- Country of Incorporation: ✓
- Website: ✓ (clickable link, opens in new tab)
- Social Media Links: ✓ (LinkedIn, Twitter)

**☐ Campaign Description Quality**:
- Description Length: 1,200 words ✓ (minimum 500 words)
- Clarity: Good / Needs Improvement (dropdown)
- Grammar: Good / Needs Improvement
- No Prohibited Content: ✓ (no gambling, adult content, weapons, etc.)

**☐ Financial Documents Uploaded**:
- Balance Sheet (last 2 years): ✓ Uploaded (link to view)
- Profit & Loss Statement (last 2 years): ✓ Uploaded
- Cash Flow Statement (last 2 years): ✓ Uploaded
- Financial Projections (next 3 years): ✓ Uploaded
- Cap Table: ✓ Uploaded

**☐ Legal Documents Uploaded**:
- Certificate of Incorporation: ✓ Uploaded
- Business License: ✓ Uploaded
- Terms of Investment: ✓ Uploaded
- Shareholder Agreement: ✓ Uploaded
- Legal Opinion (if required): ✗ Not Uploaded

**☐ Team Information**:
- Founder Profiles: 2 profiles ✓ (minimum 1)
- Team Member Profiles: 5 profiles ✓
- LinkedIn Verification: ✓ All verified
- Background Checks: ✓ Completed (via third-party service)

**☐ Compliance Checks**:
- Company KYC: ✓ Verified
- Founders KYC: ✓ All verified
- Sanctions Screening: ✓ No hits
- AML Risk Assessment: Low Risk ✓
- Regulatory Approval (if required): N/A

**☐ Content Review**:
- Images Quality: Good ✓
- Video Pitch: ✓ Uploaded (link to view, 3:45 duration)
- No Misleading Claims: ✓ (reviewer manually verifies)
- Risk Disclosures Present: ✓

**☐ Valuation & Terms**:
- Pre-Money Valuation: $2,000,000 ✓
- Equity Offered: 20% ✓
- Share Price: $1.00 ✓
- Valuation Reasonable: Yes / Needs Justification (dropdown)

---

**Review Decision**:

**Options**:
1. **Approve Campaign**:
   - Campaign goes live immediately
   - Company notified via email + in-app notification
   - Campaign visible to investors

2. **Request Changes**:
   - Select issues from checklist (multi-select)
   - Add custom note explaining what needs to be fixed
   - Company receives notification with detailed feedback
   - Campaign status: "Changes Requested"
   - Company can resubmit after making changes

3. **Reject Campaign**:
   - Requires reason (dropdown + text area):
     - Does Not Meet Platform Standards
     - Insufficient Documentation
     - High Risk / Compliance Concerns
     - Fraudulent / Misleading Information
     - Other (specify)
   - Company notified via email
   - Company can dispute rejection (escalates to senior reviewer)

**Actions**:
- Approve (button, green) → Confirms approval, logs to audit trail
- Request Changes (button, yellow) → Opens modal to specify changes
- Reject (button, red) → Opens modal to specify reason
- Assign to Another Reviewer (button) → Reassigns to different reviewer
- Escalate to Senior Reviewer (button) → For complex cases
- Add Internal Note (button) → Visible only to admins

---

**Request Changes Modal**:

**Fields**:
- Issues to Address (multi-select checkboxes):
  - Company Information Incomplete
  - Financial Documents Missing or Unclear
  - Legal Documents Missing
  - Team Information Incomplete
  - Content Quality Issues (grammar, clarity)
  - Valuation Needs Justification
  - Compliance Documents Missing
  - Other (specify)
- Detailed Feedback (required): Text area (visible to company)
  - Placeholder: "Please explain what needs to be changed and provide specific instructions..."
- Internal Notes (optional): Text area (visible only to admins)
- Set Deadline for Resubmission: 7 days (default), 14 days, 30 days

**Actions**:
- Send Feedback (button) → Sends to company, changes campaign status
- Cancel (button)

---

**Reject Campaign Modal**:

**Fields**:
- Rejection Reason (required): Dropdown
  - Does Not Meet Platform Standards
  - Insufficient Documentation
  - High Risk / Compliance Concerns
  - Fraudulent / Misleading Information
  - Regulatory Issues
  - Other (specify)
- Detailed Explanation (required): Text area (visible to company)
- Internal Notes (optional): Text area (visible only to admins)
- Allow Resubmission: Yes / No (checkbox)
- Blacklist Company (for fraud): Yes / No (checkbox, Super Admin only)

**Warning**:
"This campaign will be rejected and the company will be notified. This action is logged in the audit trail."

**Actions**:
- Confirm Rejection (button) → Rejects campaign, notifies company
- Cancel (button)

---

**Campaign Resubmission Flow**:

**When company resubmits after "Changes Requested":**
1. Campaign status changes to "Resubmitted"
2. Auto-assigns to same reviewer (or reassigns if unavailable)
3. Reviewer sees:
   - Previous feedback given
   - Changes made by company (highlighted)
   - New version vs old version comparison
4. Reviewer re-reviews and approves or requests further changes

---

**Review Analytics Dashboard** (top of Campaign Review Queue):

**Metrics Cards**:
- Pending Reviews: 12 campaigns
- Avg Review Time: 2.3 days (SLA: 5 days) ✓
- Approval Rate: 78% (industry benchmark: 65-75%)
- Rejected Campaigns: 5 (12%)
- Changes Requested: 4 (10%)

**Charts**:
- Review Time Trend (line chart, last 12 months)
- Approval Rate by Reviewer (bar chart, for performance tracking)
- Rejection Reasons (pie chart)
- Submissions by Industry (bar chart)

---

**SLA Monitoring**:

**Service Level Agreement**:
- Standard Review: 5 business days
- High-Priority (>$1M goal): 3 business days
- Resubmission Review: 2 business days

**SLA Alerts**:
- Yellow Alert: 80% of SLA time elapsed (e.g., day 4 of 5)
- Red Alert: SLA breached (overdue)
- Email notification to reviewer + supervisor

---

**Acceptance Criteria**:

- Admin can view all pending campaigns in review queue
- Admin can filter, sort, and search campaigns
- Admin can review campaign with complete checklist
- Admin can approve, request changes, or reject campaign
- Company receives email notification of decision within 1 hour
- All review decisions logged to audit trail (who, what, when, why)
- SLA monitoring alerts reviewers of approaching deadlines
- Review analytics dashboard displays key metrics
- Resubmission flow works correctly (assigns to same reviewer, shows changes)
- Role-based permissions enforced (only Campaign Reviewers can approve)

---

#### 4.5.3 KYC Review Queue

**Overview**:
Centralized queue for reviewing user KYC submissions. Integrates with third-party KYC providers (Sumsub, Onfido) but allows manual review and override for edge cases.

**KYC Review Queue**:

**Display Columns**:
- User ID
- User Name
- Email
- Country
- KYC Status (Pending, In Review, Verified, Rejected)
- Submission Date
- Assigned Reviewer (if any)
- Risk Level (Low, Medium, High) - auto-assigned by KYC provider
- Actions (Review, Approve, Reject)

**Filters**:
- Status: Pending, In Review, Verified, Rejected, All
- Submission Date Range: From - To
- Assigned Reviewer: Dropdown
- Risk Level: Low, Medium, High, All
- Country: Singapore, Hong Kong, UAE, Thailand, Malaysia, Indonesia, All
- KYC Provider: Sumsub, Onfido, All

**Sorting**:
- Sort by: Submission Date, Risk Level, Country
- Default: Submission Date (oldest first) + Risk Level (high first)

**Auto-Assignment**:
- Low Risk: Auto-approved by system (no manual review needed)
- Medium Risk: Auto-assigned to next available Compliance Officer
- High Risk: Auto-assigned to senior Compliance Officer + flagged for escalation

---

**KYC Review Page**:

**When admin clicks "Review" on a KYC submission, display:**

**Section 1: User Information**:
- Full Name: John Doe
- Email: john.doe@example.com
- Phone: +65 9123 4567
- Country: Singapore
- Registration Date: April 5, 2026
- Submission Date: April 6, 2026
- Risk Level: Medium (auto-assigned by Sumsub)
- Assigned Reviewer: Jane Smith

**Section 2: Identity Documents**:

**Document 1: ID Document (Passport, National ID, Driver's License)**:
- Document Type: Passport
- Document Number: E1234567 (partially masked for security)
- Issuing Country: Singapore
- Expiry Date: March 15, 2030
- Image: Front, Back (if applicable)
  - View Full Resolution (button) → Opens image in modal
  - Download (button) → Downloads image
- OCR Extracted Data:
  - Name: John Doe ✓ (matches user input)
  - Date of Birth: January 1, 1990 ✓
  - Document Number: E1234567 ✓
- Verification Status:
  - Document Authenticity: ✓ Passed (verified by Sumsub)
  - Face Match: ✓ Passed (selfie matches ID photo)
  - Expiry Date: ✓ Valid (not expired)

**Document 2: Proof of Address (Utility Bill, Bank Statement)**:
- Document Type: Utility Bill
- Issue Date: March 2026
- Address: 123 Main Street, Singapore 123456
- Image: Front
  - View Full Resolution (button)
  - Download (button)
- OCR Extracted Data:
  - Name: John Doe ✓
  - Address: 123 Main Street, Singapore 123456 ✓
- Verification Status:
  - Document Age: ✓ Passed (issued within 3 months)
  - Address Match: ✓ Passed (matches user input)

**Document 3: Selfie (Liveness Check)**:
- Image: Front (with liveness check indicators)
  - View Full Resolution (button)
  - Download (button)
- Liveness Check Results:
  - Real Person: ✓ Passed (not a photo of a photo)
  - Face Match: ✓ Passed (matches ID photo, 95% confidence)
  - Lighting: ✓ Good
  - Quality: ✓ High

---

**Section 3: Sanctions Screening**:

**Screening Results**:
- OFAC (US Office of Foreign Assets Control): ✓ No Match
- UN Sanctions List: ✓ No Match
- EU Sanctions List: ✓ No Match
- Singapore Monetary Authority: ✓ No Match
- Interpol Red Notices: ✓ No Match

**Potential Matches** (if any):
- Name: Similar Name (85% match)
- Details: Click to view details
- Action: Mark as False Positive / Escalate to Legal

---

**Section 4: AML Risk Assessment**:

**Risk Score**: 35/100 (Medium Risk)

**Risk Factors**:
- Country Risk: Low (Singapore is low-risk jurisdiction)
- IP Address: Singapore ✓ (matches declared country)
- Device Fingerprint: Desktop, Chrome, Windows ✓ (consistent)
- Transaction History: None (new user)
- Source of Funds: Not yet declared
- Politically Exposed Person (PEP): No ✓

**AI Risk Assessment** (from internal model):
- Fraud Probability: 5% (Low)
- Identity Theft Probability: 3% (Low)
- AML Risk: 12% (Medium, due to lack of transaction history)

---

**Section 5: Third-Party Verification** (Sumsub/Onfido):

**Sumsub Results**:
- Overall Verification Status: Review Required
- Review Reason: Address document needs manual verification
- Applicant ID: 5f3e2...9c1a (link to Sumsub dashboard)
- Verification Date: April 6, 2026
- Confidence Score: 85%

**Recommended Action**: Approve (system recommends approval based on 85% confidence)

---

**Section 6: Admin Review Checklist**:

**Reviewer must verify:**

**☐ Identity Document**:
- Document is clear and legible: Yes / No
- Document appears authentic (no signs of tampering): Yes / No
- Face in ID matches selfie: Yes / No
- Document not expired: Yes / No

**☐ Proof of Address**:
- Document is recent (within 3 months): Yes / No
- Address matches user input: Yes / No
- Document appears authentic: Yes / No

**☐ Selfie Liveness Check**:
- Real person (not a photo): Yes / No
- Face matches ID photo: Yes / No
- Lighting and quality acceptable: Yes / No

**☐ Sanctions Screening**:
- No sanctions matches: Yes / No
- All potential matches reviewed: Yes / No

**☐ AML Risk Assessment**:
- Risk level acceptable (Low or Medium): Yes / No
- High-risk factors reviewed and documented: Yes / No

---

**Review Decision**:

**Options**:
1. **Approve KYC**:
   - User KYC status: Verified
   - User can now invest
   - User notified via email + in-app notification

2. **Request Re-submission**:
   - Specify which documents need re-submission
   - Provide instructions to user (e.g., "Please upload a clearer image of your passport")
   - User receives email with instructions
   - User can re-upload documents

3. **Reject KYC**:
   - Requires reason (dropdown + text area):
     - Document Not Clear / Legible
     - Document Expired
     - Document Appears Fake / Tampered
     - Sanctions Hit
     - High AML Risk
     - Other (specify)
   - User notified via email
   - User account suspended (cannot invest)
   - User can dispute rejection (escalates to senior Compliance Officer)

**Actions**:
- Approve (button, green) → Approves KYC, logs to audit trail
- Request Re-submission (button, yellow) → Opens modal to specify what needs re-upload
- Reject (button, red) → Opens modal to specify reason
- Escalate to Senior Compliance Officer (button) → For complex cases
- Add Internal Note (button) → Visible only to admins

---

**Request Re-submission Modal**:

**Fields**:
- Documents to Re-submit (multi-select checkboxes):
  - ID Document (Front)
  - ID Document (Back)
  - Proof of Address
  - Selfie
- Instructions to User (required): Text area
  - Placeholder: "Please re-upload your passport. The current image is not clear. Ensure the photo is well-lit and all text is legible."
- Internal Notes (optional): Text area (visible only to admins)

**Actions**:
- Send Request (button) → Sends to user, changes KYC status to "Resubmission Requested"
- Cancel (button)

---

**Reject KYC Modal**:

**Fields**:
- Rejection Reason (required): Dropdown
  - Document Not Clear / Legible
  - Document Expired
  - Document Appears Fake / Tampered
  - Sanctions Hit (OFAC, UN, EU, etc.)
  - High AML Risk
  - Inconsistent Information
  - Other (specify)
- Detailed Explanation (required): Text area (visible to user)
- Internal Notes (optional): Text area (visible only to admins)
- Suspend Account: Yes / No (checkbox, default Yes)
- Blacklist User (for fraud): Yes / No (checkbox, Super Admin only)

**Warning**:
"This KYC submission will be rejected and the user will be notified. The user will not be able to invest until KYC is approved."

**Actions**:
- Confirm Rejection (button) → Rejects KYC, suspends account, notifies user
- Cancel (button)

---

**KYC Analytics Dashboard** (top of KYC Review Queue):

**Metrics Cards**:
- Pending Reviews: 23 submissions
- Avg Review Time: 18 hours (SLA: 24 hours) ✓
- Approval Rate: 92% (industry benchmark: 85-95%)
- Rejected KYC: 3 (3%)
- Resubmission Rate: 5% (5 of 100)

**Charts**:
- KYC Submissions Trend (line chart, last 12 months)
- Approval Rate by Country (bar chart)
- Rejection Reasons (pie chart)
- Review Time by Reviewer (bar chart, for performance tracking)

---

**SLA Monitoring**:

**Service Level Agreement**:
- Low Risk (auto-approved): Instant
- Medium Risk: 24 hours
- High Risk: 48 hours

**SLA Alerts**:
- Yellow Alert: 80% of SLA time elapsed (e.g., 19 hours of 24)
- Red Alert: SLA breached (overdue)
- Email notification to reviewer + supervisor

---

**Acceptance Criteria**:

- Admin can view all pending KYC submissions in queue
- Admin can filter, sort, and search submissions
- Admin can review KYC with complete checklist and documents
- Admin can view third-party verification results (Sumsub, Onfido)
- Admin can approve, request re-submission, or reject KYC
- User receives email notification of decision within 1 hour
- All KYC decisions logged to audit trail (who, what, when, why)
- SLA monitoring alerts reviewers of approaching deadlines
- KYC analytics dashboard displays key metrics
- Sanctions screening runs automatically for all submissions
- High-risk submissions auto-escalate to senior Compliance Officer
- Documents stored securely (encrypted at rest, access logged)

---

#### 4.5.4 Compliance Dashboard

**Overview**:
Centralized compliance monitoring and reporting dashboard. Provides real-time visibility into compliance metrics, audit logs, regulatory reports, and risk indicators.

**Dashboard Layout**:

**Top Metrics Row**:
- Total Users: 12,345
- KYC Verified Users: 9,123 (74%)
- Active Campaigns: 45
- Total Funds in Escrow: $12.5M USDC
- High-Risk Alerts: 3 (requires attention)

---

**Section 1: Real-Time Compliance Metrics**:

**Metrics Cards**:
- **KYC Compliance Rate**: 74% (target: >70%) ✓
  - Breakdown: Verified 74%, Pending 12%, Rejected 2%, Not Started 12%
- **AML Transaction Monitoring**: 1,234 transactions monitored today
  - Flagged for Review: 5 (0.4%)
  - False Positives: 3
  - Escalated: 2
- **Sanctions Screening Hit Rate**: 0.1% (12 hits in last 30 days)
  - False Positives: 11
  - True Positives: 1 (account suspended)
- **Regulatory Reporting Status**: All reports submitted on time ✓
  - Next Report Due: May 15, 2026 (MAS Quarterly Report)

**Charts**:
- KYC Verification Rate Trend (line chart, last 12 months)
- AML Alerts by Type (pie chart: Unusual Transaction Pattern, High-Value Transaction, Geographic Risk, etc.)
- Sanctions Hits by Country (bar chart)

---

**Section 2: Audit Log**:

**Display Columns**:
- Timestamp
- User (Admin who performed action)
- Action Type (User Created, KYC Approved, Campaign Approved, Account Suspended, etc.)
- Entity (User ID, Campaign ID, etc.)
- Details (brief description)
- IP Address
- Device

**Filters**:
- Date Range: Today, Last 7 Days, Last 30 Days, Custom Range
- Action Type: KYC Approved, Campaign Approved, Account Suspended, etc., All
- Admin User: Dropdown (list of all admins)

**Search**:
- Search by: Entity ID (User ID, Campaign ID), Admin Name, IP Address

**Export**:
- Export Audit Log: CSV, JSON, PDF
- Date Range: Custom
- Retention: 7 years (regulatory requirement)

**Audit Log Immutability**:
- All audit log entries are write-once (cannot be edited or deleted)
- Hash of each entry stored on-chain (Solana) for tamper-proof verification
- Monthly audit log hash published publicly

---

**Section 3: Regulatory Reports**:

**Available Reports**:

**1. MAS Quarterly Report** (Singapore):
- Report Type: Capital Markets Services License Holder Report
- Frequency: Quarterly (Q1, Q2, Q3, Q4)
- Last Submission: March 31, 2026 ✓
- Next Due: June 30, 2026
- Status: On Track
- Actions:
  - Download Last Report (PDF)
  - Generate Current Quarter Report (button)

**2. SFC Annual Report** (Hong Kong):
- Report Type: Type 1 License Holder Annual Report
- Frequency: Annual
- Last Submission: December 31, 2025 ✓
- Next Due: December 31, 2026
- Status: On Track
- Actions:
  - Download Last Report (PDF)
  - Generate Current Year Report (button)

**3. VARA Monthly Report** (UAE):
- Report Type: VASP Monthly Activity Report
- Frequency: Monthly
- Last Submission: March 31, 2026 ✓
- Next Due: April 30, 2026 (in 18 days)
- Status: On Track
- Actions:
  - Download Last Report (PDF)
  - Generate Current Month Report (button)

**4. AML/CFT Suspicious Activity Report (SAR)**:
- Report Type: Suspicious Transaction Report
- Frequency: As needed (when suspicious activity detected)
- Last Submission: None (no suspicious activity)
- Status: N/A
- Actions:
  - File SAR (button) → Opens SAR filing form

**Report Generation**:
- Auto-generated from platform data
- Includes: GMV, user growth, KYC stats, transaction volume, compliance metrics
- Downloadable formats: PDF, Excel, CSV
- Submit to regulator: Via email or API (if supported)

---

**Section 4: Risk Monitoring**:

**High-Risk Alerts** (requires immediate attention):

**Alert 1**:
- Type: Unusual Transaction Pattern
- User: John Doe (User ID: abc123)
- Details: Invested $50K in 5 campaigns within 1 hour (unusual for this user)
- Risk Score: 75/100 (High)
- Date: April 12, 2026, 10:30 AM
- Actions:
  - View User Profile (button)
  - Flag for AML Review (button)
  - Mark as False Positive (button)

**Alert 2**:
- Type: Sanctions Screening Hit
- User: Jane Smith (User ID: xyz789)
- Details: Potential match with OFAC sanctions list (85% name match)
- Risk Score: 90/100 (Critical)
- Date: April 12, 2026, 11:00 AM
- Actions:
  - View KYC Documents (button)
  - Suspend Account (button)
  - Escalate to Legal (button)
  - Mark as False Positive (button)

**Alert 3**:
- Type: High-Value Transaction
- User: ABC Company (Company ID: comp456)
- Details: Raised $1M in 24 hours (triggers enhanced due diligence)
- Risk Score: 60/100 (Medium)
- Date: April 12, 2026, 2:00 PM
- Actions:
  - View Campaign Details (button)
  - Request Additional Documents (button)
  - Approve (button, after review)

**Alert History**:
- View All Alerts (last 30 days)
- Filter by: Type, Risk Score, Status (Open, Closed, False Positive)
- Export: CSV

---

**Section 5: Compliance Policies**:

**Active Policies**:

**1. KYC/AML Policy**:
- Version: 2.1
- Last Updated: March 1, 2026
- Effective Date: March 15, 2026
- Status: Active
- Actions:
  - View Policy (PDF)
  - Edit Policy (Super Admin only)
  - View Change History

**2. Sanctions Screening Policy**:
- Version: 1.5
- Last Updated: February 1, 2026
- Effective Date: February 15, 2026
- Status: Active
- Actions:
  - View Policy (PDF)
  - Edit Policy (Super Admin only)

**3. Transaction Monitoring Policy**:
- Version: 1.3
- Last Updated: January 1, 2026
- Effective Date: January 15, 2026
- Status: Active
- Actions:
  - View Policy (PDF)
  - Edit Policy (Super Admin only)

**4. Data Retention Policy**:
- Version: 1.0
- Last Updated: December 1, 2025
- Effective Date: January 1, 2026
- Status: Active
- Retention Period: 7 years (transaction data), 3 years (marketing data)
- Actions:
  - View Policy (PDF)
  - Edit Policy (Super Admin only)

---

**Section 6: Compliance Team Performance**:

**Metrics by Compliance Officer**:

**Table**:
- Officer Name
- KYC Reviews Completed (last 30 days)
- Avg Review Time (hours)
- Approval Rate (%)
- Escalations
- Alerts Resolved

**Example**:
- Jane Smith: 45 reviews, 18 hours avg, 92% approval, 2 escalations, 10 alerts resolved
- John Doe: 38 reviews, 22 hours avg, 88% approval, 5 escalations, 8 alerts resolved

**Team Averages**:
- Avg Review Time: 20 hours (SLA: 24 hours) ✓
- Avg Approval Rate: 90%
- Total Alerts Resolved: 18 of 20 (90%)

---

**Section 7: Regulatory Calendar**:

**Upcoming Deadlines**:

**Table**:
- Date
- Report Type
- Regulator
- Jurisdiction
- Status (On Track, At Risk, Overdue)
- Actions

**Example**:
- April 30, 2026: VARA Monthly Report, VARA, UAE, On Track, Generate Report
- May 15, 2026: MAS Quarterly Report, MAS, Singapore, On Track, Generate Report
- June 30, 2026: SFC Semi-Annual Report, SFC, Hong Kong, On Track, Generate Report

**Calendar View**:
- Monthly calendar with all compliance deadlines highlighted
- Color-coded: Green (On Track), Yellow (At Risk), Red (Overdue)

---

**Acceptance Criteria**:

- Compliance dashboard displays real-time metrics
- Admin can view audit log with filters and search
- Audit log entries are immutable (write-once, hash stored on-chain)
- Admin can generate regulatory reports (auto-generated from data)
- High-risk alerts displayed with details and actions
- Admin can view and edit compliance policies (Super Admin only)
- Compliance team performance metrics displayed
- Regulatory calendar displays upcoming deadlines
- All data exports work (CSV, JSON, PDF)
- Dashboard loads in <3s with 1 year of data
- Role-based permissions enforced (Compliance Officer can view all, Finance Officer cannot)

---

**Section 4.5 Summary (Admin Panel)**:

Section 4.5 covers the comprehensive admin panel with 4 major subsections:

- **4.5.1**: User Management (view, edit, suspend, delete users with detailed profiles)
- **4.5.2**: Campaign Approval Workflow (review queue, checklist, approve/reject/request changes)
- **4.5.3**: KYC Review Queue (document verification, sanctions screening, approve/reject)
- **4.5.4**: Compliance Dashboard (real-time metrics, audit logs, regulatory reports, risk monitoring)

**Total lines added**: ~1,850 lines
**Estimated implementation time**: 10-12 weeks for all admin panel features

**Key Features**:
- Role-based access control (Super Admin, Compliance Officer, Campaign Reviewer, etc.)
- Immutable audit trail (all actions logged, hash stored on-chain)
- SLA monitoring (alerts for approaching deadlines)
- Regulatory compliance (MAS, SFC, VARA reporting)
- Risk-based workflows (auto-escalation for high-risk users/campaigns)

---

### 4.6 Smart Contract Features

Smart contracts are the backbone of Elevate Finance's tokenization and escrow infrastructure. Built on Solana using the Anchor framework, these contracts ensure trustless, transparent, and compliant management of tokenized securities and investor funds.

**Blockchain**: Solana (Phase 1), Ethereum & Sui (Phase 2+)
**Token Standard**: SPL Token-2022 (Solana), ERC-1400 (Ethereum)
**Development Framework**: Anchor (Rust)
**Networks**: Devnet → Testnet → Mainnet

---

#### 4.6.1 Token Issuance (SPL Token-2022)

**Overview**:
Each campaign issues a unique SPL Token-2022 representing fractional ownership of the tokenized asset. SPL Token-2022 provides advanced features like transfer hooks, metadata extensions, and built-in compliance mechanisms.

**Token Creation Flow**:

**Step 1: Campaign Approved**
- Admin approves campaign via Admin Panel (Section 4.5.2)
- Campaign status changes to "Approved" → "Preparing Launch"
- Backend triggers token creation process

**Step 2: Token Mint Initialization**
- Smart contract instruction: `initialize_mint()`
- Parameters:
  - Campaign ID (UUID)
  - Token name: `{Company Name} - {Campaign Title}`
  - Token symbol: Auto-generated (e.g., "ELEV-001")
  - Decimals: 6 (matches USDC for easy calculations)
  - Mint authority: Escrow Program PDA (Program Derived Address)
  - Freeze authority: Admin multi-sig (3-of-5)
- Token Extensions:
  - **Transfer Hook**: Whitelist verification (KYC check before transfer)
  - **Metadata Extension**: Campaign details, company info, legal docs URL
  - **Permanent Delegate**: Platform recovery key (emergency only)

**Step 3: Token Account Creation**
- Create Associated Token Accounts (ATAs) for:
  - Escrow vault (holds tokens until investors claim)
  - Company wallet (receives tokens for internal allocation, if any)
  - Reserve pool (for future issuance, if overfunding allowed)

**Step 4: Initial Token Supply Minting**
- Calculate total token supply:
  ```
  Total_supply = Funding_goal / Token_price

  Example:
  Funding_goal = $500,000 USDC
  Token_price = $1.00 USDC
  Total_supply = 500,000 tokens
  ```
- Mint tokens to escrow vault
- Tokens remain in escrow until investors purchase them

---

**Token Metadata Structure**:

```json
{
  "name": "GreenTech Solutions - Series A",
  "symbol": "ELEV-GT-001",
  "description": "Tokenized equity representing 20% ownership in GreenTech Solutions Pte Ltd",
  "image": "https://cdn.elevate-fi.com/campaigns/gt-001/logo.png",
  "external_url": "https://elevate-fi.com/campaigns/gt-001",
  "attributes": [
    {
      "trait_type": "Campaign ID",
      "value": "gt-001"
    },
    {
      "trait_type": "Company",
      "value": "GreenTech Solutions Pte Ltd"
    },
    {
      "trait_type": "Asset Type",
      "value": "Equity"
    },
    {
      "trait_type": "Equity Percentage",
      "value": "20%"
    },
    {
      "trait_type": "Pre-Money Valuation",
      "value": "$2,000,000 USD"
    },
    {
      "trait_type": "Funding Goal",
      "value": "$500,000 USDC"
    },
    {
      "trait_type": "Token Price",
      "value": "$1.00 USDC"
    },
    {
      "trait_type": "Lock-up Period",
      "value": "12 months"
    },
    {
      "trait_type": "Campaign Start",
      "value": "2026-04-15T00:00:00Z"
    },
    {
      "trait_type": "Campaign End",
      "value": "2026-06-14T23:59:59Z"
    },
    {
      "trait_type": "Jurisdiction",
      "value": "Singapore"
    },
    {
      "trait_type": "Legal Document Hash",
      "value": "0x3a5f2b8c9d1e4a6f7b8c9d0e1f2a3b4c5d6e7f8a9b0c1d2e3f4a5b6c7d8e9f0a"
    }
  ],
  "properties": {
    "files": [
      {
        "uri": "https://cdn.elevate-fi.com/campaigns/gt-001/prospectus.pdf",
        "type": "application/pdf"
      }
    ],
    "category": "security_token"
  }
}
```

---

**Transfer Hook (Whitelist Verification)**:

**Purpose**: Enforce KYC/AML compliance by restricting token transfers to verified investors only.

**Hook Logic**:
```rust
pub fn transfer_hook(
    ctx: Context<TransferHook>,
    amount: u64,
) -> Result<()> {
    let from = ctx.accounts.from.key();
    let to = ctx.accounts.to.key();
    let mint = ctx.accounts.mint.key();

    // 1. Check if "to" address is whitelisted
    let whitelist = &ctx.accounts.whitelist;
    require!(
        whitelist.is_whitelisted(&to, &mint),
        ErrorCode::RecipientNotWhitelisted
    );

    // 2. Check if lock-up period has expired (for "from" address)
    let lock_schedule = &ctx.accounts.lock_schedule;
    let current_time = Clock::get()?.unix_timestamp;
    require!(
        lock_schedule.unlock_timestamp <= current_time,
        ErrorCode::TokensStillLocked
    );

    // 3. Log transfer for audit trail
    emit!(TransferEvent {
        from,
        to,
        mint,
        amount,
        timestamp: current_time,
    });

    Ok(())
}
```

**Whitelist Management**:
- Admin adds investor to whitelist after KYC approval
- Instruction: `add_to_whitelist(investor_pubkey, mint_pubkey)`
- Only Admin multi-sig can add/remove from whitelist
- Whitelist is per-token (each campaign has its own whitelist)

---

**Token Minting During Investment**:

**When investor invests $1,000 USDC:**

1. Investor approves USDC transfer (via wallet)
2. Backend calls: `invest(campaign_id, amount_usdc)`
3. Smart contract:
   - Transfers $1,000 USDC from investor to escrow vault
   - Calculates tokens: `tokens = amount_usdc / token_price` → 1,000 tokens
   - Mints 1,000 tokens to investor's ATA
   - Creates lock schedule: `unlock_timestamp = current_time + 12 months`
   - Updates campaign state: `raised_amount += 1,000 USDC`, `investor_count++`
   - Emits `InvestmentEvent`

4. Investor now owns 1,000 tokens (visible in wallet, but locked for 12 months)

---

**Acceptance Criteria**:

- Each campaign issues a unique SPL Token-2022
- Token metadata includes campaign details, legal doc hash
- Transfer hook enforces whitelist + lock-up period
- Tokens minted to investors during investment flow
- Lock-up period enforced on-chain (12 months minimum)
- Admin can mint additional tokens if overfunding allowed (up to 150% of goal)
- All token operations logged to audit trail
- Token details queryable via RPC (for portfolio display)

---

#### 4.6.2 Escrow Management (3-of-5 Multi-Sig)

**Overview**:
All investor funds are held in a secure escrow vault managed by a 3-of-5 multi-signature account. Funds are released to the company only after milestone voting (investor approval) and multi-sig authorization (platform safeguard).

**Escrow Architecture**:

**Escrow Vault**:
- PDA (Program Derived Address) derived from: `["escrow", campaign_id]`
- Holds USDC deposited by investors
- Cannot be controlled by any single party
- Requires 3-of-5 signatures for fund release

**Multi-Sig Authorities** (5 signers):
1. Platform Treasury (cold wallet)
2. Platform Operations (hot wallet, daily operations)
3. Compliance Officer (oversight)
4. External Auditor (third-party verification)
5. Legal Counsel (regulatory compliance)

**Threshold**: 3-of-5 signatures required for any fund release

---

**Escrow Initialization**:

**When campaign goes live:**

```rust
pub fn initialize_escrow(
    ctx: Context<InitializeEscrow>,
    campaign_id: [u8; 32],
    goal_amount: u64,
    end_timestamp: i64,
) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;

    escrow.campaign_id = campaign_id;
    escrow.authority = ctx.accounts.escrow_authority.key();
    escrow.usdc_vault = ctx.accounts.usdc_vault.key();
    escrow.goal_amount = goal_amount;
    escrow.end_timestamp = end_timestamp;
    escrow.total_deposited = 0;
    escrow.total_released = 0;
    escrow.total_refunded = 0;
    escrow.status = EscrowStatus::Active;

    // Set multi-sig configuration
    escrow.multisig_threshold = 3;
    escrow.multisig_signers = vec![
        ctx.accounts.signer_1.key(),
        ctx.accounts.signer_2.key(),
        ctx.accounts.signer_3.key(),
        ctx.accounts.signer_4.key(),
        ctx.accounts.signer_5.key(),
    ];

    Ok(())
}
```

---

**Deposit Flow** (when investor invests):

```rust
pub fn deposit(
    ctx: Context<Deposit>,
    amount: u64,
) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;

    // 1. Transfer USDC from investor to escrow vault
    token::transfer(
        CpiContext::new(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.investor_usdc.to_account_info(),
                to: ctx.accounts.escrow_vault.to_account_info(),
                authority: ctx.accounts.investor.to_account_info(),
            },
        ),
        amount,
    )?;

    // 2. Update escrow state
    escrow.total_deposited += amount;

    // 3. Check if goal reached
    if escrow.total_deposited >= escrow.goal_amount {
        escrow.status = EscrowStatus::Funded;
        emit!(CampaignFundedEvent {
            campaign_id: escrow.campaign_id,
            total_raised: escrow.total_deposited,
        });
    }

    // 4. Emit deposit event
    emit!(DepositEvent {
        campaign_id: escrow.campaign_id,
        investor: ctx.accounts.investor.key(),
        amount,
        timestamp: Clock::get()?.unix_timestamp,
    });

    Ok(())
}
```

---

**Milestone-Based Fund Release**:

**Milestone Voting Process**:

1. **Company proposes milestone**: "Product Development Phase 1 Complete"
2. **Backend calls**: `propose_release(campaign_id, milestone_id, amount, evidence_url)`
3. **Investors vote**: Yes / No (weighted by token ownership)
4. **Voting period**: 7 days
5. **Approval threshold**: >50% of token holders vote "Yes"
6. **If approved**: Multi-sig signers receive notification to review and sign

**Multi-Sig Release Flow**:

```rust
pub fn propose_release(
    ctx: Context<ProposeRelease>,
    milestone_id: u64,
    amount: u64,
    recipient: Pubkey,
) -> Result<()> {
    let release_proposal = &mut ctx.accounts.release_proposal;

    release_proposal.escrow = ctx.accounts.escrow.key();
    release_proposal.milestone_id = milestone_id;
    release_proposal.amount = amount;
    release_proposal.recipient = recipient;
    release_proposal.proposer = ctx.accounts.proposer.key();
    release_proposal.proposed_at = Clock::get()?.unix_timestamp;
    release_proposal.signatures = vec![]; // Empty initially
    release_proposal.executed = false;

    emit!(ReleaseProposedEvent {
        campaign_id: ctx.accounts.escrow.campaign_id,
        milestone_id,
        amount,
    });

    Ok(())
}

pub fn sign_release(
    ctx: Context<SignRelease>,
) -> Result<()> {
    let release_proposal = &mut ctx.accounts.release_proposal;
    let signer = ctx.accounts.signer.key();

    // 1. Verify signer is authorized
    let escrow = &ctx.accounts.escrow;
    require!(
        escrow.multisig_signers.contains(&signer),
        ErrorCode::UnauthorizedSigner
    );

    // 2. Check if already signed
    require!(
        !release_proposal.signatures.contains(&signer),
        ErrorCode::AlreadySigned
    );

    // 3. Add signature
    release_proposal.signatures.push(signer);

    // 4. Check if threshold reached
    if release_proposal.signatures.len() >= escrow.multisig_threshold as usize {
        // Execute release
        release_funds(ctx)?;
        release_proposal.executed = true;
    }

    emit!(ReleaseSignedEvent {
        signer,
        signatures_count: release_proposal.signatures.len() as u8,
        threshold: escrow.multisig_threshold,
    });

    Ok(())
}

fn release_funds(ctx: Context<SignRelease>) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;
    let release_proposal = &ctx.accounts.release_proposal;

    // 1. Calculate platform fee (2%)
    let gross_amount = release_proposal.amount;
    let platform_fee = gross_amount * 2 / 100; // 2% fee
    let net_amount = gross_amount - platform_fee;

    // 2. Transfer net amount to company
    token::transfer(
        CpiContext::new_with_signer(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.escrow_vault.to_account_info(),
                to: ctx.accounts.company_usdc.to_account_info(),
                authority: ctx.accounts.escrow_authority.to_account_info(),
            },
            &[&[
                b"escrow_authority",
                &escrow.campaign_id,
                &[ctx.bumps.escrow_authority],
            ]],
        ),
        net_amount,
    )?;

    // 3. Transfer platform fee to treasury
    token::transfer(
        CpiContext::new_with_signer(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.escrow_vault.to_account_info(),
                to: ctx.accounts.platform_treasury.to_account_info(),
                authority: ctx.accounts.escrow_authority.to_account_info(),
            },
            &[&[
                b"escrow_authority",
                &escrow.campaign_id,
                &[ctx.bumps.escrow_authority],
            ]],
        ),
        platform_fee,
    )?;

    // 4. Update escrow state
    escrow.total_released += gross_amount;

    // 5. Emit event
    emit!(FundsReleasedEvent {
        campaign_id: escrow.campaign_id,
        milestone_id: release_proposal.milestone_id,
        gross_amount,
        net_amount,
        platform_fee,
        recipient: release_proposal.recipient,
    });

    Ok(())
}
```

---

**Refund Flow** (if campaign fails to reach goal):

```rust
pub fn refund(
    ctx: Context<Refund>,
) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;
    let investment = &ctx.accounts.investment;

    // 1. Verify campaign failed
    let current_time = Clock::get()?.unix_timestamp;
    require!(
        current_time > escrow.end_timestamp,
        ErrorCode::CampaignStillActive
    );
    require!(
        escrow.total_deposited < escrow.goal_amount,
        ErrorCode::CampaignSucceeded
    );

    // 2. Calculate refund amount (investor's original investment)
    let refund_amount = investment.amount_usdc;

    // 3. Transfer USDC back to investor
    token::transfer(
        CpiContext::new_with_signer(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.escrow_vault.to_account_info(),
                to: ctx.accounts.investor_usdc.to_account_info(),
                authority: ctx.accounts.escrow_authority.to_account_info(),
            },
            &[&[
                b"escrow_authority",
                &escrow.campaign_id,
                &[ctx.bumps.escrow_authority],
            ]],
        ),
        refund_amount,
    )?;

    // 4. Burn investor's tokens (no longer valid)
    token::burn(
        CpiContext::new(
            ctx.accounts.token_program.to_account_info(),
            token::Burn {
                mint: ctx.accounts.mint.to_account_info(),
                from: ctx.accounts.investor_token.to_account_info(),
                authority: ctx.accounts.investor.to_account_info(),
            },
        ),
        investment.tokens_received,
    )?;

    // 5. Update escrow state
    escrow.total_refunded += refund_amount;

    // 6. Mark investment as refunded
    let investment = &mut ctx.accounts.investment;
    investment.refunded = true;

    // 7. Emit event
    emit!(RefundEvent {
        campaign_id: escrow.campaign_id,
        investor: ctx.accounts.investor.key(),
        amount: refund_amount,
    });

    Ok(())
}
```

---

**Emergency Pause Mechanism**:

**Purpose**: Halt all escrow operations in case of security threat, regulatory order, or critical bug.

```rust
pub fn pause_escrow(
    ctx: Context<PauseEscrow>,
) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;

    // Only admin multi-sig can pause
    require!(
        ctx.accounts.admin.key() == escrow.multisig_signers[0] ||
        ctx.accounts.admin.key() == escrow.multisig_signers[1],
        ErrorCode::Unauthorized
    );

    escrow.status = EscrowStatus::Paused;

    emit!(EscrowPausedEvent {
        campaign_id: escrow.campaign_id,
        paused_by: ctx.accounts.admin.key(),
        timestamp: Clock::get()?.unix_timestamp,
    });

    Ok(())
}

pub fn unpause_escrow(
    ctx: Context<UnpauseEscrow>,
) -> Result<()> {
    let escrow = &mut ctx.accounts.escrow;

    // Requires 3-of-5 multi-sig to unpause
    require!(
        ctx.accounts.multisig_signers.len() >= 3,
        ErrorCode::InsufficientSignatures
    );

    escrow.status = EscrowStatus::Active;

    emit!(EscrowUnpausedEvent {
        campaign_id: escrow.campaign_id,
        timestamp: Clock::get()?.unix_timestamp,
    });

    Ok(())
}
```

**Effects of Pause**:
- No deposits allowed
- No fund releases allowed
- Refunds still allowed (investor protection)
- Admin can investigate and resolve issue

---

**Acceptance Criteria**:

- All investor funds held in escrow vault (PDA-controlled)
- 3-of-5 multi-sig required for fund releases
- Milestone voting by investors before fund release
- Platform fee (2%) auto-deducted during fund release
- Automatic refunds if campaign fails to reach goal
- Emergency pause mechanism (admin-controlled, multi-sig to unpause)
- All escrow operations logged to audit trail
- Escrow state queryable via RPC

---

#### 4.6.3 Distribution Program (Profit Sharing)

**Overview**:
After campaign funding, companies can distribute profits, dividends, or revenue shares to token holders on a quarterly basis. All distributions are pro-rata based on token ownership and paid in the same stablecoin as the original investment.

**Distribution Frequency**: Quarterly (March 31, June 30, Sept 30, Dec 31)
**Distribution Currency**: USDC (same as investment)
**Distribution Method**: Pull-based (investors claim their share)

---

**Distribution Creation**:

**When company schedules a distribution:**

```rust
pub fn schedule_distribution(
    ctx: Context<ScheduleDistribution>,
    distribution_id: u64,
    total_amount: u64,
    distribution_date: i64,
) -> Result<()> {
    let distribution = &mut ctx.accounts.distribution;
    let campaign = &ctx.accounts.campaign;

    // 1. Verify caller is company
    require!(
        ctx.accounts.company.key() == campaign.company_pubkey,
        ErrorCode::Unauthorized
    );

    // 2. Initialize distribution
    distribution.campaign_id = campaign.campaign_id;
    distribution.distribution_id = distribution_id;
    distribution.total_amount = total_amount;
    distribution.distribution_date = distribution_date;
    distribution.claimed_count = 0;
    distribution.total_claimed = 0;

    // 3. Calculate amount per token (pro-rata)
    let total_supply = campaign.tokens_issued;
    distribution.amount_per_token = (total_amount * 1_000_000) / total_supply; // Scaled by 1M for precision

    // 4. Transfer USDC from company to distribution pool
    token::transfer(
        CpiContext::new(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.company_usdc.to_account_info(),
                to: ctx.accounts.distribution_pool.to_account_info(),
                authority: ctx.accounts.company.to_account_info(),
            },
        ),
        total_amount,
    )?;

    // 5. Emit event
    emit!(DistributionScheduledEvent {
        campaign_id: campaign.campaign_id,
        distribution_id,
        total_amount,
        distribution_date,
        amount_per_token: distribution.amount_per_token,
    });

    Ok(())
}
```

---

**Distribution Claim Flow**:

**When investor claims their distribution:**

```rust
pub fn claim_distribution(
    ctx: Context<ClaimDistribution>,
) -> Result<()> {
    let distribution = &mut ctx.accounts.distribution;
    let claim_record = &mut ctx.accounts.claim_record;

    // 1. Check if already claimed
    require!(
        !claim_record.claimed,
        ErrorCode::AlreadyClaimed
    );

    // 2. Check if distribution date has passed
    let current_time = Clock::get()?.unix_timestamp;
    require!(
        current_time >= distribution.distribution_date,
        ErrorCode::DistributionNotYetAvailable
    );

    // 3. Get investor's token balance
    let investor_balance = ctx.accounts.investor_token.amount;

    // 4. Calculate distribution amount
    let amount_to_claim = (investor_balance * distribution.amount_per_token) / 1_000_000;

    // 5. Transfer USDC from distribution pool to investor
    token::transfer(
        CpiContext::new_with_signer(
            ctx.accounts.token_program.to_account_info(),
            token::Transfer {
                from: ctx.accounts.distribution_pool.to_account_info(),
                to: ctx.accounts.investor_usdc.to_account_info(),
                authority: ctx.accounts.distribution_authority.to_account_info(),
            },
            &[&[
                b"distribution_authority",
                &distribution.campaign_id,
                &distribution.distribution_id.to_le_bytes(),
                &[ctx.bumps.distribution_authority],
            ]],
        ),
        amount_to_claim,
    )?;

    // 6. Mark as claimed
    claim_record.claimed = true;
    claim_record.claimed_at = current_time;
    claim_record.amount_claimed = amount_to_claim;

    // 7. Update distribution state
    distribution.claimed_count += 1;
    distribution.total_claimed += amount_to_claim;

    // 8. Emit event
    emit!(DistributionClaimedEvent {
        campaign_id: distribution.campaign_id,
        distribution_id: distribution.distribution_id,
        investor: ctx.accounts.investor.key(),
        amount: amount_to_claim,
        investor_balance,
    });

    Ok(())
}
```

---

**Automatic Distribution (Optional, Phase 2)**:

For better UX, platform can implement automatic push-based distributions:

- Instead of investors claiming, contract automatically sends distributions
- Requires cranking service to iterate through all token holders
- More gas-expensive but better UX
- Implementation: Off-chain service queries all token holders, submits batch transactions

---

**Distribution History & Tracking**:

**Investor can query:**
- Upcoming distributions (scheduled but not yet claimable)
- Claimable distributions (distribution date passed, not yet claimed)
- Claimed distributions (historical record)

**Company can query:**
- Total distributions scheduled
- Total amount distributed
- Claim rate (% of investors who claimed)
- Unclaimed amount (after 90 days, can be reclaimed by company)

---

**Acceptance Criteria**:

- Company can schedule quarterly distributions (USDC only)
- Distribution amount calculated pro-rata based on token ownership
- Investors can claim their share after distribution date
- Claim records prevent double-claiming
- Distribution history queryable via RPC
- Unclaimed distributions can be reclaimed by company after 90 days
- All distributions logged to audit trail
- Frontend displays upcoming, claimable, and claimed distributions (Section 4.3.7)

---

**Section 4.6 Summary (Smart Contract Features)**:

Section 4.6 covers the complete blockchain infrastructure with 3 major subsections:

- **4.6.1**: Token Issuance (SPL Token-2022 with transfer hooks, whitelist, lock-up enforcement)
- **4.6.2**: Escrow Management (3-of-5 multi-sig, milestone-based releases, automatic refunds)
- **4.6.3**: Distribution Program (quarterly profit sharing, pro-rata calculations, claim mechanism)

**Total lines added**: ~1,200 lines
**Estimated implementation time**: 12-16 weeks for all smart contract features (includes audits)

**Key Features**:
- Trustless escrow (no single party controls funds)
- Compliance-enforced transfers (KYC whitelist + lock-up)
- Transparent fund releases (multi-sig + milestone voting)
- Automated refunds (if campaign fails)
- Profit sharing (quarterly distributions)
- Emergency pause (security safeguard)

**Security Measures**:
- External audit required before Mainnet deployment
- Multi-sig for all critical operations
- Time-locked upgrades (7-day delay)
- Comprehensive test coverage (unit + integration tests)
- Bug bounty program ($50K-$500K rewards)

---

### 4.7 Payment & Treasury

The Payment & Treasury system enables seamless onboarding of both crypto-native and traditional investors through multiple payment methods. It handles stablecoin deposits, fiat on-ramps, wallet connections, transaction tracking, and automated fee calculations.

**Supported Payment Methods**:
- Stablecoins: USDC, USDT (Solana SPL tokens)
- Credit/Debit Cards: Stripe
- Bank Transfers: Transak (Asia-focused)
- Crypto On-Ramp: MoonPay (global)
- Wallet Direct Transfer: Phantom, Solflare, Ledger, MetaMask

---

#### 4.7.1 Stablecoin Deposits

**Overview**:
Crypto-native investors can invest directly using USDC or USDT held in their Solana wallets. This is the fastest, cheapest, and most seamless payment method.

**Supported Stablecoins**:
- **USDC (Primary)**: USD Coin (SPL Token)
  - Mint Address: `EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v`
  - Issuer: Circle
  - Decimals: 6
- **USDT (Secondary)**: Tether USD (SPL Token)
  - Mint Address: `Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB`
  - Issuer: Tether
  - Decimals: 6

**Why USDC/USDT?**:
- Price stability (1:1 peg to USD)
- Widely available on exchanges
- Low transfer fees on Solana (~$0.00025)
- Fast finality (400ms)
- Regulatory clarity (Circle is regulated)

---

**Direct Wallet Investment Flow**:

**Step 1: Investor Connects Wallet**
- User clicks "Invest" on campaign page
- WalletConnect modal opens
- User selects wallet: Phantom, Solflare, Backpack, Ledger
- Wallet prompts for connection approval
- User approves connection
- Frontend receives wallet public key

**Step 2: Select Investment Amount**
- User enters amount: e.g., $1,000 USDC
- Frontend displays:
  - Investment amount: $1,000 USDC
  - Platform fee: $0 (fee deducted at escrow release, not at investment)
  - Tokens to receive: 1,000 tokens (if token price = $1.00)
  - Lock-up period: 12 months (unlock date displayed)
- User clicks "Confirm Investment"

**Step 3: Check Wallet Balance**
```typescript
// Frontend checks if user has sufficient USDC
const usdcMint = new PublicKey('EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v');
const userUsdcAccount = await getAssociatedTokenAddress(
  usdcMint,
  wallet.publicKey
);

const balance = await connection.getTokenAccountBalance(userUsdcAccount);
const balanceUsdc = balance.value.uiAmount;

if (balanceUsdc < investmentAmount) {
  // Show error: "Insufficient USDC balance"
  // Offer: "Buy USDC with card" (redirect to fiat on-ramp)
  return;
}
```

**Step 4: Create & Send Transaction**
```typescript
// Backend prepares transaction
const transaction = await program.methods
  .invest(
    campaignId,
    new BN(investmentAmount * 1_000_000) // Convert to lamports (6 decimals)
  )
  .accounts({
    investor: wallet.publicKey,
    investorUsdc: userUsdcAccount,
    escrow: escrowPda,
    escrowVault: escrowVaultPda,
    mint: campaignMintPda,
    investorToken: investorTokenAccount,
    campaign: campaignPda,
    tokenProgram: TOKEN_PROGRAM_ID,
    systemProgram: SystemProgram.programId,
  })
  .transaction();

// Frontend sends transaction to wallet for signing
const signedTx = await wallet.signTransaction(transaction);
const txSignature = await connection.sendRawTransaction(signedTx.serialize());

// Wait for confirmation (400ms average on Solana)
await connection.confirmTransaction(txSignature, 'confirmed');
```

**Step 5: Transaction Confirmed**
- Smart contract executes (Section 4.6.2 Deposit Flow):
  - Transfers USDC from investor to escrow
  - Mints tokens to investor
  - Creates lock schedule
  - Updates campaign state
- Frontend shows success message:
  - "Investment successful! ✓"
  - Transaction hash (link to Solscan)
  - Tokens received: 1,000 tokens
  - Unlock date: April 15, 2027
- Email confirmation sent to investor
- Investment appears in portfolio (Section 4.3.5)

---

**Error Handling**:

**Insufficient Balance**:
- Error: "Insufficient USDC balance. You have $500 USDC but need $1,000 USDC."
- Solution: Offer "Buy USDC" button → Redirect to fiat on-ramp (Section 4.7.2)

**Wallet Not Connected**:
- Error: "Please connect your wallet first."
- Solution: Show WalletConnect modal

**Transaction Failed**:
- Error: "Transaction failed. Please try again."
- Reason: User rejected signature, network timeout, insufficient SOL for gas
- Solution: Show detailed error message, retry button

**Campaign Ended**:
- Error: "This campaign has ended. Investments are no longer accepted."
- Solution: Disable "Invest" button, show campaign status

**KYC Not Verified**:
- Error: "Please complete KYC verification before investing."
- Solution: Redirect to KYC flow (Section 4.1)

---

**Acceptance Criteria**:

- Investor can connect wallet (Phantom, Solflare, Ledger, Backpack)
- Investor can invest using USDC or USDT
- Balance check before transaction submission
- Transaction confirmation within 5 seconds (p95)
- Clear error messages for all failure cases
- Investment immediately visible in portfolio
- Email confirmation sent within 1 minute
- Transaction hash displayed (link to block explorer)

---

#### 4.7.2 Fiat On-Ramp Integration

**Overview**:
Traditional investors without crypto can purchase USDC directly using credit/debit cards or bank transfers. The platform integrates three fiat on-ramp providers for optimal coverage and conversion rates.

**Supported On-Ramps**:
1. **Stripe** (Credit/Debit Cards) - Global, best for small amounts ($100-$10K)
2. **Transak** (Bank Transfers) - Asia-focused, best for large amounts ($10K-$500K)
3. **MoonPay** (Credit Cards + Bank) - Global backup, widest currency support

---

**On-Ramp Selection Logic**:

```typescript
function selectOnRamp(amount: number, country: string, paymentMethod: string) {
  // Priority 1: Stripe for cards globally
  if (paymentMethod === 'card' && amount <= 10_000) {
    return 'stripe';
  }

  // Priority 2: Transak for Asia bank transfers
  if (paymentMethod === 'bank' && ASIA_COUNTRIES.includes(country)) {
    return 'transak';
  }

  // Priority 3: MoonPay as fallback
  return 'moonpay';
}
```

---

**Stripe Integration (Credit/Debit Cards)**:

**Use Case**: Investor wants to invest $1,000 but has no USDC

**Flow**:

1. **Investor clicks "Buy USDC"**
   - Modal opens: "Purchase USDC with Card"
   - Input: Amount in USD (e.g., $1,000)
   - Display:
     - USDC to receive: ~998 USDC (after 0.2% Stripe fee)
     - Total charge: $1,000 USD
     - Estimated time: 2-5 minutes

2. **Stripe Checkout**
   ```typescript
   // Backend creates Stripe Checkout session
   const session = await stripe.checkout.sessions.create({
     payment_method_types: ['card'],
     mode: 'payment',
     line_items: [{
       price_data: {
         currency: 'usd',
         product_data: {
           name: 'USDC Purchase',
           description: 'USDC for campaign investment',
         },
         unit_amount: 100000, // $1,000.00 in cents
       },
       quantity: 1,
     }],
     success_url: `${BASE_URL}/payment/success?session_id={CHECKOUT_SESSION_ID}`,
     cancel_url: `${BASE_URL}/payment/cancel`,
     metadata: {
       user_id: userId,
       wallet_address: walletAddress,
       usdc_amount: 998, // After fees
     },
   });

   // Redirect to Stripe Checkout
   window.location.href = session.url;
   ```

3. **User Completes Payment**
   - Stripe processes card payment
   - Stripe webhook notifies backend: `checkout.session.completed`

4. **Backend Mints USDC**
   ```typescript
   // Backend receives Stripe webhook
   async function handleStripeWebhook(event: Stripe.Event) {
     if (event.type === 'checkout.session.completed') {
       const session = event.data.object;
       const { wallet_address, usdc_amount } = session.metadata;

       // Purchase USDC from Circle (API)
       const circleTx = await circle.transfers.create({
         source: { type: 'wire', id: stripePaymentIntentId },
         destination: { type: 'blockchain', address: PLATFORM_USDC_WALLET },
         amount: { amount: usdc_amount, currency: 'USD' },
       });

       // Transfer USDC to user's wallet
       await transferUsdc(PLATFORM_USDC_WALLET, wallet_address, usdc_amount);

       // Notify user
       await sendEmail(user.email, 'USDC purchased successfully!');
     }
   }
   ```

5. **User Redirected to Success Page**
   - Message: "Payment successful! Your USDC will arrive in 2-5 minutes."
   - Show transaction status: "Processing..." → "Complete ✓"
   - Auto-redirect to investment flow after USDC arrives

**Fees**:
- Stripe: 2.9% + $0.30 per transaction
- Circle: 0.2% USDC purchase fee
- **Total**: ~3.1% + $0.30

**Limits**:
- Min: $100 USD
- Max: $10,000 USD per transaction
- Daily limit: $50,000 USD per user

---

**Transak Integration (Bank Transfers - Asia)**:

**Use Case**: Singapore investor wants to invest $50,000 via bank transfer

**Flow**:

1. **Investor clicks "Buy USDC with Bank Transfer"**
   - Transak widget opens (embedded iframe)
   - User selects:
     - Fiat currency: SGD
     - Amount: $50,000 SGD (~$37,000 USD)
     - Crypto: USDC (Solana)
     - Payment method: Bank Transfer

2. **Transak KYC** (if not completed):
   - User uploads ID, selfie (same as platform KYC)
   - Transak verifies in real-time (~2 minutes)
   - If user already completed platform KYC, Transak can skip (API integration)

3. **Bank Transfer Instructions**:
   - Transak displays:
     - Bank account name: Transak Singapore Pte Ltd
     - Bank: DBS Bank
     - Account number: 123-456-789
     - Reference code: TRX-XYZ123 (unique per transaction)
     - Amount: $50,000 SGD
   - User initiates bank transfer via online banking
   - Transfer takes 1-2 business days (FAST in Singapore = same day)

4. **Transak Receives Payment**:
   - Transak detects incoming bank transfer
   - Transak webhook notifies backend: `ORDER_COMPLETED`

5. **Backend Receives USDC**:
   ```typescript
   async function handleTransakWebhook(event: TransakWebhook) {
     if (event.status === 'COMPLETED') {
       const { wallet_address, crypto_amount } = event.data;

       // Transak already sent USDC to user's wallet
       // Backend just records transaction
       await db.transactions.create({
         user_id: event.user_id,
         type: 'fiat_onramp',
         provider: 'transak',
         fiat_amount: event.fiat_amount,
         crypto_amount: crypto_amount,
         status: 'completed',
       });

       // Notify user
       await sendEmail(user.email, 'Bank transfer received! USDC is in your wallet.');
     }
   }
   ```

**Fees**:
- Transak: 0.99% for bank transfers
- Bank transfer fee: $0-$25 (varies by bank)
- **Total**: ~0.99% + bank fee

**Limits**:
- Min: $1,000 USD
- Max: $500,000 USD per transaction
- Daily limit: $1,000,000 USD per user (after enhanced KYC)

---

**MoonPay Integration (Global Fallback)**:

**Use Case**: Investor from Indonesia wants to invest using Rupiah (IDR)

**Flow**:

1. **MoonPay Widget**:
   ```typescript
   // Embed MoonPay widget
   const moonPay = new MoonPaySDK({
     apiKey: MOONPAY_API_KEY,
     environment: 'production',
     params: {
       currencyCode: 'USDC_SOLANA',
       baseCurrencyCode: 'IDR',
       baseCurrencyAmount: 15_000_000, // 15M IDR ≈ $1,000 USD
       walletAddress: wallet.publicKey.toString(),
       colorCode: '#3B82F6', // Brand color
     },
   });

   moonPay.show();
   ```

2. **User Completes Purchase**:
   - MoonPay handles KYC, payment, USDC delivery
   - USDC sent directly to user's wallet
   - MoonPay webhook notifies backend

**Fees**:
- MoonPay: 4.5% (higher than competitors)
- **Use only as fallback** when Stripe/Transak unavailable

---

**On-Ramp Comparison Table** (displayed to user):

| Provider | Payment Method | Fees | Time | Limits |
|----------|---------------|------|------|--------|
| **Stripe** | Credit/Debit Card | 3.1% | 2-5 min | $100 - $10K |
| **Transak** | Bank Transfer | 0.99% | 1-2 days | $1K - $500K |
| **MoonPay** | Card/Bank | 4.5% | 5-30 min | $50 - $20K |

**Recommendation Logic**:
- **Small amount (<$10K) + Need speed**: Stripe
- **Large amount (>$10K) + Low fees**: Transak
- **Unsupported country**: MoonPay

---

**Acceptance Criteria**:

- User can purchase USDC with credit/debit card (Stripe)
- User can purchase USDC with bank transfer (Transak - Asia)
- User can purchase USDC with MoonPay (global fallback)
- On-ramp provider auto-selected based on amount, country, payment method
- USDC arrives in user's wallet within stated timeframe
- Transaction status tracking (Processing → Complete)
- Email notification when USDC arrives
- Failed payments show clear error message + retry option
- All fiat transactions logged to database
- Compliance: Source of funds tracked for AML

---

#### 4.7.3 Wallet Connection & Management

**Overview**:
Secure wallet connection using WalletConnect protocol and Solana Wallet Adapter. Supports hardware wallets for enhanced security.

**Supported Wallets**:
- **Phantom** (Primary, most popular)
- **Solflare** (Mobile-friendly)
- **Backpack** (Multi-chain)
- **Ledger** (Hardware wallet, highest security)
- **Trezor** (Hardware wallet)
- **MetaMask** (via Snaps, future for Ethereum support)

---

**Wallet Connection Flow**:

**Step 1: User Clicks "Connect Wallet"**
```typescript
// Frontend component
import { WalletMultiButton } from '@solana/wallet-adapter-react-ui';

function ConnectWalletButton() {
  return <WalletMultiButton />;
}
```

**Step 2: Wallet Selector Modal Opens**
- Display all supported wallets
- Auto-detect installed wallets (highlight available)
- Show "Not installed?" link for each wallet (redirects to install page)

**Step 3: User Selects Wallet**
- User clicks "Phantom" (example)
- Phantom extension opens
- Phantom asks: "Connect to elevate-fi.com?"
- User clicks "Connect"

**Step 4: Connection Established**
```typescript
// Frontend receives wallet connection event
import { useWallet } from '@solana/wallet-adapter-react';

function MyComponent() {
  const { publicKey, connected, connecting } = useWallet();

  useEffect(() => {
    if (connected && publicKey) {
      // Save wallet address to backend
      await api.post('/users/wallet', {
        wallet_address: publicKey.toString(),
      });

      // Check if wallet is whitelisted (KYC verified)
      const whitelisted = await checkWhitelist(publicKey);
      if (!whitelisted) {
        toast.error('Please complete KYC verification first');
      }
    }
  }, [connected, publicKey]);
}
```

**Step 5: Wallet Connected**
- User sees: Wallet address (truncated): `5Xw8...9Kp2`
- Display: USDC balance, SOL balance (for gas)
- Show: "Disconnect Wallet" button

---

**Multiple Wallet Support**:

**Use Case**: User wants to invest from multiple wallets

```typescript
// Backend: Associate multiple wallets with one user
const userWallets = await db.user_wallets.findMany({
  where: { user_id: userId },
});

// Each wallet must complete KYC separately (regulatory requirement)
for (const wallet of userWallets) {
  if (!wallet.kyc_verified) {
    console.log(`Wallet ${wallet.address} needs KYC`);
  }
}
```

**Frontend**: Show wallet selector dropdown
- Primary wallet: `5Xw8...9Kp2` (default)
- Secondary wallet: `7Yz9...3Lm1`
- Button: "Add Another Wallet"

---

**Hardware Wallet Support (Ledger)**:

**Why Hardware Wallets?**:
- Highest security (private keys never leave device)
- Required for institutional investors
- Protects against phishing, malware

**Ledger Connection Flow**:

1. User selects "Ledger" from wallet list
2. Prompt: "Connect your Ledger device"
3. User connects Ledger via USB
4. Ledger shows: "Open Solana app"
5. User opens Solana app on Ledger
6. Frontend sends connection request
7. Ledger shows: "Allow connection to elevate-fi.com?"
8. User approves on device (physical button press)
9. Connection established

**Transaction Signing with Ledger**:
- User initiates investment
- Ledger shows transaction details on screen:
  - "Transfer 1,000 USDC"
  - "To: escrow_vault_address"
  - "Fee: 0.00025 SOL"
- User reviews on device
- User approves by pressing button
- Transaction signed and submitted

---

**Wallet Security Features**:

**Auto-Logout**:
- Wallet disconnects after 30 minutes of inactivity
- User must reconnect to perform transactions
- Session persists for viewing (read-only)

**Transaction Simulation**:
```typescript
// Before sending transaction, simulate it
const simulation = await connection.simulateTransaction(transaction);

if (simulation.value.err) {
  // Show error: "Transaction would fail. Reason: ..."
  // Don't send transaction
  return;
}

// Simulation succeeded, proceed with signing
const signature = await wallet.signTransaction(transaction);
```

**Phishing Protection**:
- Display domain in wallet: "elevate-fi.com"
- Warn if domain doesn't match: "⚠️ This site is not elevate-fi.com"
- Verify contract addresses before transactions

---

**Acceptance Criteria**:

- User can connect via Phantom, Solflare, Backpack, Ledger, Trezor
- Wallet auto-detected if installed
- Connection persists across page reloads (until logout or 30min timeout)
- User can connect multiple wallets to one account
- Hardware wallet support (Ledger, Trezor) works correctly
- Transaction simulation before signing (prevent failures)
- Clear error messages if wallet not installed or connection failed
- Disconnect wallet button visible when connected
- Wallet balance (USDC, SOL) displayed
- Security: Verify user owns wallet (signature challenge on first connect)

---

#### 4.7.4 Transaction History & Tracking

**Overview**:
Complete transaction history for all user activities: investments, distributions, refunds, and wallet transfers.

**Transaction Types**:
- **Investment**: USDC → Campaign tokens
- **Distribution**: Profit share claimed (USDC)
- **Refund**: Campaign failed, USDC returned
- **Fiat On-Ramp**: Card/Bank → USDC
- **Token Transfer**: Send tokens to another wallet (after lock-up)

---

**Transaction History Page** (Section 4.3.6):

**Display Columns**:
- Date & Time
- Type (Investment, Distribution, Refund, On-Ramp, Transfer)
- Campaign Name (if applicable)
- Amount (in USDC or tokens)
- Status (Pending, Confirmed, Failed)
- Transaction Hash (link to Solscan)
- Actions (View Details, Export)

**Filters**:
- Date Range: Last 7 days, Last 30 days, Last 90 days, All Time, Custom
- Type: All, Investments, Distributions, Refunds, On-Ramps, Transfers
- Status: All, Confirmed, Pending, Failed
- Campaign: Dropdown (all campaigns user invested in)

**Sorting**:
- Sort by: Date (newest first, oldest first), Amount (high to low, low to high)

**Search**:
- Search by: Campaign name, Transaction hash

---

**Transaction Detail Modal**:

**When user clicks "View Details":**

**Example: Investment Transaction**
```
Transaction Details
───────────────────
Type: Investment
Date: April 15, 2026, 10:30:45 AM SGT
Status: Confirmed ✓

Campaign: GreenTech Solutions - Series A
Amount Invested: 1,000 USDC
Tokens Received: 1,000 ELEV-GT-001
Token Price: $1.00 USDC per token

Lock-up Period: 12 months
Unlock Date: April 15, 2027

Transaction Hash: 5X8wK...9Lp2
Block: 12,345,678
Confirmations: 1,234 blocks

Fees:
- Network Fee (SOL): 0.00025 SOL (~$0.005)
- Platform Fee: $0 (deducted at escrow release)

From Wallet: 7Yz9...3Lm1
To Escrow: 2Bc4...6Np8

[View on Solscan] [Download Receipt]
```

---

**Export Functionality**:

**Use Case**: User needs transaction history for tax reporting

**Export Formats**:
- CSV (for Excel)
- PDF (printable receipt)
- JSON (for developers/APIs)

**CSV Export Example**:
```csv
Date,Type,Campaign,Amount,Currency,Tokens,Status,Transaction Hash
2026-04-15 10:30:45,Investment,GreenTech Solutions,1000,USDC,1000,Confirmed,5X8wK...9Lp2
2026-04-10 14:22:10,Investment,HealthTech Innovations,500,USDC,500,Confirmed,8Yp2...3Kl9
2026-06-30 09:00:00,Distribution,GreenTech Solutions,25,USDC,0,Confirmed,3Mn7...1Qw5
```

**PDF Export**: Formatted invoice with platform logo, user details, transaction breakdown

---

**Real-Time Transaction Monitoring**:

**WebSocket Updates**:
```typescript
// Frontend subscribes to transaction updates
const ws = new WebSocket(`wss://api.elevate-fi.com/transactions/${userId}`);

ws.onmessage = (event) => {
  const tx = JSON.parse(event.data);

  if (tx.status === 'confirmed') {
    toast.success(`Transaction confirmed! ${tx.type}`);
    // Update transaction list
    setTransactions([tx, ...transactions]);
  } else if (tx.status === 'failed') {
    toast.error(`Transaction failed: ${tx.error}`);
  }
};
```

**Transaction States**:
1. **Pending**: Transaction submitted, awaiting confirmation (0-5 seconds on Solana)
2. **Confirmed**: Transaction confirmed on-chain
3. **Failed**: Transaction failed (insufficient balance, rejected by user, network error)
4. **Cancelled**: User cancelled transaction before signing

---

**Transaction Receipts**:

**Auto-Generated PDF Receipt** (emailed to user):
```
ELEVATE FINANCE
Investment Receipt
──────────────────────────────────────────

Receipt No: INV-2026-00123
Date: April 15, 2026, 10:30:45 AM SGT

Investor Details:
Name: John Doe
Email: john.doe@example.com
Wallet: 7Yz9...3Lm1

Investment Details:
Campaign: GreenTech Solutions - Series A
Amount: 1,000 USDC
Tokens: 1,000 ELEV-GT-001
Token Price: $1.00 USDC
Lock-up: 12 months (until April 15, 2027)

Transaction Hash:
5X8wK9Lp2...3Bv7Mn1

Blockchain: Solana
Block Number: 12,345,678
Confirmations: 1,234

This is an automated receipt. For questions,
contact support@elevate-fi.com

──────────────────────────────────────────
Elevate Finance Pte Ltd
License: MAS CMS-123456
```

---

**Tax Reporting Integration** (Future - Phase 2):

**Auto-generate tax forms**:
- **Singapore**: Not required (no capital gains tax on securities)
- **US**: Form 8949 (if expanding to US market)
- **Australia**: CGT (Capital Gains Tax) report

**CoinTracker / Koinly Integration**:
- Export transactions in compatible format
- Auto-sync transactions via API
- Generate cost basis reports

---

**Acceptance Criteria**:

- Transaction history displays all user transactions (investments, distributions, refunds, on-ramps)
- Filters work correctly (date range, type, status, campaign)
- Search by campaign name or transaction hash
- Transaction detail modal shows complete information
- Export to CSV, PDF, JSON works
- PDF receipts auto-emailed after investment
- Real-time updates via WebSocket (pending → confirmed)
- Transaction hash links to block explorer (Solscan)
- Load time <2s for 1,000 transactions
- Pagination for large transaction lists (50 per page)

---

#### 4.7.5 Fee Calculation & Deduction

**Overview**:
Transparent fee structure with automatic calculation and deduction. Platform fees are deducted at escrow release (not at investment), ensuring investors receive full token allocation for their investment amount.

**Fee Types**:
1. **Platform Fee**: 2% of funds released (deducted from company, not investor)
2. **Network Fees**: Solana gas fees (~$0.005 per transaction, paid by investor)
3. **On-Ramp Fees**: 0.99% - 4.5% (varies by provider, paid by investor)

---

**Platform Fee (2%)**:

**When Charged**: At escrow release (Section 4.6.2)

**Calculation**:
```typescript
// Example: Company raises $500K, releases funds for Milestone 1
const milestoneFunding = 200_000; // $200K USDC
const platformFeeRate = 0.02; // 2%

const platformFee = milestoneFunding * platformFeeRate; // $4,000 USDC
const netToCompany = milestoneFunding - platformFee; // $196,000 USDC

// Smart contract auto-deducts and transfers:
// - $196,000 → Company wallet
// - $4,000 → Platform treasury
```

**Why Deduct at Release (not at Investment)?**:
- **Investor-friendly**: Investor gets 100% token allocation for their investment
- **Aligns incentives**: Platform only earns if company successfully raises funds
- **Regulatory clarity**: Fee structure transparent to regulators

**Volume Discounts**:
- Standard: 2% (up to $1M raised)
- Tier 1: 1.5% ($1M - $3M raised)
- Tier 2: 1% (>$3M raised)

```typescript
function calculatePlatformFee(totalRaised: number) {
  if (totalRaised <= 1_000_000) {
    return 0.02; // 2%
  } else if (totalRaised <= 3_000_000) {
    return 0.015; // 1.5%
  } else {
    return 0.01; // 1%
  }
}
```

---

**Network Fees (Solana Gas)**:

**Typical Fees**:
- Investment transaction: ~0.00025 SOL (~$0.005)
- Distribution claim: ~0.00010 SOL (~$0.002)
- Token transfer: ~0.00005 SOL (~$0.001)

**Auto-Deduction**:
- Solana runtime automatically deducts from user's SOL balance
- If user has insufficient SOL, transaction fails
- Frontend shows warning: "You need at least 0.001 SOL for gas fees"

**SOL Airdrop** (for new users):
```typescript
// Backend airdrops 0.01 SOL to new wallets (covers ~40 transactions)
if (user.first_investment && solBalance < 0.001) {
  await airdropSol(walletAddress, 0.01);
  toast.info('0.01 SOL airdropped for gas fees');
}
```

---

**On-Ramp Fees**:

**Stripe** (3.1% + $0.30):
```typescript
const usdcAmount = 1000; // User wants $1,000 USDC
const stripeFeePercent = 0.031;
const stripeFeeFixed = 0.30;
const circleFee = 0.002; // 0.2% USDC purchase

const totalFee = (usdcAmount * (stripeFeePercent + circleFee)) + stripeFeeFixed;
// = (1000 * 0.033) + 0.30 = $33.30

const totalCharge = usdcAmount + totalFee; // $1,033.30
const usdcReceived = usdcAmount; // $1,000 USDC
```

**Transak** (0.99%):
```typescript
const usdcAmount = 50_000; // User wants $50K USDC
const transakFee = usdcAmount * 0.0099; // $495

const totalCharge = usdcAmount + transakFee; // $50,495
const usdcReceived = usdcAmount; // $50,000 USDC
```

**Fee Comparison Displayed to User**:
```
Purchase $1,000 USDC

Option 1: Stripe (Credit Card)
- You pay: $1,033.30 USD
- You receive: 1,000 USDC
- Fee: $33.30 (3.3%)
- Time: 2-5 minutes
[Select]

Option 2: Transak (Bank Transfer)
- You pay: $1,009.90 USD
- You receive: 1,000 USDC
- Fee: $9.90 (0.99%)
- Time: 1-2 business days
[Select] ← Recommended (Lower Fees)

Option 3: MoonPay (Credit Card)
- You pay: $1,045.00 USD
- You receive: 1,000 USDC
- Fee: $45.00 (4.5%)
- Time: 5-30 minutes
[Select]
```

---

**Fee Breakdown Display** (Investment Confirmation Page):

```
Investment Summary
──────────────────
Campaign: GreenTech Solutions - Series A
Investment Amount: 1,000 USDC

Tokens You'll Receive: 1,000 ELEV-GT-001
Token Price: $1.00 USDC

Fees:
┌─────────────────────────────────────┐
│ Network Fee (SOL): 0.00025 SOL     │
│                    ~$0.005 USD      │
│                                     │
│ Platform Fee: $0                    │
│ (Deducted from company at release) │
└─────────────────────────────────────┘

Total Cost: 1,000 USDC + 0.00025 SOL

Lock-up Period: 12 months
Unlock Date: April 15, 2027

[Confirm Investment]
```

---

**Fee Transparency Dashboard** (Admin Panel):

**Platform Revenue Tracking**:
- Total Fees Collected: $125,000 USDC (Year-to-Date)
- Average Fee per Campaign: $4,167 USDC
- Fee Breakdown:
  - From Milestone Releases: $120,000 (96%)
  - From Performance Fees: $5,000 (4%, future feature)
- Top Revenue Campaigns:
  1. GreenTech Solutions: $10,000
  2. HealthTech Innovations: $8,500
  3. FinTech Startup: $7,200

---

**Acceptance Criteria**:

- Platform fee (2%) auto-deducted at escrow release
- Volume discounts applied automatically ($1M, $3M thresholds)
- Network fees (SOL) estimated and displayed before transaction
- On-ramp fees clearly shown with provider comparison
- Fee breakdown visible on investment confirmation page
- $0 platform fee charged to investors (charged to companies)
- SOL airdrop for new users (covers gas for ~40 transactions)
- Fee transparency: All fees disclosed upfront
- Admin dashboard shows total fees collected, breakdown by campaign
- Audit trail for all fee deductions

---

**Section 4.7 Summary (Payment & Treasury)**:

Section 4.7 covers the complete payment infrastructure with 5 major subsections:

- **4.7.1**: Stablecoin Deposits (USDC/USDT direct wallet investments with full transaction flow)
- **4.7.2**: Fiat On-Ramp Integration (Stripe, Transak, MoonPay with selection logic and fee comparison)
- **4.7.3**: Wallet Connection & Management (WalletConnect, hardware wallet support, multi-wallet)
- **4.7.4**: Transaction History & Tracking (complete history, export, real-time updates, tax receipts)
- **4.7.5**: Fee Calculation & Deduction (transparent fees, volume discounts, auto-deduction at release)

**Total lines added**: ~1,050 lines
**Estimated implementation time**: 8-10 weeks for all payment features

**Key Features**:
- Multiple payment methods (crypto + fiat)
- Seamless fiat-to-crypto on-ramps
- Hardware wallet support (Ledger, Trezor)
- Real-time transaction tracking
- Transparent fee structure (no hidden fees)
- Investor-friendly (platform fee from company, not investor)
- Tax-ready exports (CSV, PDF, JSON)

**Integrations Required**:
- Stripe (credit/debit cards)
- Transak (bank transfers - Asia)
- MoonPay (global fallback)
- Circle API (USDC purchases)
- Solana Wallet Adapter (WalletConnect)

---

