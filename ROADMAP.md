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

## Q1 2026 (Feb – Apr) — Foundation

### Product

- [ ] **CYROID: Enterprise hardening + training integration**
  - Multi-tenant isolation and RBAC overhaul
  - API versioning (v1 stable) and OpenAPI docs
  - Telemetry pipeline (usage metrics, range health dashboards)
  - Training-mode features: guided lab walkthroughs, progress tracking, exercise scoring
  - Pre-built range templates for each FSC training course

- [ ] **SOC-in-a-Box: Alpha release**
  - Core stack integration: SIEM (Wazuh/Elastic), EDR agent, threat intel feed
  - Helm chart packaging with Secure K8s Core as the base layer
  - Internal dogfooding on FSC infrastructure

- [ ] **Secure Kubernetes Core: Beta**
  - Zero Trust network policies, OPA/Gatekeeper admission control
  - Hardened node images (CIS benchmarks)
  - GitOps bootstrap (Flux/ArgoCD) with sealed secrets

- [ ] **App Bundles: Define catalog**
  - Finalize bundle compositions (DevSecOps, DFIR, SOC Stack, Productivity)
  - Helm/Kustomize packaging standard
  - Dependency matrix and compatibility testing framework

### Business

- [ ] **Compliance groundwork**
  - Engage FedRAMP 3PAO for readiness assessment
  - Begin CMMC Level 2 gap analysis
  - Document SSP (System Security Plan) for SOC-in-a-Box

- [ ] **Government pipeline**
  - Identify 3-5 target contract vehicles (BPAs, IDIQs, OTAs)
  - Submit SAM.gov registrations and update capability statements
  - Begin SBIR/STTR proposal research for cyber range funding

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
  - Hire training content developer

- [ ] **Hiring**
  - Platform engineering lead (K8s, Helm, Go/Rust)
  - Sales engineer (government sector)
  - Training content developer

---

## Q2 2026 (May – Jul) — Ship & Certify

### Product

- [ ] **SOC-in-a-Box: Beta release**
  - Automated deployment pipeline (single-command standup)
  - Alert correlation engine and playbook framework
  - Customer-facing dashboards (Grafana-based)
  - Integration testing with Secure K8s Core

- [ ] **Secure Kubernetes Core: GA release**
  - Production-hardened, documented, tested
  - Compliance evidence generation (CIS, NIST 800-53 controls mapping)
  - Published as standalone product with pricing

- [ ] **CYROID: Self-service pilot**
  - Customer self-registration and onboarding flow
  - Usage-based metering and billing integration (Stripe/AWS Marketplace)
  - Scenario marketplace: community-contributed range templates

- [ ] **App Bundles: First bundles ship**
  - DevSecOps Bundle and DFIR Bundle available
  - One-click deployment on Secure K8s Core
  - Bundle health monitoring and update channels

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

- [ ] **Training expansion**
  - Launch LMS with on-demand course catalog (async + recorded)
  - Package CYROID + training as unified offering for government RFPs
  - Develop 2 additional courses: Threat Hunting Advanced, Kubernetes Security Operations
  - Begin FSC certification program design (Certified Cyber Range Operator)
  - 3+ enterprise training engagements delivered via CYROID

---

## Q3 2026 (Aug – Oct) — Scale

### Product

- [ ] **SOC-in-a-Box: GA release**
  - Production deployment at 2+ customer sites
  - Automated compliance reporting (NIST, CMMC control evidence)
  - Managed service tier: FSC-operated SOC option

- [ ] **CYROID: Marketplace & integrations**
  - AWS GovCloud and Azure Government deployment options
  - LMS integration for training course <> range lab handoff
  - Automated scoring and assessment engine for exercises
  - Published on AWS Marketplace

- [ ] **Platform convergence**
  - Unified management plane across CYROID + SOC-in-a-Box
  - Single identity provider (SSO/SAML) across all products
  - Shared observability stack

- [ ] **App Bundles: Full catalog**
  - SOC Stack and Productivity Suite bundles ship
  - Custom bundle builder for enterprise customers
  - Automated dependency resolution and upgrade paths

### Business

- [ ] **Government traction**
  - 2+ active government contracts or task orders
  - IL4/IL5 authorization path for SOC-in-a-Box
  - Participate in CDAO or Service Cyber Component exercises with CYROID

- [ ] **Enterprise sales**
  - 5+ commercial enterprise customers
  - MSSP partner channel: 2+ partners reselling platforms
  - Case studies published from early adopters

- [ ] **Training brand**
  - FSC Certified Cyber Range Operator certification launches
  - 100+ students through online courses
  - Conference presence: speaking slots at 2+ industry events

- [ ] **Hiring**
  - Customer success / support engineer
  - Training content developer
  - Business development (commercial sector)

---

## Q4 2026 (Nov – Jan 2027) — Compound

### Product

- [ ] **SOC-in-a-Box: SaaS tier**
  - Multi-tenant SaaS offering (FSC-hosted)
  - Self-service signup, trial environment, upgrade path
  - SOC-as-a-Service: 24/7 managed detection & response option

- [ ] **CYROID: Advanced capabilities**
  - AI-driven adversary simulation (automated red team scenarios)
  - After-action review analytics and trainee performance tracking
  - Federation: connect multiple ranges for joint exercises

- [ ] **Secure K8s Core: Ecosystem**
  - Certified partner integrations (Palo Alto, CrowdStrike, Splunk)
  - Air-gapped deployment package for classified environments
  - Community edition (open-source base layer)

- [ ] **Developer platform**
  - Public API and SDK for CYROID and SOC-in-a-Box
  - Webhook framework for customer workflow automation
  - Terraform/Pulumi providers for infrastructure-as-code deployment

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

- [ ] **Training at scale**
  - 500+ students trained (combined in-person + online)
  - 3+ FSC certifications offered
  - Training revenue as standalone business unit

---

## Key Metrics

| Metric | Q1 Target | Q2 Target | Q3 Target | Q4 Target |
|--------|-----------|-----------|-----------|-----------|
| Products at GA | 1 (CYROID) | 2 (+Secure K8s Core) | 3 (+SOC-in-a-Box) | 4 (+SaaS tier) |
| Government contracts | 0 | 1 | 2+ | 3+ |
| Commercial customers | — | 2 | 5+ | 10+ |
| Training courses available | 5 | 7 | 9 | 9+ |
| Students trained | 50 | 150 | 300 | 500+ |
| Training engagements | 2 | 5 | 10 | 15+ |
| MSSP partners | 0 | 0 | 2 | 5+ |
| Team size (eng + sales) | +2 | +1 | +3 | +2 |

## Risk Register

| Risk | Impact | Mitigation |
|------|--------|------------|
| FedRAMP timeline slips | Blocks government SaaS deals | Pursue agency ATOs in parallel; sell on-prem while waiting |
| SOC-in-a-Box scope creep | Delays GA | Strict MVP scope; ship alert triage first, advanced analytics later |
| Key person dependency | Single points of failure on small team | Document everything; cross-train; hire ahead of need |
| Compliance cost overruns | Cash drain from 3PAO and audit fees | Budget 20% buffer; prioritize CMMC (cheaper) before FedRAMP |
| Commercial market fit | Platforms built for gov may not resonate commercially | Validate with 3 commercial design partners before full launch |

## Dependencies

```
Secure K8s Core (Beta Q1 → GA Q2)
    └── SOC-in-a-Box (Alpha Q1 → Beta Q2 → GA Q3 → SaaS Q4)
    └── App Bundles (Define Q1 → Ship Q2 → Full catalog Q3)

CYROID (Live → Enterprise hardening Q1 → Self-service Q2 → Marketplace Q3 → Advanced Q4)

Training (Live → Accelerate + CYROID integration Q1 → LMS + expand Q2 → Certification Q3 → Scale Q4)

Compliance (Groundwork Q1 → FedRAMP Ready Q2 → IL4/5 Q3 → Authorized Q4)
```
