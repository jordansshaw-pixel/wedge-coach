# Healthcare IT Glossary — Buyer-Side Meaning

What these terms mean to a healthcare CEO or COO in an orthopedic surgical group — not what they mean to a technician.

Wedge Coach uses this file to (1) speak the buyer's language during DRILL mode, and (2) recognize when a user's pitch is using a term in a way the buyer would find credible vs. fluffy.

---

## EHR / EMR

**What it is:** The system that runs the practice. Schedules, documentation, billing, prescriptions, imaging integration.

**What it means to the buyer:** "When this is down, my practice does not function. Surgeons document on paper, billing stops, my schedulers can't book."

**Common ortho EHRs:** Epic, athenahealth, NextGen, Greenway (especially Intergy and Prime Suite), Modernizing Medicine (EMA), eClinicalWorks, Cerner.

**Credible pitch claim:** *"We host [specific EHR] for [N] orthopedic groups."*
**Fluff:** *"We have EHR experience."*

---

## HIPAA

**What it is:** Federal floor for protected health information (PHI) handling.

**What it means to the buyer:** "If we get breached, OCR investigates. Findings letters lead to corrective action plans. Civil monetary penalties can run $100 to $50,000 per violation, up to $1.9M per category per year."

**Credible pitch claim:** *"We've shepherded N orthopedic groups through OCR investigations. Findings closed in under [N] days."*
**Fluff:** *"We're HIPAA-compliant."* (So is every MSP. It's the floor.)

---

## HITECH

**What it is:** The breach notification rule layer on top of HIPAA. Triggers when 500+ records are breached — requires HHS notification, media notification, and listing on the HHS "Wall of Shame."

**What it means to the buyer:** "If we breach 500+ records, our practice name shows up in HHS's public breach portal. Local news picks it up. Patients call. Surgeons get nervous."

---

## SOC 2

**What it is:** AICPA attestation report (Type 1 = point-in-time, Type 2 = over a period of 6+ months) covering Trust Services Criteria — Security, Availability, Processing Integrity, Confidentiality, Privacy.

**What it means to the buyer:** "Hospital systems and ASCs increasingly require SOC 2 from their vendors and downstream practice partners. Without it, contracts walk."

**Credible pitch claim:** *"We help ortho groups achieve SOC 2 Type 2 readiness in [N] months — including the policy work, the evidence collection, and the auditor handoff."*
**Fluff:** *"We do SOC 2."*

---

## OCR Audit

**What it is:** Office for Civil Rights (HHS) — the regulator that enforces HIPAA. Audits and investigates breaches.

**What it means to the buyer:** "When OCR sends a findings letter, the practice is in the regulator's process. Closing findings is operational, expensive, and the clock is running."

---

## BAA — Business Associate Agreement

**What it is:** Required HIPAA contract layer between a covered entity (the practice) and any vendor handling PHI (the MSP, EHR vendor, hosting provider, etc.).

**What it means to the buyer:** "If our MSP isn't BAA-covered, we have a HIPAA violation just by working with them."

---

## vCIO — Virtual Chief Information Officer

**What it is:** A fractional executive-level IT advisor who sits in leadership conversations — strategy, budget, vendor decisions, audit response — at a fraction of a full-time CIO's cost.

**What it means to the buyer:** "Someone at my leadership table who actually knows IT, instead of me trying to translate technical decisions into business decisions on my own."

**Distinct from:** Help desk (tactical), MSP account manager (transactional), IT director (in-house).

---

## vCAIO — Virtual Chief AI Officer

**What it is:** Emerging fractional executive role focused on AI strategy in the practice. Where AI moves the needle (ambient scribes, RCM automation, patient-comms automation, scheduling optimization, image-analysis tooling), where it doesn't yet, and how to govern it.

**What it means to the buyer:** "My board is asking 'what's our AI strategy?' and I don't have one. A vCAIO gives me a 12-month roadmap I can actually execute."

**Credible pitch claim:** *"Our vCAIO sits with you quarterly and produces a written 12-month AI roadmap specific to orthopedic group operations."*
**Fluff:** *"We use AI."*

---

## AI SIEM

**What it is:** Security Information and Event Management platform with AI/ML for anomaly detection, dwell-time reduction, and automated response.

**What it means to the buyer:** "Faster detection of breaches in progress = smaller breach = lower fines, lower legal cost, and (when documented) lower cyber insurance premiums."

**Credible pitch claim:** *"Our AI SIEM is deployed at [specific class of institution]. Documented dwell time on average is [N hours/days] vs. industry baseline of [N]."*
**Fluff:** *"We have AI-powered security."*

---

## ASC — Ambulatory Surgical Center

**What it is:** Outpatient surgical facility. Subject to additional federal and state regulation (Medicare conditions for coverage, state licensure, accreditation by AAAHC/Joint Commission/AAAASF).

**What it means to the buyer:** "An OR-day outage costs us six-figure surgeon revenue, plus the surgeon may take cases elsewhere if we get a reputation for tech failures."

---

## MIPS — Merit-Based Incentive Payment System

**What it is:** CMS quality-reporting program affecting Medicare Part B reimbursement. Reporting categories: Quality, Promoting Interoperability, Improvement Activities, Cost.

**What it means to the buyer:** "If we miss MIPS reporting, Medicare reimbursement drops by [up to 9%]. IT sits underneath the Promoting Interoperability category."

---

## PE-Backed

**What it is:** Practice owned (in whole or in part) by a private equity sponsor. Common in orthopedic roll-ups.

**What it means to the buyer (the CEO):** "I report to a board. Operational metrics matter at every QBR. EBITDA matters at exit. IT chaos in QofE (Quality of Earnings) findings can cost millions on multiple."

---

## Asset Management — 3-Tier with One Source of Truth

**What it is:** Operational discipline that combines physical assets (devices, infrastructure), logical assets (accounts, identities, software), and configuration assets (settings, policies) into a single inventory with consistent naming, ownership, and lifecycle.

**What it means to the buyer:** "When OCR or SOC 2 auditors ask 'show me everything connected to your environment,' there is one report, not ten spreadsheets in disagreement."

**Credible pitch claim:** *"Our 3-tier asset model with one source of truth means audit prep takes hours, not weeks."*
**Fluff:** *"We do asset management."*

---

## 99.999% Uptime ("Five Nines")

**What it is:** ~5.26 minutes of unplanned downtime per year.

**What it means to the buyer:** "EHR will not be the reason a clinic day collapses or a surgical schedule slips."

**Credibility test:** Five nines is a *measured outcome over a defined period in a documented environment*, not an aspiration. A pitch claim of 99.999% uptime should be backed by what was measured, where, and over what period. Otherwise it's marketing.

---

## Cyber Insurance Posture

**What it means to the buyer:**

- **Premium amount and direction (rising/falling):** signals risk perception by the carrier
- **Sub-limits and exclusions:** what the policy will not cover (often: ransomware payments, social engineering)
- **Renewal questionnaire scoring:** the carrier's view of your controls maturity

**Credible pitch claim:** *"We've documented insurance premium reductions for clients at renewal. Carriers price our environments lower because of [specific controls evidence]."*
**Fluff:** *"We help reduce your cyber risk."*

---

## Claim-credibility framework

When a user's pitch makes a claim, the question to ask is:

| Dimension | Credible | Fluff |
|---|---|---|
| **Specific** | Names a system, group, person, or metric | Generic ("comprehensive") |
| **Numbered** | Includes a count, percentage, or time | "Many," "significant," "improved" |
| **Time-bound** | Includes a period or deadline | "Ongoing," "long-term" |
| **Falsifiable** | Could in principle be checked | Cannot be checked |
| **Translatable to a CFO** | The buyer can repeat to the board | The buyer cannot repeat to the board |

A wedge claim should clear at least 4 of 5. A claim that clears 0–2 is fluff and the diagnosis should call it out.
