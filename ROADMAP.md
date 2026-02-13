# Fighting Smart Cyber — 12-Month Roadmap

**Period:** Q1 2026 – Q4 2026
**Last updated:** 2026-02-13

## Current State

| Asset | Status |
|-------|--------|
| CYROID Cyber Range | Live |
| Training Programs | Live |
| SOC-in-a-Box | In development |
| Secure Kubernetes Core | In development |
| App Bundles | In development |
| Consulting & Assessments | Active |

## Strategic Pillars

1. **Training + CYROID revenue engine** — Training is the revenue driver now; scale it and deepen CYROID integration
2. **Platform maturity** — Ship SOC-in-a-Box and Secure K8s Core to production
3. **Government readiness** — Achieve compliance posture for DoD/IC contracts
4. **Commercial expansion** — Package platforms for enterprise and MSSP buyers
5. **Self-service SaaS** — Move CYROID and SOC-in-a-Box toward self-service models

---

## Business Model: Open Core + SaaS + Managed Services

FSC operates a **tiered service model** with clear boundaries between open, commercial, and managed offerings.

### Tier 1: Open Core (Community)
Free, open-source base layers that drive adoption and build trust.

| Product | What's open | Purpose |
|---------|------------|---------|
| Secure K8s Core | Hardened K8s baseline, CIS-aligned configs, basic GitOps | On-ramp for enterprises; proves expertise; community contributions |
| CYROID | Scenario template format, basic range definition spec | Ecosystem lock-in through community-built scenarios |

**Revenue from open core: $0 (intentional).** Goal is adoption, not direct revenue.

### Tier 2: Commercial Platform (Licensed / Subscription)
Enterprise features, support, and compliance tooling layered on top of open core.

| Product | Commercial features | Pricing model |
|---------|-------------------|---------------|
| Secure K8s Core Pro | Compliance evidence generation, NIST/CMMC mapping, automated auditing, priority support | Annual subscription per cluster |
| CYROID Enterprise | Multi-tenant RBAC, training mode, scoring engine, LMS integration, GovCloud deployment | Annual subscription per seat or per range |
| SOC-in-a-Box | Full SOC stack (SIEM + EDR + threat intel), deployment automation, dashboards | Annual subscription per deployment |
| App Bundles | DevSecOps, DFIR, SOC Stack, Productivity suites — curated and tested on Secure K8s Core | Per-bundle subscription or bundled with platform |

**Revenue targets by tier:**

| Quarter | Open core users | Commercial licenses | Target ARR |
|---------|----------------|-------------------|------------|
| Q2 2026 | 50+ | 3 | — |
| Q3 2026 | 200+ | 8 | $500K |
| Q4 2026 | 500+ | 15+ | $2M |

### Tier 3: SaaS (FSC-Hosted)
Fully managed, multi-tenant cloud offerings — customers pay for outcomes, not infrastructure.

| Product | SaaS offering | Pricing model |
|---------|--------------|---------------|
| CYROID Cloud | Self-service range provisioning, pay-per-use, hosted scenario marketplace | Usage-based (hours/ranges) + seat subscription |
| SOC-in-a-Box Cloud | Hosted SOC with dashboards, alerting, compliance reporting | Monthly per-seat + data volume |

**SaaS launches in Q4 2026.** Revenue target: 40% of total revenue from SaaS + managed by end of year.

### Tier 4: Managed Services
White-glove, FSC-operated services for customers who need outcomes, not products.

| Service | What FSC does | Pricing model |
|---------|--------------|---------------|
| SOC-as-a-Service | 24/7 detection, triage, and response operated by FSC analysts | Monthly retainer based on scope |
| Training-as-a-Service | CYROID ranges + FSC instructors, delivered on customer schedule | Per-engagement or annual contract |
| Consulting & Assessment | Red team, pen test, DOTMLPF-P analysis, capability development | T&M or fixed-price per engagement |

### Decision Framework: Which Tier for Each Customer?

```
Customer needs → Does it themselves → Tier 1 (Open Core) or Tier 2 (Commercial)
Customer needs → FSC hosts it        → Tier 3 (SaaS)
Customer needs → FSC runs it          → Tier 4 (Managed Services)
```

### Quarterly SaaS & Model Goals

| Quarter | Goal |
|---------|------|
| Q1 | Define open core vs. commercial boundary for each product. Publish community editions. |
| Q2 | Commercial licenses shipping. Begin self-service SaaS pilot (CYROID). Price validation with 3 design partners. |
| Q3 | CYROID SaaS live. SOC-in-a-Box commercial license GA. Managed SOC tier operational. Track open core → commercial conversion. |
| Q4 | SOC-in-a-Box SaaS live. 40% revenue from SaaS + managed. Annual plans and expansion pricing established. |

---

## Q1 2026 (Feb – Apr) — Foundation

### Product

- [ ] **CYROID: Enterprise hardening + training integration**
  - Multi-tenant isolation and role-based access control overhaul
  - Stable API (v1) with published documentation
  - Usage telemetry and range health dashboards
  - Training-mode features: guided lab walkthroughs, progress tracking, exercise scoring
  - Pre-built range templates for each FSC training course

- [ ] **Secure Kubernetes Core: Beta** *(prerequisite for SOC-in-a-Box and App Bundles)*
  - Zero Trust network policy architecture
  - Hardened node images aligned to CIS benchmarks
  - GitOps-driven deployment with secrets management

- [ ] **SOC-in-a-Box: Architecture & design** *(depends on Secure K8s Core beta)*
  - Requirements gathering: SIEM, EDR, threat intel, vulnerability management
  - Architecture design document and technology evaluation
  - Component integration plan with Secure K8s Core as the base layer
  - Internal proof-of-concept on FSC infrastructure

- [ ] **App Bundles: Define catalog**
  - Finalize bundle compositions (DevSecOps, DFIR, SOC Stack, Productivity)
  - Define packaging and deployment standards
  - Dependency matrix and compatibility requirements

### Training

- [ ] **Training acceleration**
  - Develop 2 new CYROID-integrated courses: Cloud Security Operations, Purple Teaming
  - Build reusable CYROID range templates for each training course
  - Launch training-as-a-service: bundled CYROID access + instructor-led sessions
  - Establish training delivery cadence (monthly cohorts)
  - Begin LMS platform evaluation and selection

- [ ] **Training content pipeline**
  - Document course development framework (objectives, labs, assessments)
  - Create CYROID scenario library tied to each course module
  - Record intro/marketing content for each course offering

### Business

- [ ] **Compliance groundwork**
  - Engage FedRAMP 3PAO for readiness assessment
  - Begin CMMC Level 2 gap analysis
  - Document SSP (System Security Plan) for SOC-in-a-Box

- [ ] **Government pipeline**
  - Identify 3-5 target contract vehicles (BPAs, IDIQs, OTAs)
  - Submit SAM.gov registrations and update capability statements
  - Begin SBIR/STTR proposal research for cyber range funding

- [ ] **Customer engagement targets**
  - 10 discovery calls / product demos with prospective customers
  - 2 active proposals or RFP responses in progress
  - Build target account list (25+ gov, 25+ commercial)
  - Attend 1 conference or trade show for networking

### Operations

- [ ] **Company infrastructure**
  - Set up corporate email (domain-based) and internal comms platform (Mattermost or similar)
  - Self-hosted Git server for internal/classified repos
  - Document retention and records management system
  - Establish accounting/bookkeeping system and financial reporting
  - Legal: business entity formalization, contracts templates, NDA/MSA library
  - Insurance: general liability, E&O, cyber liability policies

- [ ] **Internal IT & security**
  - Endpoint management and security baseline for team devices
  - VPN / secure remote access for distributed team
  - Password management and MFA enforcement
  - Backup and disaster recovery plan
  - Ticket/issue tracking system for internal project management

- [ ] **SOPs & governance**
  - Standard operating procedures for core business processes
  - Incident response plan (internal)
  - Employee handbook and HR policies
  - Information security policy aligned to NIST 800-171 (for CMMC readiness)
  - Document templates and version control standards

- [ ] **Brand & marketing foundation**
  - Brand identity: logo, style guide, slide templates, one-pagers
  - Social media presence (LinkedIn, X/Twitter) and content calendar
  - Website refinement: SEO, analytics tracking, lead capture forms
  - Marketing collateral for each product and training offering

- [ ] **Hiring**
  - Platform engineering lead
  - Sales engineer (government sector)
  - Training content developer

---

## Q2 2026 (May – Jul) — Ship & Certify

### Product

- [ ] **Secure Kubernetes Core: GA release** *(gates SOC-in-a-Box and App Bundles)*
  - Production-hardened, documented, tested
  - Compliance evidence generation (CIS, NIST 800-53 controls mapping)
  - Published as standalone product with pricing

- [ ] **SOC-in-a-Box: Alpha release** *(depends on Secure K8s Core GA)*
  - Core stack integration based on architecture decisions from Q1
  - Automated deployment pipeline (single-command standup)
  - Initial alert correlation and playbook framework
  - Customer-facing operational dashboards

- [ ] **CYROID: Self-service pilot**
  - Customer self-registration and onboarding flow
  - Usage-based metering and billing integration
  - Scenario marketplace: community-contributed range templates

- [ ] **App Bundles: First bundles ship**
  - DevSecOps Bundle and DFIR Bundle available
  - One-click deployment on Secure K8s Core
  - Bundle health monitoring and update channels

### Training

- [ ] **Training expansion**
  - Launch LMS with on-demand course catalog (async + recorded)
  - Package CYROID + training as unified offering for government RFPs
  - Develop 2 additional courses: Threat Hunting Advanced, Kubernetes Security Operations
  - Begin FSC certification program design (Certified Cyber Range Operator)
  - 3+ enterprise training engagements delivered via CYROID

### Business

- [ ] **FedRAMP authorization**
  - Submit FedRAMP Ready designation package
  - Begin ATO documentation for first government customer

- [ ] **First government contract**
  - Respond to 2-3 RFPs/RFIs targeting CYROID + training
  - Pursue GSA Schedule listing or existing vehicle subcontract

- [ ] **Commercial launch**
  - Pricing and packaging finalized for all products
  - Website overhaul: product pages with demos, ROI calculator
  - Launch partner program for MSSPs and integrators

- [ ] **Customer engagement targets**
  - 20 discovery calls / product demos
  - 5 active proposals or RFP responses
  - Close first government deal + 2 commercial customers
  - Attend 2 conferences or trade shows
  - Establish 2 prime contractor relationships

### Operations

- [ ] **Marketing & advertising**
  - Paid digital advertising campaigns (LinkedIn, Google Ads targeting gov/enterprise)
  - Email marketing: newsletter, drip campaigns for leads
  - Content marketing: blog posts, whitepapers, case study framework
  - Conference/trade show calendar and sponsorship plan

- [ ] **Business operations**
  - CRM setup and sales pipeline tooling
  - Customer onboarding process documentation
  - Proposal/RFP response workflow and templates
  - Quarterly business review cadence established

- [ ] **Infrastructure evaluation: self-hosted vs. SaaS**
  - Assess GitHub/GHCR usage against API rate limits and scaling needs
  - Evaluate self-hosted alternatives (Gitea/Forgejo, Harbor for container registry)
  - Decision criteria: cost, API limits, compliance requirements, team size
  - If GitHub works at current scale, defer self-hosting; if not, plan migration for Q3

---

## Q3 2026 (Aug – Oct) — Scale

### Product

- [ ] **SOC-in-a-Box: Beta release**
  - Production pilot at 2+ customer sites
  - Automated compliance reporting (NIST, CMMC control evidence)
  - Managed service tier: FSC-operated SOC option

- [ ] **CYROID: Marketplace & integrations**
  - GovCloud deployment options (AWS, Azure)
  - LMS integration for training course to range lab handoff
  - Automated scoring and assessment engine for exercises
  - Published on cloud marketplace

- [ ] **Platform convergence**
  - Unified management plane across CYROID + SOC-in-a-Box
  - Single sign-on across all products
  - Shared observability and monitoring stack

- [ ] **App Bundles: Full catalog**
  - SOC Stack and Productivity Suite bundles ship
  - Custom bundle builder for enterprise customers
  - Automated dependency resolution and upgrade paths

### Training

- [ ] **Training brand**
  - FSC Certified Cyber Range Operator certification launches
  - 100+ students through online courses
  - Conference presence: speaking slots at 2+ industry events

### Business

- [ ] **Government traction**
  - 2+ active government contracts or task orders
  - IL4/IL5 authorization path for SOC-in-a-Box
  - Participate in CDAO or Service Cyber Component exercises with CYROID

- [ ] **Enterprise sales**
  - 5+ commercial enterprise customers
  - MSSP partner channel: 2+ partners reselling platforms
  - Case studies published from early adopters

- [ ] **Customer engagement targets**
  - 30 discovery calls / product demos
  - 8 active proposals or RFP responses
  - $5M in pipeline value
  - Attend 3 conferences; speaking slots at 2+
  - 3 prime contractor relationships

### Operations

- [ ] **Scaling operations**
  - Customer support system and SLAs defined
  - Incident response and escalation procedures for managed services
  - Internal knowledge base and runbooks
  - Financial: revenue forecasting model, unit economics analysis

- [ ] **Infrastructure self-hosting (if needed)**
  - Based on Q2 evaluation: migrate Git, container registry, and ticket management
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

### Product

- [ ] **SOC-in-a-Box: GA + SaaS tier**
  - Multi-tenant SaaS offering (FSC-hosted)
  - Self-service signup, trial environment, upgrade path
  - SOC-as-a-Service: 24/7 managed detection & response option

- [ ] **CYROID: Advanced capabilities**
  - AI-driven adversary simulation (automated red team scenarios)
  - After-action review analytics and trainee performance tracking
  - Federation: connect multiple ranges for joint exercises

- [ ] **Secure K8s Core: Ecosystem**
  - Certified partner integrations with major security vendors
  - Air-gapped deployment package for classified environments
  - Community edition (open-source base layer)

- [ ] **Developer platform**
  - Public API and SDK for CYROID and SOC-in-a-Box
  - Webhook framework for customer workflow automation
  - Infrastructure-as-code providers for automated deployment

### Training

- [ ] **Training at scale**
  - 500+ students trained (combined in-person + online)
  - 3+ FSC certifications offered
  - Training revenue as standalone business unit

### Business

- [ ] **Revenue milestones**
  - ARR targets established and tracked
  - Recurring revenue from SaaS + managed services > 40% of total
  - Expansion revenue from existing accounts

- [ ] **Government depth**
  - FedRAMP Authorized (or In Process)
  - 3+ government agency customers
  - Subcontract relationships with 2+ large defense primes

- [ ] **Market position**
  - Recognized in analyst reports (Gartner, Forrester) for cyber range
  - 10+ commercial enterprise customers
  - Active partner ecosystem (5+ MSSP/integrator partners)

- [ ] **Customer engagement targets**
  - 40 discovery calls / product demos
  - 12 active proposals or RFP responses
  - $10M in pipeline value
  - Attend 4 conferences
  - 5 prime contractor relationships

### Operations

- [ ] **Mature business operations**
  - Annual strategic planning process for 2027
  - Formalized hiring pipeline and onboarding program
  - Vendor and partnership management framework
  - Marketing: measure ROI on all channels, double down on what works

- [ ] **AI operations: maturity**
  - Self-hosted AI infrastructure for day-to-day business tasks
  - AI agents handling routine operations: scheduling, customer intake, ticket triage
  - AI-powered content generation: training materials, marketing copy, proposal drafts
  - Internal AI platform that team members can build custom workflows on
  - Evaluate integrating AI capabilities into customer-facing products

---

## Key Metrics

| Metric | Q1 Target | Q2 Target | Q3 Target | Q4 Target |
|--------|-----------|-----------|-----------|-----------|
| **Product** | | | | |
| Products at GA | 1 (CYROID) | 2 (+Secure K8s Core) | 2 (SOC beta) | 3 (+SOC-in-a-Box GA) |
| **Sales & Pipeline** | | | | |
| Discovery calls / demos | 10 | 20 | 30 | 40 |
| Active proposals / RFPs | 2 | 5 | 8 | 12 |
| Closed deals (gov) | 0 | 1 | 2+ | 3+ |
| Closed deals (commercial) | 0 | 2 | 5+ | 10+ |
| Pipeline value ($) | $500K | $2M | $5M | $10M |
| **Partnerships** | | | | |
| MSSP partners | 0 | 0 | 2 | 5+ |
| Prime contractor relationships | 1 | 2 | 3 | 5 |
| **Training** | | | | |
| Training courses available | 5 | 7 | 9 | 9+ |
| Students trained | 50 | 150 | 300 | 500+ |
| Training engagements | 2 | 5 | 10 | 15+ |
| **Operations** | | | | |
| Team size (eng + sales) | +3 | +0 | +3 | +2 |
| Conference / trade show appearances | 1 | 2 | 3 | 4 |

## Risk Register

| Risk | Impact | Mitigation |
|------|--------|------------|
| FedRAMP timeline slips | Blocks government SaaS deals | Pursue agency ATOs in parallel; sell on-prem while waiting |
| SOC-in-a-Box scope creep | Delays GA | Strict MVP scope; ship core detection first, advanced analytics later |
| Key person dependency | Single points of failure on small team | Document everything; cross-train; hire ahead of need |
| Compliance cost overruns | Cash drain from 3PAO and audit fees | Budget 20% buffer; prioritize CMMC (cheaper) before FedRAMP |
| Commercial market fit | Platforms built for gov may not resonate commercially | Validate with 3 commercial design partners before full launch |
| Ops overhead underestimated | Team burns out on admin vs. product work | Automate early; hire ops/admin support; outsource bookkeeping |

## Dependencies

```
Secure K8s Core (Beta Q1 → GA Q2)
    └── SOC-in-a-Box (Design Q1 → Alpha Q2 → Beta Q3 → GA + SaaS Q4)
    └── App Bundles (Define Q1 → Ship Q2 → Full catalog Q3)

CYROID (Live → Hardening + Training Q1 → Self-service Q2 → Marketplace Q3 → Advanced Q4)

Training (Live → Accelerate + CYROID integration Q1 → LMS + expand Q2 → Certification Q3 → Scale Q4)

Compliance (Groundwork Q1 → FedRAMP Ready Q2 → IL4/5 Q3 → Authorized Q4)

Operations (Foundation Q1 → Marketing + CRM Q2 → Support + SLAs Q3 → Mature ops Q4)

Infrastructure (GitHub/SaaS Q1 → Evaluate self-hosting Q2 → Migrate if needed Q3 → Stable Q4)

AI Operations (— Q1 → Evaluate Q2 → Foundation Q3 → Self-hosted + mature Q4)
```
