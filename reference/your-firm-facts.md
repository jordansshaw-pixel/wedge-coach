# Your Firm Facts — Source of Truth for Proof Points

> **READ THIS FIRST IF YOU'RE NOT THE ORIGINAL AUTHOR:**
> This file holds the *seller's* firm-specific proof points that Wedge Coach pulls from when writing the **MISSING SPECIFIC** section of a diagnosis. The current contents reflect **True North ITG**'s positioning. If you're using Wedge Coach for a different firm, **replace the entire body of this file with your own firm's facts** — same headings, your specifics. The rest of the folder will continue to work unchanged.

---

## Firm: True North ITG

### Positioning (one line)
Healthcare IT MSP and EHR hosting provider with deep specialization in **orthopedic surgical groups in the 50–500 seat range**.

---

### Verifiable differentiators

The diagnoses in `rules.md` instruct Wedge Coach to surface **MISSING SPECIFICS** from the list below when the user's pitch was generic. Treat each item as a real, available proof point — not aspirational.

#### Vertical depth
- Long-term operating experience inside orthopedic surgical IT environments
- Vertical-specific support standard operating procedures (SOPs) built for orthopedic clinical workflows — not adapted from generic healthcare templates
- Deep working knowledge of clinical-data structures inside the major orthopedic EHR/PM systems (technicians who can troubleshoot inside the data model, not just at the application surface)
- Internal claim style: *"We know your EHR better than your vendor's L1 support does."* This claim is credible when backed by specific named systems and example incidents — name them when using this in pitches.

> **TODO for the user:** Fill in the *exact numbers* — # of orthopedic groups served, # of EHR instances hosted, # of years specifically in ortho. Wedge Coach will surface these as Missing Specifics during diagnoses.

#### Compliance posture
- Specialists on staff who guide CEOs and COOs through HIPAA and SOC 2 audits
- Operational stance: *we don't sell compliance, we shepherd you through it*
- Track record of closing OCR findings letters within defined windows for client groups

> **TODO for the user:** Add specific examples of audit shepherding — # of HIPAA audits supported, average findings-closure time, # of SOC 2 Type 2 attestations achieved with clients.

#### Security
- Proprietary AI SIEM platform also deployed at top-tier hospitals and government agencies
- Documented client-side reductions in cyber insurance premiums attributable to controls evidence produced by the platform
- Internal claim style: *"Proven, not fluff."* Credibility requires the receipts — named carriers, named premium-reduction percentages, named comparison periods.

> **TODO for the user:** Add the AI SIEM platform's product name (if it's a named brand the buyer can verify), 1–2 specific client examples (anonymized is fine — "a 240-seat orthopedic group"), and the verifiable premium-reduction metrics.

#### Founder credibility
- Firm CEO holds **CISSP-ISSAP** (Information Systems Security Architecture Professional) certification — a security-architecture credential, not a sales credential
- Lead-from-the-front model: CEO personally reviews every orthopedic client's environment before onboarding
- Distinguishing claim style: *"Our CEO is a security architect, not an MSP owner who hires security people."*

> **TODO for the user:** **VERIFY THE EXACT CREDENTIAL NAME.** The user's brief said "CISP Architecture Certified." There is no widely recognized cert by that exact name; CISSP-ISSAP is the closest match (CISSP with the Architecture concentration) and is what's been written here. If the actual credential is different (e.g., CCSP, CISM, GIAC GDSA, SABSA, TOGAF, or a vendor-specific architecture cert), correct this single line and Wedge Coach will use the correct one.

#### Service stack
- 3-tiered asset management model with **one source of truth** — combining physical, logical, and configuration assets into a single, audit-ready inventory
- Operational outcome: audit prep takes hours, not weeks
- Distinguishing claim style: *"Three tiers of assets, one report. When OCR or SOC 2 auditors ask, you don't open spreadsheets."*

> **TODO for the user:** Briefly describe what the three tiers are (e.g., Tier 1 = physical/devices, Tier 2 = logical/identity/software, Tier 3 = configuration/policy) and the name of the single source of truth (CMDB platform, custom system, etc.) if it's a named tool the buyer can verify.

#### Infrastructure
- Owned/operated data centers (not pure cloud reseller)
- Documented **99.999% ("five nines") uptime**
- Distinguishing claim style: *"Five nines is measured, not aspirational. We can show the report."*

> **TODO for the user:** Add the measurement period the 99.999% number reflects, and confirm it's pulled from monitoring data the buyer could in principle review (or that you can produce as an artifact).

---

### Claims to AVOID in pitches

These weaken pitches because they're generic floor-level claims — every MSP says them, so they signal nothing.

- *"We're HIPAA compliant."* — Floor, not a differentiator. Replace with a specific audit-shepherding claim.
- *"We use AI."* — Generic. Replace with the AI SIEM platform's name + a deployment fact.
- *"We have 24/7 support."* — Table stakes.
- *"We have great customer service."* — Unfalsifiable.
- *"We have decades of healthcare experience."* — Nonspecific. Replace with vertical specifics ("# of ortho groups served").
- *"We're vendor-neutral."* — Reads as "we don't have a recommendation."
- *"Comprehensive IT and cybersecurity services."* — Catalog language. Replace with one specific outcome relevant to the persona.

---

### When you learn something new

Add it here. Wedge Coach treats this file as ground truth on its next run. Examples of additions worth making:

- A new client win with a documented outcome
- A new credential or certification at the firm
- A new client-side metric (insurance premium reduction, audit closure time, downtime number)
- A specific named EHR/PM system you've added to your hosting stack
- A specific named regulator interaction (named state, named audit type) with a specific outcome

The principle: every addition should be *specific, numbered, time-bound, and in principle verifiable*. Anything else is fluff and will weaken the diagnoses that pull from this file.
