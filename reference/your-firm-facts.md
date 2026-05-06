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

- **60+ orthopedic groups served to date** — this is the headline vertical-depth specific; surface it whenever a pitch references "healthcare experience"
- Long-term operating experience inside orthopedic surgical IT environments
- Vertical-specific support standard operating procedures (SOPs) built for orthopedic clinical workflows — not adapted from generic healthcare templates
- Deep working knowledge of clinical-data structures inside the major orthopedic EHR/PM systems (technicians who can troubleshoot inside the data model, not just at the application surface)
- Internal claim style: *"We know your EHR better than your vendor's L1 support does."* This claim is credible when backed by specific named systems and example incidents — name them when using this in pitches.

> **Still to capture:** # of EHR instances hosted, # of years specifically in ortho, named EHR/PM systems where the L1-knowledge claim is most defensible. Add as you confirm them.

#### Compliance posture

- Specialists on staff who guide CEOs and COOs through HIPAA and SOC 2 audits
- Operational stance: *we don't sell compliance, we shepherd you through it*
- Track record of closing OCR findings letters within defined windows for client groups

> **TODO for the user:** Add specific examples of audit shepherding — # of HIPAA audits supported, average findings-closure time, # of SOC 2 Type 2 attestations achieved with clients.

#### Security

- Proprietary AI SIEM platform also deployed at top-tier hospitals and government agencies
- Documented client-side reductions in cyber insurance premiums attributable to controls evidence produced by the platform
- Internal claim style: *"Proven, not fluff."* Credibility requires the receipts — named carriers, named premium-reduction percentages, named comparison periods.

**Receipts** (use these by name in pitches when persona context fits):

- **Insurance retention save — 26-clinic orthopedic group.** The group's cyber carrier was preparing to non-renew the policy. True North's controls evidence and audit posture reversed the carrier's decision and the group kept coverage. This is the receipt to pull on Burned-Before COOs, Skeptical CFOs, and any persona whose recent context includes a premium increase or carrier conversation. Translation for the buyer: *"We don't just reduce premiums — we've kept carriers from walking. A 26-clinic group is on coverage today because of evidence we produced for their carrier."*

- **Ransomware containment on an adjacent unmanaged network.** Ransomware was deployed on a network connected to one of our orthopedic clients — a network True North did not manage. The threat reached the perimeter of our client's environment and could not pivot into the infrastructure we did manage. This is the **operational proof point for the isolated per-customer infrastructure claim** (the "air gap" wedge). Use it any time a pitch references air-gapped or isolated infrastructure: *"This isn't theoretical — when ransomware was deployed on a network adjacent to one of our clients, it could not pivot into the environment we manage. That's what isolation actually means in practice."*

> **Still to capture:** AI SIEM platform's product name (if it's a named brand the buyer can verify); the named carrier (or anonymized as "a top-5 cyber carrier") for the 26-clinic save; the year/quarter of the ransomware event for time-bound credibility. Add as you confirm them.

#### Founder credibility

- Firm CEO holds **CISSP-ISSAP** (Information Systems Security Architecture Professional) certification — a security-architecture credential, not a sales credential
- Lead-from-the-front model: CEO personally reviews every orthopedic client's environment before onboarding
- Distinguishing claim style: *"Our CEO is a security architect, not an MSP owner who hires security people."*

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
