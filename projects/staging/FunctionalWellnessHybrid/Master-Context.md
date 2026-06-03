# FunctionalWellnessHybrid — Staging Master Context

**Project Name:** FunctionalWellnessHybrid
**Category:** Business (medical practice business-model transformation)
**Owner:** SammyD (Administrator, Chandra Britt Armstrong MD, LLC)
**Clinical Lead:** Chandra Britt Armstrong, MD
**Stage:** Staging (Ideation & Preparation)
**Last Updated:** 2026-06-03

---

## Project Vision

Transform Chandra Britt Armstrong MD, LLC (CBA) from a ~98%-insurance-dependent independent family practice into a **hybrid medical business** that pairs an optimized insurance/Medicare core with high-margin, direct-pay functional-wellness and rehabilitation services (laser, EMSELLA, EMSCULPT NEO, IV/infusion therapy, PIR), recurring care-management revenue (APCM/RPM), and part-time mental health. The model monetizes CBA's existing 1,000+ senior patient panel more effectively, reduces dependence on declining payer reimbursement, fixes broken billing/collections, and produces predictable cash flow — with a 12-month target of **$1M+ gross revenue** and a path to retiring practice debt while honoring the Citizens Trust Bank DCR ≥ 1.2 covenant.

---

## Staging Phase Objectives

During staging, we develop three foundation documents (all three are drafted in this file and refined collaboratively before promotion to a full project via `PROJECT_MEMORY_INIT.md`):

1. **Project Context** — Vision, goals, target market, success metrics, dependencies, assumptions/constraints.
2. **Architecture/Business Model Design** — Revenue streams, service-line blueprint & economics, org/staffing, operational workflows, OpEx-reduction plan, compliance/risk framework.
3. **Release Plan** — Phased roadmap with epics, milestones, acceptance criteria, and risks — from today to the $1M / debt-payoff goal.

---

## Staging Roadmap

### Document 1: Project Context
**Status:** [ ] Not Started  [x] In Progress (v0.9 draft)  [ ] Complete

### Document 2: Architecture/Business Model Design
**Status:** [ ] Not Started  [x] In Progress (v0.9 draft)  [ ] Complete

### Document 3: Release Plan
**Status:** [ ] Not Started  [x] In Progress (v0.9 draft)  [ ] Complete

> These drafts are AI-generated from owner context + market research + advisor frameworks. They are starting points for owner review, not final commitments. Edit any section, then we lock it.

---

## Key Commands During Staging

- **Continue from a document:** "Continue with Document {1|2|3}"
- **Review progress:** "Where are we in staging?"
- **Save and close:** "Close staging session"
- **Promote to full project:** "Initialize FunctionalWellnessHybrid via PROJECT_MEMORY_INIT.md"

---

## Available Agents (Activated for this project)

Domain-expert advisors are distributed into this project's department folders. Read the relevant `{Department}/agents/{Source}-advisor.md` before working in that domain.

| Domain | Department Folder | Agent Files | Applied To |
|---|---|---|---|
| Finance & Investment | `Finance/agents/` | Finance-AGENT/advisor, Investment-AGENT/advisor | Cash-flow model, DCR covenant, unit economics, CapEx (devices) vs lease, debt paydown |
| Marketing, Market Dev & Sales | `Marketing/agents/` | Marketing-, Market-Development-, Sales- AGENT/advisor | Cash-line demand gen, senior patient activation, membership packaging, beachhead segments |
| Legal | `Legal/agents/` | Legal-AGENT/advisor | HIPAA, Medicare opt-out, AKS/Stark, fee-splitting, GA laser supervision, LCSW 1099, scope of practice |
| Security & Infrastructure | `Security/agents/` | Infrastructure-AGENT/advisor | PHI security, EHR/RPM data, device/network |
| Executive & Strategy | `Executive/agents/` | Strategy-, PMO-, Growth-n-Revenue-, Human-Psychology- AGENT/advisor | Transformation strategy, portfolio/critical path, revenue system, patient & staff behavior change |
| Operations | `Operations/agents/` | Operations-, Infrastructure-, Automation- AGENT/advisor | RCM fix, workflows, capacity (8 PIR chairs), OpEx reduction, scheduling automation |
| Product Development | `Product_Development/agents/` | Product-Development-, Software-Development- AGENT/advisor | Service-line "product" design, tech stack (EHR/RPM/booking/payments) |
| Tech Support | `TechSupport/agents/` | Tech-Support-AGENT/advisor | Patient/device support workflows |
| People & Culture | `People-n-Culture/agents/` | People-n-Culture-AGENT/advisor | Staffing model, NP/MA cross-training, 1099 LCSW, comp design |

**Source of truth:** `AI_Memory_Open/Memory_Agents/`. Refresh local copies if the source updates.

**Advisors consulted in producing the drafts below:** Finance, Growth-n-Revenue, Strategy, PMO, Operations, Marketing, Legal, Human-Psychology (per AI Memory Agent Integration Protocol).

---

## Institutional Dependencies (which apply)

- **Finance:** $450k Citizens Trust Bank refi; DCR ≥ 1.2 covenant w/ close monitoring; constrained working capital; device CapEx vs. lease decisions. **(Critical)**
- **Legal/Regulatory:** HIPAA; Medicare rules for APCM/RPM and any cash-pay opt-out; Anti-Kickback/Stark; GA fee-splitting & corporate-practice-of-medicine; cosmetic laser physician supervision/delegation rules; LCSW 1099 scope & supervision; PIR licensing under Well Cell. **(Critical)**
- **Operations:** Revenue cycle management (root cause of cash-flow pain); scheduling; 8-chair PIR capacity; device throughput. **(Critical)**
- **Marketing:** Senior-panel activation, cash-line demand generation, brand for functional wellness/rehab, community/non-profit halo. **(High)**
- **Executive/Strategy:** Sequencing the pivot without destabilizing the insurance core. **(High)**
- **Security:** PHI protection across EHR/RPM/payments. **(Medium)**
- **People & Culture:** Thin staff (NP Mon/Tue), cross-training, 1099 LCSW. **(High)**

---

# Document 1: Project Context

### Vision & Goals

**Vision Statement:** A community-rooted, physician-led hybrid practice that earns durable margin from direct-pay functional wellness and recurring care management while stabilizing — not abandoning — its Medicare/insurance core.

**Primary Goal (12-month, anchor metric):** **$1M+ gross revenue** within the year, with enough free cash flow to service and accelerate payoff of practice debt while keeping **DCR ≥ 1.2** every reporting period.

**Secondary Goals:**
- Lift cash-pay (non-insurance) revenue from ~2% to **≥ 25%** of gross within 12 months (reduce payer dependence).
- Repair the revenue cycle: **clean-claim ≥ 95%, denial < 5%, A/R days < 40, net collection ≥ 95%** (industry benchmarks).
- Stand up **recurring** revenue: APCM/RPM enrollment of the eligible senior panel + PIR + memberships.
- Launch the senior **fall-prevention / mobility / mental-health non-profit** as a mission + referral/halo engine.

### Target Audience / Users

- **Core (existing):** 1,000+ panel, ~98% African American, majority age 60+. Primary care + chronic-disease management; high APCM/RPM eligibility; candidates for PIR (glucose/metabolic), incontinence (EMSELLA), mobility/strength (EMSCULPT NEO, rehab), and IV/wellness.
- **Adjacent cash-pay (new):** Working-age family members and the broader DeKalb/Decatur/Stonecrest community for aesthetics (laser hair removal), body contouring, IV wellness, and self-pay mental health.
- **Problem solved:** For seniors — affordable, trusted, culturally-aligned care that improves mobility, continence, metabolic health, and quality of life. For the practice — margin and predictable cash that insurance reimbursement no longer provides.

### Success Metrics (KPIs)

- **Financial:** Gross revenue run-rate to $1M+; cash-pay % of revenue ≥ 25%; monthly DCR ≥ 1.2; days cash on hand; debt balance trending down.
- **Revenue cycle:** Clean-claim rate, denial rate, A/R days, net collection rate.
- **Recurring:** # patients enrolled in APCM (G0556/57/58) and RPM; PIR chair utilization (of 8); active memberships.
- **Service lines:** Revenue & gross margin per line; device utilization hrs; revenue/clinical hour (target $600–$1,000/hr for device services).
- **Mission:** Non-profit launched; fall-risk screenings completed; downstream referrals.

### Assumptions & Constraints

- **Assumption:** A meaningful share of the senior panel has willingness/ability to pay for select cash services (continence, mobility, metabolic) and qualifies for APCM/RPM — to be validated by a panel survey/segmentation (cash-pay for seniors requires explicit willingness-to-pay modeling).
- **Assumption:** Most device cash services run at 40–80% gross margin with low consumables (lasers/IV highest; body contouring mid).
- **Constraint:** DCR ≥ 1.2 covenant + close lender monitoring → discipline on CapEx and overhead; prefer lease/financed devices and phased spend.
- **Constraint:** Clinical capacity is thin (NP Mon/Tue; one MD) → sequencing must not overload providers; delegate device services to qualified staff under GA supervision rules.
- **Constraint:** Limited working capital until RCM is fixed → Phase 0 prioritizes collections.
- **Constraint:** Regulatory — Medicare opt-out/cash rules, AKS/Stark, GA laser supervision, LCSW scope — gate several lines; Legal advisor must clear before launch.

---

# Document 2: Architecture / Business Model Design

### Business Model Overview

CBA moves from a **single-engine** (fee-for-service insurance) model to a **four-engine hybrid**:

1. **Optimized Insurance/Medicare Core** — same clinical care, but with a fixed revenue cycle so earned money is actually collected (the fastest "new" revenue is stopping leakage). Hybrid practices average ~23% higher revenue than single-model peers.
2. **Recurring Care Management** — APCM (G0556 $15.20 / G0557 $48.84 / G0558 $107.07 per patient/month) + RPM on the eligible senior panel; predictable monthly revenue layered on patients already in the practice.
3. **Direct-Pay Functional Wellness & Rehab** — laser hair removal (Soprano Titanium), EMSELLA (incontinence), EMSCULPT NEO (muscle/mobility), IV/infusion (foundational wellness IVs, targeted injections), and PIR (Well Cell licensee, 8 chairs). High margin, low admin, no payer dependence.
4. **Self-Pay Mental Health** — part-time 1099 LCSW counseling (cash + select payer), serving a panel with high behavioral-health need.

Mission halo: the **senior fall-prevention/mobility/mental-health non-profit** drives screenings, community trust, and referrals into the rehab/wellness lines.

### Revenue Streams & Illustrative Unit Economics

> Directional, assumption-driven (Finance advisor: avoid false precision — these are planning ranges to validate, not forecasts). Margins from market research; volumes to be set with the owner.

| Stream | Pricing (typical) | Gross margin | Recurring? | Notes |
|---|---|---|---|---|
| Insurance/Medicare core (fixed RCM) | per visit/FFS | n/a (collections recovery) | No | Biggest near-term lift = collecting what's already earned |
| APCM (G0556/57/58) | $15.20 / $48.84 / $107.07 /pt/mo | High (low marginal cost) | **Yes** | Scales with eligible panel enrollment |
| RPM | ~$40–$110 /pt/mo (CPT 99453–99458) | High | **Yes** | Pairs with APCM & chronic disease panel |
| PIR (Well Cell) | program/visit pricing | Mid–High | **Yes** | 8 chairs; utilization is the lever |
| Memberships (functional wellness) | $75–$150 /mo (DPC-style benchmark) | High | **Yes** | Bundles discounts/priority for cash services |
| Laser hair removal | per package/series | **High** (minimal consumables; device recoups in ~7–8 mo) | Repeat series | Strong margin + rebookings |
| EMSELLA (incontinence) | per series (e.g., 6) | High | Repeat/maintenance | High senior relevance; device throughput |
| EMSCULPT NEO (muscle/mobility) | per series | ~40–50% (machine ~$150k; pads ~$10k/300–450 tx) | Repeat/maintenance | Tie to rehab/mobility positioning |
| IV / infusion / injections | ~$100–$400 (NAD+ $400–$1,000); supplies ~$10 | 50–80%+ | Repeat | "Foundational wellness IVs" + targeted injections |
| Mental health (LCSW, 1099) | cash + select payer | Mid (1099 cost) | Repeat | Part-time; low fixed cost |

**Target revenue/clinical hour for device services:** $600–$1,000 (med-spa benchmark).

### Service-Line Blueprint (how each works end-to-end)

For each line: eligibility/indication → consult/booking → consent & payment (upfront for cash) → delivery (provider/qualified staff under supervision) → rebooking/series/membership → outcome tracking. Standardize as repeatable "products" (Product-Development advisor) with fixed protocols, pricing sheets, and consent forms.

### Organization & Staffing Model

- **MD (Dr. Armstrong):** medical director, supervision, complex care, device oversight per GA rules.
- **NP (Terri Scott, Mon/Tue):** PIR program + select visits; expand days as utilization justifies.
- **MA/clinical staff:** cross-trained to run device services (laser/EMSELLA/EMSCULPT) and IVs under supervision — keeps labor (50–60% of overhead) efficient via cross-training, per-diem/part-time where possible (Operations advisor).
- **1099 LCSW:** part-time mental health (variable cost, no fixed overhead).
- **RCM:** insource a competent biller OR replace/right-size the third-party billing vendor with strict SLAs and weekly denial-feedback loops (root cause of current pain).
- **Front desk:** scheduling + cash collection at point of service + membership sales.

### Operational Workflows & OpEx-Reduction Plan

Revenue up **and** cost down (both were explicit asks):

**Revenue cycle (highest priority):** clean-claim ≥ 95%, denial < 5% (top performers < 3%), A/R days < 40 (high performers < 30), net collection ≥ 95%. Weekly denial review with documented root-cause fixes; eligibility verification at scheduling; point-of-service collection.

**OpEx reduction (Operations advisor / Lean):**
- Labor: cross-train staff, team-based care, per-diem/part-time for device/MA roles (labor = 50–60% of overhead).
- Supplies/inventory: just-in-time ordering for IV/injectables and device consumables; bulk where margin-accretive (injectables 70–80% margin).
- Contracts/subscriptions: periodic review & renegotiation of vendor/EHR/insurance contracts.
- Automation (Automation advisor): online booking, automated reminders (cut no-shows), digital intake/consent, automated payment + membership billing.
- Facility/energy: low-cost efficiency wins (LED/HVAC) where applicable.
- Outsource non-core (janitorial/IT) only where cheaper than in-house.

**Capacity:** drive PIR 8-chair utilization and device hours as the throughput levers (idle devices destroy unit economics).

### Technology Stack (to confirm)

EHR + claims; RPM platform; online scheduling; digital intake/consent; payments + recurring membership billing; light CRM for cash-line marketing & recall. Prefer integrations over point tools to limit admin overhead. (Enterprise OS deferred at setup — revisit; Zoho connector available.)

### Compliance & Risk Framework (Legal advisor — clear before launch)

- **HIPAA / PHI security** across EHR/RPM/payments.
- **Medicare:** APCM/RPM documentation & consent; cash-pay/opt-out rules for Medicare-covered services (don't bill cash for covered services improperly).
- **AKS / Stark / fee-splitting / corporate practice of medicine (GA):** membership and referral structures, non-profit relationship.
- **GA cosmetic laser/device rules:** physician supervision/delegation for laser & energy devices.
- **Scope of practice:** NP and delegated MA device duties; **LCSW 1099** scope, supervision, billing.
- **PIR:** Well Cell license terms & medical oversight.
- **Consents, pricing transparency, and refund policy** for all cash services.

---

# Document 3: Release Plan

### Release Overview

- **Release:** Phase 1.0 — "Hybrid Pivot to $1M"
- **Window:** June 2026 → May 2027 (12 months)
- **Success Criteria:** $1M+ gross revenue run-rate; cash-pay ≥ 25% of gross; DCR ≥ 1.2 every reporting period; RCM KPIs in target band; recurring revenue (APCM/RPM/PIR/memberships) established; non-profit launched.
- **Sequencing principle (Strategy + PMO advisors):** Fix the cash engine first (collect what's earned), then layer recurring revenue on the existing panel, then add high-margin cash lines, then scale & optimize. Don't destabilize the insurance core while pivoting.

### Epics (major work streams)

**Epic A — Revenue Cycle Repair & Financial Control** *(Operations, Finance)*
Fix billing/collections; establish DCR monitoring and a rolling cash-flow model. *Outcome:* clean-claim ≥ 95%, denial < 5%, A/R days < 40, net collection ≥ 95%; monthly DCR dashboard. *Dependencies:* biller/vendor decision, EHR/claims access.

**Epic B — Recurring Care Management (APCM + RPM)** *(Finance, Operations, Legal)*
Segment eligible seniors; enroll into APCM (G0556/57/58) + RPM with consent & workflows. *Outcome:* recurring monthly per-patient revenue scaling with enrollment. *Dependencies:* documentation/consent, RPM platform, panel segmentation.

**Epic C — PIR Optimization** *(Operations, Finance)*
Drive utilization of the 8 PIR chairs (scheduling, recall, NP capacity). *Outcome:* chair utilization target met; PIR contribution margin positive. *Dependencies:* Well Cell terms, NP days.

**Epic D — Cash Service Lines Launch** *(Product-Dev, Operations, Legal, Finance)*
Stand up laser, EMSELLA, EMSCULPT NEO, IV/injection as standardized "products" (protocols, pricing, consent, payment, staff training under supervision). *Outcome:* device hours booked; revenue/clinical hour $600–$1,000; line-level gross margin tracked. *Dependencies:* device acquisition (lease vs buy), GA supervision compliance, staff training.

**Epic E — Membership & Packaging** *(Growth-n-Revenue, Marketing, Finance)*
Design membership tiers/packages ($75–$150/mo benchmark) bundling cash-service discounts & priority. *Outcome:* active recurring memberships; higher revenue/patient. *Dependencies:* recurring billing, pricing approval, legal review.

**Epic F — Mental Health (1099 LCSW)** *(Legal, People-n-Culture, Operations)*
Contract part-time LCSW; scope, supervision, billing, scheduling. *Outcome:* counseling line live with low fixed cost. *Dependencies:* LCSW hire, payer/cash setup.

**Epic G — Demand Generation & Patient Activation** *(Marketing, Human-Psychology, Sales)*
Activate existing senior panel (recall, education, trust-based messaging) + community acquisition for aesthetics/wellness; willingness-to-pay survey. *Outcome:* booked consults per line; CAC tracked; panel survey complete. *Dependencies:* CRM/recall, brand assets.

**Epic H — Senior Wellness Non-Profit** *(Strategy, Legal, Marketing)*
Form non-profit (fall prevention, mobility, mental health for AA seniors); screenings + referral halo. *Outcome:* entity formed; first screenings; referral pathway to rehab/wellness lines. *Dependencies:* formation/legal, partnerships.

**Epic I — OpEx Reduction & Automation** *(Operations, Automation, Finance)*
Cross-training, JIT inventory, contract renegotiation, booking/reminder/payment automation. *Outcome:* overhead ratio down; no-shows down; admin hours down. *Dependencies:* tech stack, staff buy-in.

### Representative User Stories (with acceptance criteria)

- **A:** *As the administrator, I want a weekly denial-root-cause report so denials drop below 5%.* **AC:** weekly report live; denial trend < 5% within 90 days; each denial reason has a documented fix.
- **B:** *As Dr. Armstrong, I want eligible seniors enrolled in APCM with compliant consent so we earn recurring monthly revenue.* **AC:** segmentation complete; consent workflow approved by Legal; first cohort billing G0556/57/58.
- **D:** *As a patient, I want to book and pay for a laser/EMSELLA series online so I can start treatment quickly.* **AC:** online booking + upfront payment live; consent captured; staff trained & supervised per GA rules.
- **E:** *As a member, I want a monthly plan that discounts wellness services so I get ongoing value.* **AC:** ≥1 tier live with recurring billing; legal-reviewed; first members enrolled.
- **I:** *As front desk, I want automated reminders so no-shows fall.* **AC:** reminders live; no-show rate down vs. baseline.

### Milestones

| Milestone | Target | Objective |
|---|---|---|
| **M1 — Stabilize** | Month 1–2 (Jun–Jul 2026) | RCM baseline + fixes underway; DCR dashboard live; biller/vendor decision; panel data pulled |
| **M2 — Recurring on** | Month 3 (Aug 2026) | APCM/RPM first cohort billing; PIR utilization plan executing |
| **M3 — First cash lines** | Month 4–5 (Sep–Oct 2026) | Laser + EMSELLA + IV live with payments & compliance; revenue/hr tracked |
| **M4 — Body contouring + memberships** | Month 6–7 (Nov–Dec 2026) | EMSCULPT NEO live; membership tiers launched |
| **M5 — Mental health + scale** | Month 8–9 (Jan–Feb 2027) | LCSW live; demand-gen engine scaling cash lines; non-profit formed |
| **M6 — $1M & optimize** | Month 10–12 (Mar–May 2027) | $1M+ run-rate; cash-pay ≥ 25%; OpEx reductions banked; debt paydown accelerating; non-profit screenings underway |

### Risks & Mitigation (PMO risk register seed)

- **R1 — RCM fix slips / vendor underperforms (High/High).** *Mitigation:* dual-track (insource backup); strict SLA + weekly KPIs; this is the critical path — do not let it slip.
- **R2 — DCR covenant breach from CapEx/overhead (High/Med).** *Mitigation:* lease/finance devices; phase spend; monthly DCR check before each purchase; Finance gate.
- **R3 — Senior cash-pay willingness lower than assumed (Med/Med).** *Mitigation:* validate with panel survey before heavy spend; lead with continence/mobility/metabolic (highest senior relevance); memberships to spread cost.
- **R4 — Clinical capacity bottleneck (Med/High).** *Mitigation:* delegate device services to trained staff under supervision; add NP days only as utilization justifies.
- **R5 — Regulatory misstep (laser supervision, Medicare cash, AKS/LCSW) (Med/High).** *Mitigation:* Legal advisor clears each line before launch; documented consents & policies.
- **R6 — Device under-utilization (Med/High).** *Mitigation:* tie devices to recall + memberships + non-profit referrals; track revenue/hour weekly.

---

## How to Use This File

1. Reference this Master-Context at the start of every staging session.
2. Update the Status fields and Document drafts as we refine them.
3. Log decisions in `decisions-learnings/` and index in `Key-Decisions.md`; update `NextSteps.md`.
4. When all three documents are owner-approved, run `PROJECT_MEMORY_INIT.md` to promote to a full project.

## Next Steps

1. **Owner review** of the three drafts — correct any economics, scope, or sequencing.
2. **Validate assumptions:** panel APCM/RPM eligibility count; senior willingness-to-pay; current RCM baseline numbers; device acquisition terms.
3. **Legal pre-clear** the gated lines (laser supervision, Medicare/cash, memberships, LCSW, non-profit).
4. Then say **"Initialize FunctionalWellnessHybrid via PROJECT_MEMORY_INIT.md"** to launch the full project.
