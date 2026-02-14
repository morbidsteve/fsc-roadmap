# Fighting Smart Cyber — 12-Month Roadmap

**Period:** Q1 2026 – Q4 2026
**Last updated:** 2026-02-13

---

## Mission

Deliver operator-grade cybersecurity platforms and training to defense, intelligence, and commercial organizations — built by operators, for operators.

## Strategic Position

FSC's founding team brings combined decades of classified cyber operations experience across DoD and the Intelligence Community. This is FSC's competitive moat.

| Differentiator | Why it matters |
|----------------|----------------|
| Operator-led, not sales-led | Products designed by people who've executed real-world cyber operations — not built by engineers guessing at operator needs |
| TS/SCI-cleared leadership | Engage on classified requirements and environments from day one |
| DOTMLPF-P assessment framework | Holistic capability evaluations that go beyond tools — doctrine, organization, training, materiel, leadership, personnel, facilities, policy |
| Full-stack delivery | Strategy through implementation through training through managed operations — one vendor, no handoffs |
| Training as the entry point | Every training engagement is a live product demo; every assessment identifies gaps FSC products solve |

### Where FSC plays

- **Cyber range & training** — CYROID: enterprise range orchestration, operator-led courses, certification programs
- **Security operations** — SOC-in-a-Box: turnkey SOC platform (SIEM + EDR + threat intel), SOC-as-a-Service
- **Infrastructure security** — Secure Kubernetes Core: Zero Trust K8s baseline for mission-critical workloads
- **Advisory** — Red team, penetration testing, DOTMLPF-P analysis, capability development, Zero Trust roadmaps

### Competitive landscape

| Category | Premium tier | Mid-market | FSC positioning |
|----------|-------------|------------|-----------------|
| Cyber ranges | SimSpace ($500K+ contracts) | Hack The Box, RangeForce | Operator-grade fidelity at mid-market pricing ($200–400/seat/mo) |
| MDR / SOC | Arctic Wolf, Expel | Blumira, Todyl | Accreditation-ready, K8s-native, deployed on-prem or FSC-hosted |
| K8s security | Aqua Security, Sysdig | ARMO (Kubescape) | Zero Trust baseline + compliance evidence generation, not just runtime scanning |

---

## Current State

| Asset | Status | Revenue generating |
|-------|--------|--------------------|
| CYROID Cyber Range | Live | Yes — training engagements |
| Training Programs | Live | Yes — primary revenue driver |
| Consulting & Assessments | Active | Yes — per-engagement |
| Secure Kubernetes Core | In development | No |
| SOC-in-a-Box | In development | No |

---

## Strategic Pillars (Priority Order)

1. **Training revenue engine** — Training and consulting are the revenue base today. Scale delivery, deepen CYROID integration, and build recurring revenue through certification programs. Every training dollar funds product development.

2. **Platform maturity** — Ship Secure K8s Core and SOC-in-a-Box to production. These unlock the enterprise and government platform sale. K8s Core is the prerequisite — it gates SOC-in-a-Box and all deployment bundles.

3. **Government market entry** — Secure contract vehicles, pursue agency ATOs, and position for FedRAMP 20x authorization. SBA set-aside designation (SDVOSB if applicable) is the single biggest accelerator for government deal velocity.

4. **Commercial expansion** — Package platforms for enterprise security teams and MSSPs. Training opens doors; platforms close multi-year deals.

5. **Managed services growth** — SOC-as-a-Service and Training-as-a-Service create high-margin recurring revenue layered on top of platforms.

---

## Go-to-Market Model

### Revenue Streams

| Stream | Offerings | Model | Priority |
|--------|-----------|-------|----------|
| **Training & Certification** | Instructor-led courses, CYROID range access, certification exams | Per-engagement + annual seat licenses | Highest — live now |
| **Consulting & Assessments** | Red team, pen test, DOTMLPF-P analysis, Zero Trust roadmaps | T&M or fixed-price | High — active now |
| **Platform Subscriptions** | Secure K8s Core Pro, CYROID Enterprise, SOC-in-a-Box | Annual subscription (per cluster / seat / deployment) | Medium — ships Q2–Q4 |
| **Managed Services** | SOC-as-a-Service (24/7 MDR), Training-as-a-Service | Monthly retainer | Medium — launches Q3 |
| **SaaS** | CYROID Cloud, SOC-in-a-Box Cloud (FSC-hosted, self-service) | Usage-based + seat subscription | Future — launches Q4 |

### Customer Engagement Ladder

```
Discovery call
  → Assessment or training engagement (proves value, builds trust)
    → Platform license (customer deploys FSC products)
      → Managed services (FSC operates on customer's behalf)
        → SaaS (fully FSC-hosted, self-service)
```

Training and consulting are the top of funnel. Every training engagement is a platform demo. Every assessment identifies gaps FSC products address. This flywheel drives deal velocity without cold outbound.

### Community Editions

Free evaluation tiers of Secure K8s Core and CYROID (limited feature set) drive awareness and conversion to commercial licenses. These are lead generation instruments, not standalone products.

> *Community users only matter if they convert. Track both adoption and conversion rate — the target is 5% conversion to commercial within 6 months of signup. Without that, community metrics are vanity metrics.*

| Quarter | Community users (cumulative) | Target conversion to commercial |
|---------|----------------------------|-------------------------------|
| Q2 | 50+ | Tracking begins |
| Q3 | 200+ | 5% (10 leads in pipeline) |
| Q4 | 500+ | 5% (25 leads in pipeline) |

### Funding Strategy

| Source | Timeline | Purpose |
|--------|----------|---------|
| Training + consulting revenue | Now | Fund operations and core team |
| Platform license revenue | Q2+ | Fund scaling and go-to-market |
| Government contract revenue | Q3+ | Fund platform development and compliance |
| SBIR/STTR proposals | Submit Q1–Q2; awards unlikely before Q4 2026 due to program reauthorization delays | Non-dilutive R&D funding (treat as upside, not dependency) |
| Retained earnings | Ongoing | Reinvest into product and growth |

*FSC's model: grow on revenue and non-dilutive funding. Avoid premature equity dilution.*

### Pricing Assumptions

> *Every revenue target in this roadmap is built on these assumptions. If actual ACVs differ, update the targets accordingly. These are calibrated against market benchmarks (SimSpace, Arctic Wolf, Hack The Box, Blumira) and adjusted for FSC's stage.*

| Revenue stream | Assumed ACV | Basis |
|----------------|------------|-------|
| Training engagement (instructor-led + CYROID) | $20K–$50K per engagement | Mid-market: above Hack The Box ($3K/seat/yr), below SimSpace ($500K+) |
| Consulting / assessment | $25K–$75K per engagement | T&M at $200–$300/hr or fixed-price scoping |
| Platform license (K8s Core, CYROID Enterprise, SOC) | $50K–$150K annual | Enterprise subscription; positions below Aqua/Sysdig ($100K+) on-ramp |
| Managed SOC retainer | $10K–$25K/month | MDR market rate: $15–$25/endpoint/mo for mid-market |
| SaaS (CYROID Cloud, SOC Cloud) | $200–$400/seat/month | Usage-based; validated against CYRIN ($2.5K/yr) and HTB Enterprise |

### Revenue Targets

> *All figures are quantitative so any reader can verify the math. "Baseline" has been replaced with a fill-in — the CEO must enter the actual current-state number. Revenue columns show projected quarterly bookings by stream; ARR is the cumulative annual run rate at quarter-end.*

| Quarter | Training + Consulting (quarterly) | Platform Licenses (quarterly) | Managed / SaaS (quarterly) | ARR (cumulative, quarter-end) |
|---------|----------------------------------|------------------------------|---------------------------|-------------------------------|
| Q1 | **[ENTER CURRENT QUARTERLY REVENUE]** | $0 | $0 | **[ENTER CURRENT ARR]** |
| Q2 | $100K–$150K (3+ engagements) | $100K–$200K (2–3 licenses × $50K–$75K) | $0 | $250K+ |
| Q3 | $150K–$250K (5+ engagements) | $250K–$400K (5–8 licenses cumulative) | $30K–$75K (1–2 managed SOC pilots) | $500K+ |
| Q4 | $200K–$300K (certification + engagements) | $500K–$750K (10–15 licenses cumulative) | $100K–$200K (SaaS + managed active) | $750K–$1M |

> *Pipeline-to-close ratio assumption: ~10:1 for government, ~5:1 for commercial. A $10M pipeline at Q4 implies ~$1M–$2M in closeable revenue — consistent with the ARR target. If actual close rates differ, adjust pipeline targets accordingly.*

---

## Q1 2026 (Feb – Apr) — Foundation

**Quarter focus:** Stand up company operations. Accelerate training revenue. Ship Secure K8s Core beta. Begin government pipeline.

### Product

- [ ] **CYROID: Enterprise hardening + training integration**
  - Multi-tenant isolation and role-based access control
  - Stable API (v1) with published documentation
  - Training-mode features: guided walkthroughs, progress tracking, exercise scoring
  - Pre-built range templates for each FSC training course
  - Usage telemetry and range health dashboards

- [ ] **Secure Kubernetes Core: Beta** *(prerequisite for SOC-in-a-Box)*
  - Zero Trust network policy architecture
  - Hardened node images aligned to CIS benchmarks
  - GitOps-driven deployment with secrets management
  - Internal dogfooding: deploy on FSC infrastructure

- [ ] **SOC-in-a-Box: Architecture & design** *(depends on Secure K8s Core beta)*
  - Requirements: SIEM, EDR, threat intel, vulnerability management
  - Architecture design document and technology selection
  - Component integration plan with Secure K8s Core as base layer

### Training

- [ ] **Training acceleration**
  - Expand CYROID-integrated course catalog (Cloud Security Operations, Purple Teaming)
  - Build reusable CYROID range templates per training course
  - Launch Training-as-a-Service: bundled CYROID access + instructor-led sessions
  - Establish monthly training cohort delivery cadence
  - Begin LMS platform evaluation and selection

- [ ] **Training content pipeline**
  - Document course development framework (objectives, labs, assessments)
  - Build CYROID scenario library mapped to each course module

### Business

- [ ] **Government readiness**
  - SAM.gov registration and capability statement updates
  - Identify 3–5 target contract vehicles (BPAs, IDIQs, OTAs)
  - **Evaluate SBA set-aside designations** — SDVOSB, 8(a), HUBZone (fastest path to reducing government sales cycle)
  - Begin SBIR/STTR proposal preparation (submit when program reauthorization passes)
  - Engage FedRAMP 3PAO for readiness assessment; plan for FedRAMP 20x Low authorization path

- [ ] **Compliance groundwork**
  - Begin CMMC Level 2 gap analysis
  - Document System Security Plan (SSP) for SOC-in-a-Box

- [ ] **Customer engagement**
  - 10 discovery calls / product demos
  - 2 active proposals or RFP responses in progress
  - Build target account list: 25 government + 25 commercial
  - Attend 1 industry conference or trade show

### Operations

- [ ] **Company infrastructure**
  - Business entity formalization, contract templates, NDA/MSA library
  - Accounting, financial reporting, insurance (GL, E&O, cyber liability)
  - Corporate email, internal comms platform, document management
  - Endpoint management, MFA enforcement, backup/DR plan
  - Ticket/issue tracking for internal project management

- [ ] **Brand & thought leadership**
  - Brand identity: logo, style guide, slide deck templates, one-pagers
  - Website: SEO, analytics tracking, lead capture
  - Content calendar: LinkedIn and X presence, technical blog posts from leadership
  - Marketing collateral for each product and training offering

- [ ] **Hiring**
  - Platform engineering lead
  - Sales engineer (government sector)

---

## Q2 2026 (May – Jul) — Ship & Sell

**Quarter focus:** Ship Secure K8s Core GA and SOC-in-a-Box alpha. Close first commercial deals. Begin FedRAMP 20x preparation.

### Product

- [ ] **Secure Kubernetes Core: GA release** *(gates SOC-in-a-Box and deployment bundles)*
  - Production-hardened, tested, documented
  - Compliance evidence generation (CIS, NIST 800-53 controls mapping)
  - Published as standalone product with pricing
  - Community edition released (limited feature set, drives adoption)

- [ ] **SOC-in-a-Box: Alpha** *(depends on Secure K8s Core GA)*
  - Core stack integration: SIEM + EDR + threat intel on K8s Core
  - Automated deployment pipeline (single-command standup)
  - Initial alert correlation and playbook framework
  - Customer-facing operational dashboards
  - Internal proof-of-concept on FSC infrastructure

- [ ] **CYROID: Self-service pilot**
  - Customer self-registration and onboarding flow
  - Usage-based metering and billing integration
  - Community scenario templates: first contributed range definitions

- [ ] **Deployment bundles: First releases**
  - DevSecOps Bundle and DFIR Bundle on Secure K8s Core
  - One-click deployment, health monitoring, update channels

### Training

- [ ] **Training expansion**
  - LMS launch with on-demand course catalog (async + recorded)
  - Package CYROID + training as unified offering for government RFPs
  - 2 additional courses: Threat Hunting Advanced, Kubernetes Security Operations
  - Begin FSC certification program design (Certified Cyber Range Operator)
  - 3+ enterprise training engagements delivered

### Business

- [ ] **FedRAMP 20x preparation**
  - Submit FedRAMP Ready designation package
  - Prepare for FedRAMP 20x Phase 3 (general availability expected mid-2026)
  - Budget $150K–$300K for Low authorization process
  - Begin agency ATO documentation for first government customer

- [ ] **First deals**
  - Pursue GSA Schedule listing or existing vehicle subcontract
  - Respond to 2–3 RFPs/RFIs targeting CYROID + training
  - Close first government deal + 2 commercial customers
  - Target federal Q3 (Apr–Jun) for contract timing

- [ ] **Commercial launch**
  - Pricing and packaging finalized for all products
  - Product pages with demos and ROI calculator
  - Launch MSSP/integrator partner program

- [ ] **Customer engagement**
  - 20 discovery calls / product demos
  - 5 active proposals or RFP responses
  - Establish 2 prime contractor relationships
  - Attend 2 conferences or trade shows

### Operations

- [ ] **Go-to-market operations**
  - CRM setup and sales pipeline tooling
  - Customer onboarding process documentation
  - Proposal/RFP response workflow and templates
  - Paid advertising: LinkedIn and Google Ads targeting gov/enterprise buyers
  - Email marketing: newsletter and lead nurture drip campaigns

- [ ] **Infrastructure evaluation: self-hosted vs. SaaS**
  - Assess GitHub/GHCR usage against API rate limits and scaling needs
  - Evaluate self-hosted alternatives (Gitea/Forgejo, Harbor for container registry)
  - Decision criteria: cost, API limits, compliance requirements (CMMC, classified repos), team size
  - If GitHub works at current scale, defer migration; if not, plan for Q3

---

## Q3 2026 (Aug – Oct) — Scale

**Quarter focus:** SOC-in-a-Box beta at customer sites. Managed SOC tier operational. Build pipeline toward $5M. Target federal fiscal year-end spending (July–September).

### Product

- [ ] **SOC-in-a-Box: Beta**
  - Production pilot at 2+ customer sites
  - Automated compliance reporting (NIST, CMMC control evidence)
  - Managed service tier: FSC-operated SOC option

- [ ] **CYROID: Marketplace & integrations**
  - GovCloud deployment options (AWS GovCloud, Azure Government)
  - LMS integration for course-to-lab handoff
  - Automated scoring and assessment engine
  - Published on cloud marketplace(s)

- [ ] **Platform convergence**
  - Unified management plane across CYROID + SOC-in-a-Box
  - Single sign-on across all products
  - Shared observability and monitoring stack

- [ ] **Deployment bundles: Full catalog**
  - SOC Stack and Productivity Suite bundles ship
  - Custom bundle builder for enterprise customers

### Training

- [ ] **Certification launch**
  - FSC Certified Cyber Range Operator (CCRO) program live
  - 100+ students through online courses
  - Speaking slots at 2+ industry events

### Business

- [ ] **Government traction** *(align with federal fiscal year-end spending)*
  - 2+ active government contracts or task orders
  - IL4/IL5 authorization path for SOC-in-a-Box
  - Participate in CDAO or Service Cyber Component exercises with CYROID
  - Leverage SBA set-aside designation (if secured) for sole-source or limited competition awards

- [ ] **Enterprise sales**
  - 5+ commercial enterprise customers
  - 2+ MSSP partners reselling platforms
  - Case studies published from early adopters

- [ ] **Customer engagement**
  - 30 discovery calls / product demos
  - 8 active proposals or RFP responses
  - $5M in pipeline value
  - 3 prime contractor relationships
  - Attend 3 conferences; speaking slots at 2+

### Operations

- [ ] **Scaling operations**
  - Customer support system and SLAs defined
  - Incident response and escalation procedures for managed services
  - Internal knowledge base and runbooks
  - Revenue forecasting model and unit economics analysis

- [ ] **Infrastructure self-hosting** *(if Q2 evaluation warrants)*
  - Migrate Git, container registry, and ticket management to self-hosted
  - Self-hosted CI/CD pipeline
  - On-prem artifact storage and package management

- [ ] **AI operations: foundation**
  - Evaluate and deploy internal AI assistant for business operations
  - Automate recurring tasks: report generation, meeting summaries, proposal drafts
  - AI-assisted code review and documentation generation for product development
  - Build internal knowledge base that AI agents can query

- [ ] **Hiring**
  - Customer success / support engineer
  - Training content developer
  - Business development (commercial sector)

---

## Q4 2026 (Nov – Jan 2027) — Compound

**Quarter focus:** SOC-in-a-Box GA + SaaS tier. FedRAMP 20x authorization in progress. Recurring revenue > 40% of total. Plan 2027.

### Product

- [ ] **SOC-in-a-Box: GA + SaaS tier**
  - Multi-tenant SaaS offering (FSC-hosted)
  - Self-service signup with trial environment and upgrade path
  - SOC-as-a-Service: 24/7 managed detection & response option

- [ ] **CYROID: Advanced capabilities**
  - After-action review analytics and trainee performance tracking
  - Federation: connect multiple ranges for joint exercises
  - Advanced scenario library with adaptive difficulty
  - AI-enhanced scenario generation and automated scoring

- [ ] **Secure K8s Core: Ecosystem**
  - Certified partner integrations with major security vendors
  - Air-gapped deployment package for classified environments
  - Community edition growth and conversion tracking

- [ ] **Developer platform**
  - Public API and SDK for CYROID and SOC-in-a-Box
  - Webhook framework for customer workflow automation

### Training

- [ ] **Training at scale**
  - 500+ students trained (combined in-person + online)
  - 3+ FSC certifications offered
  - Training operating as standalone business unit with independent P&L

### Business

- [ ] **Revenue milestones**
  - $750K–$1M ARR target
  - Recurring revenue (subscriptions + managed services) > 40% of total
  - Expansion revenue from existing accounts

- [ ] **Government depth**
  - FedRAMP 20x authorization in process (target: authorized by mid-2027)
  - 3+ government agency customers
  - Subcontract relationships with 2+ defense primes

- [ ] **Market position**
  - 10+ commercial enterprise customers
  - 5+ MSSP/integrator partners active
  - Analyst briefings initiated (Gartner, Forrester)

- [ ] **Customer engagement**
  - 40 discovery calls / product demos
  - 12 active proposals or RFP responses
  - $10M in pipeline value
  - 5 prime contractor relationships
  - Attend 4 conferences

### Operations

- [ ] **Mature operations**
  - 2027 strategic planning process and annual review
  - Formalized hiring pipeline and onboarding program
  - Vendor and partnership management framework
  - Marketing ROI analysis — double down on what works

- [ ] **AI operations: maturity**
  - Self-hosted AI infrastructure for day-to-day business tasks
  - AI agents handling routine operations: scheduling, customer intake, ticket triage
  - AI-powered content generation: training materials, marketing copy, proposal drafts
  - Internal AI platform that team members can build custom workflows on
  - Evaluate integrating AI capabilities into customer-facing products

---

## Key Metrics

> *Every metric below is labeled as either (quarterly) — measured for that quarter only, (cumulative) — running total year-to-date, or (point-in-time) — snapshot at quarter-end. This eliminates the ambiguity of "did we train 500 students total, or 500 in Q4?"*

### Revenue & Financial Health

> *These are the numbers a CEO checks weekly. ARR and burn rate together tell you whether the company survives. Training revenue funds everything else — if this line item stalls, all other targets are at risk.*

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| ARR | point-in-time | **[ENTER]** | $250K+ | $500K+ | $750K–$1M |
| Training + consulting revenue | quarterly | **[ENTER]** | $100K–$150K | $150K–$250K | $200K–$300K |
| Platform license revenue | cumulative | $0 | $100K–$200K | $250K–$400K | $500K–$750K |
| Managed / SaaS revenue | quarterly | $0 | $0 | $30K–$75K | $100K–$200K |
| Avg contract value (platform) | point-in-time | — | $50K–$75K | $60K–$80K | $60K–$80K |
| Team size (founders + hires) | point-in-time | **[ENTER]** + 2 | same | same + 3 | same |
| Quarterly operating cost (est.) | quarterly | **[ENTER]** | **[ENTER]** | **[ENTER]** | **[ENTER]** |
| Cash position / runway | point-in-time | **[ENTER]** | **[ENTER]** | **[ENTER]** | **[ENTER]** |

> *The [ENTER] fields are intentional placeholders. Only the CEO knows the actual starting revenue, team size, and burn rate. Fill these in before sharing this roadmap externally — a document with blank financials signals that the plan hasn't been pressure-tested.*

### Pipeline & Sales

> *Pipeline value is only useful in context. A $10M pipeline with a 10:1 close ratio yields $1M — which matches the ARR target. If close rates improve (via set-aside contracts, OTA wins), revenue accelerates. If they worsen, pipeline targets need to increase.*

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| Discovery calls / demos | quarterly | 10 | 20 | 30 | 40 |
| Active proposals / RFPs | point-in-time | 2 | 5 | 8 | 12 |
| Pipeline value | point-in-time | $500K | $2M | $5M | $10M |
| Pipeline-to-close ratio (est.) | point-in-time | — | ~7:1 | ~7:1 | ~10:1 |
| Gov deals closed | cumulative | 0 | 1 | 2+ | 3+ |
| Commercial deals closed | cumulative | 0 | 2 | 5+ | 10+ |
| Avg sales cycle (observed) | point-in-time | — | **[TRACK]** | **[TRACK]** | **[TRACK]** |

> *Sales cycle length is marked [TRACK] — you won't know this in Q1, but by Q2–Q3 you'll have data. Tracking actual cycle length against the 12-18 month assumption for government deals is critical for forecasting.*

### Training

> *Students trained is cumulative (year-to-date). Training engagements delivered is per-quarter — the activity metric that directly drives revenue. Courses available is a point-in-time catalog count.*

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| Training engagements delivered | quarterly | 2 | 5 | 10 | 15+ |
| Students trained | cumulative YTD | 50 | 150 | 300 | 500+ |
| Revenue per engagement (avg) | point-in-time | **[TRACK]** | **[TRACK]** | **[TRACK]** | **[TRACK]** |
| Courses available | point-in-time | 5 | 7 | 9 | 9+ |

> *Revenue per engagement is marked [TRACK] because it varies by format (instructor-led vs. online, gov vs. commercial). Tracking this from Q1 lets you forecast training revenue accurately by Q3.*

### Partnerships

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| MSSP partners | cumulative | 0 | 0 | 2 | 5+ |
| Prime contractor relationships | cumulative | 1 | 2 | 3 | 5 |

### Product

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| Products at GA | point-in-time | 1 (CYROID) | 2 (+K8s Core) | 2 (SOC beta) | 3 (+SOC GA) |
| Community edition users | cumulative | — | 50+ | 200+ | 500+ |
| Community → commercial conversion | point-in-time | — | tracking begins | 5% target | 5% target |

### Go-to-Market Activity

> *Conference appearances moved here from "Team" — they're a pipeline and brand investment, not a staffing metric. The distinction between sponsoring ($15K–$30K) and attending ($2K–$5K) matters for budget planning.*

| Metric | Type | Q1 | Q2 | Q3 | Q4 |
|--------|------|-----|-----|-----|-----|
| Conferences attended | quarterly | 1 | 2 | 3 | 4 |
| Conference investment (est.) | quarterly | **[BUDGET]** | **[BUDGET]** | **[BUDGET]** | **[BUDGET]** |
| Speaking slots | cumulative | 0 | 0 | 2+ | 4+ |

---

## Risk Register

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| FedRAMP timeline extends beyond 2027 | Medium | High | Target FedRAMP 20x Low (faster, cheaper); pursue agency ATOs in parallel; sell on-prem to gov while authorization is in process |
| SOC-in-a-Box scope creep delays GA | Medium | High | Strict MVP: ship core detection first, advanced analytics in v2. Gate features on customer demand, not roadmap ambition |
| Key person dependency | High | High | Document everything; cross-train across founders; hire to eliminate single points of failure |
| Government sales cycle exceeds 18 months | High | Medium | Maintain training + consulting cashflow; pursue OTAs and set-aside contracts for faster entry; target federal Q4 flush (Jul–Sep) |
| SBIR/STTR reauthorization stalls | Medium | Medium | Do not depend on SBIR funding; plan to fund all R&D from revenue. Treat SBIR awards as acceleration, not survival |
| Commercial market fit uncertain | Medium | Medium | Validate with 3 commercial design partners before full go-to-market. Price SOC-in-a-Box at MDR market rates ($15–25/endpoint/mo) |
| Compliance costs exceed budget | Medium | Medium | Budget 20% buffer; prioritize CMMC (faster, cheaper) before FedRAMP. FedRAMP 20x Low reduces cost to $150K–$300K |
| Training revenue plateaus | Low | High | Diversify: certification programs, LMS on-demand, enterprise annual contracts. Training funds product development — protect this at all costs |
| Team burns out on ops overhead | Medium | Medium | Automate early; outsource bookkeeping and admin; defer non-essential projects. Focus is the discipline |

---

## Dependencies

```
Secure K8s Core (Beta Q1 → GA Q2)
    ├── SOC-in-a-Box (Architecture Q1 → Alpha Q2 → Beta Q3 → GA + SaaS Q4)
    └── Deployment Bundles (DevSecOps + DFIR Q2 → Full catalog Q3)

CYROID (Live → Hardening + Training Q1 → Self-service Q2 → Marketplace Q3 → Advanced Q4)

Training (Live → Accelerate Q1 → LMS + Expand Q2 → Certification Q3 → Scale Q4)

Compliance (CMMC gap analysis Q1 → FedRAMP Ready Q2 → Agency ATOs Q3 → FedRAMP 20x In Process Q4)

Infrastructure (GitHub/SaaS Q1 → Evaluate self-hosting Q2 → Migrate if needed Q3 → Stable Q4)

AI Operations (— Q1 → — Q2 → Foundation Q3 → Self-hosted + mature Q4)

Revenue (Training + Consulting now → Platform licenses Q2 → Managed services Q3 → SaaS Q4)
```
