# Wedge Coach

A folder-based AI specialist that helps vCIO/vCAIO sellers in healthcare IT discover their wedge and sharpen their first three minutes — through realistic role-play drills with skeptical orthopedic surgical CEO/COO personas, and surgical post-rep diagnosis.

Built using **Interpretable Context Methodology** (Van Clief & McDermott, 2026): folders as agent architecture, each file does one job, plain text as the interface.

---

## What this is

Wedge Coach is **not** an AI sales script generator. It will refuse to write your pitch for you.

It does two things, in sequence, every time:

1. **DRILL** — plays a randomized healthcare CEO/COO persona; you pitch; they push back like a real prospect (interrupt, check phone, time-box you, ask the question that exposes generic claims)
2. **DIAGNOSE** — after each rep, surfaces three things only:
   - **Inflection Moment** — where attention dropped
   - **Missing Specific** — what concrete claim, name, or number would have held them
   - **One-Drill Tweak** — one change for the next rep

After every five drills, it produces a **Wedge Synthesis** — what wedge is emerging from your reps, and what to test in the next five.

---

## Who it's for

vCIO and vCAIO sellers — typically MSP owners, founders, or senior account executives — pitching to:

- Healthcare CEOs and COOs
- Orthopedic surgical groups, ASCs, and multi-location practices
- 50–500 seat range
- Goal: move qualified prospects into a paid Discovery Assessment

If you're a healthcare-IT MSP serving a different vertical (cardiology, ophthalmology, derm, etc.), swap [reference/smb-owner-personas.md](reference/smb-owner-personas.md) and [reference/your-firm-facts.md](reference/your-firm-facts.md). The rest of the folder works unchanged.

---

## How to use it (3 steps, under 5 minutes)

### 1. Drop the folder into a Claude project

Drag the entire `wedge-coach/` folder into the Project Files panel of a new Claude project (claude.ai → Projects → New Project → upload files).

### 2. Open a new chat in the project and type:

```
Drill me.
```

Wedge Coach will lock a persona and prompt you to pitch.

### 3. Pitch — out loud (then transcribe), or paste a draft

The persona will react in character — interrupting, asking questions, time-boxing you. When you're done, type `stop` (or `diagnose`), and the diagnosis arrives.

---

### For a tailored drill (recommended)

If you have a real upcoming call, give Wedge Coach the context:

```
Drill me. I have a call in 25 minutes with the COO of a 7-surgeon
orthopedic group in Phoenix that just got an OCR findings letter.
```

Wedge Coach will build a persona that matches and run the drill at audit-fatigued realism.

### After 5 drills

```
wedge synthesis
```

This is where the value compounds. The synthesis surfaces patterns across your reps — what's working, what's losing them, and which of the [six wedge archetypes](reference/wedge-taxonomy.md) is emerging from your specific style and proof points.

---

## What good output looks like

After a generic pitch, expect a diagnosis like:

```
=== DIAGNOSIS ===

INFLECTION MOMENT
"We're a managed services provider with deep healthcare experience and we offer
comprehensive IT and cybersecurity services for practices like yours."
That sentence describes 2,000 MSPs. Linda's attention was already gone before
you got to the ask.

MISSING SPECIFIC
Your firm-facts file has receipts you didn't use. You have a CISSP-ISSAP-credentialed
CEO whose actual job is risk architecture. You host EHR for orthopedic groups
specifically. None of that surfaced. To Linda — who just got an OCR letter —
your CEO's credential alone earns you 60 more seconds.

ONE-DRILL TWEAK
Replace your second sentence with: "Our CEO is CISSP-ISSAP certified — which
means he's a security architect, not a salesperson — and he reviews every
orthopedic client's environment personally for OCR-reportable gaps."
Then run it again with the same persona and see what minute two looks like.

Run another? (yes / specific prospect / different mood / wedge synthesis / stop)
```

See [examples.md](examples.md) for three full worked interactions.

---

## What it WON'T do

- Write your pitch, opener, or hook
- Generate scripts, templates, or "10 ways to start a vCIO conversation"
- Coach in jargon (BANT, MEDDIC, etc.) — buyer-side English only
- Roleplay past minute three of an initial pitch
- Roleplay clinicians, IT directors, or end-users (only the financial decision-maker)
- Quote pricing or scope a Discovery Assessment

The reason for the first restriction is structural: if it writes your pitch, you inherit Claude's wedge instead of finding your own. Reps with feedback are how you find your wedge. There's no shortcut. See [rules.md](rules.md) for the full contract.

---

## Configuring it for your firm

If you're using Wedge Coach for a firm other than True North ITG (or if you're True North and your facts have evolved):

1. Open [reference/your-firm-facts.md](reference/your-firm-facts.md)
2. Replace the body with your firm's specific differentiators using the same section headings
3. The principle for every entry: **specific, numbered, time-bound, falsifiable**. Anything else is fluff and will weaken Wedge Coach's diagnoses.

If you're targeting a different healthcare vertical:

1. Edit [reference/smb-owner-personas.md](reference/smb-owner-personas.md) to reflect that vertical's CEO/COO archetypes
2. Edit [reference/objection-bank.md](reference/objection-bank.md) to reflect the objections specific to that vertical
3. Optionally edit [reference/healthcare-it-glossary.md](reference/healthcare-it-glossary.md) to reflect vertical-specific terminology (e.g., MIPS reporting matters more in some specialties than others)

The remaining files — [identity.md](identity.md), [rules.md](rules.md), [wedge-taxonomy.md](reference/wedge-taxonomy.md), [inflection-moments.md](reference/inflection-moments.md) — are vertical-agnostic and work unchanged.

---

## File structure

```
wedge-coach/
├── identity.md                       # Who Wedge Coach is
├── rules.md                          # The DRILL → DIAGNOSE contract
├── examples.md                       # Three worked example interactions
├── reference/
│   ├── smb-owner-personas.md         # 10 healthcare CEO/COO personas
│   ├── wedge-taxonomy.md             # The six wedge archetypes
│   ├── inflection-moments.md         # 15 common attention-drop patterns
│   ├── healthcare-it-glossary.md     # Buyer-side meaning of key terms
│   ├── objection-bank.md             # 15 first-3-min objections, decoded
│   └── your-firm-facts.md            # Your firm's proof points (replace this)
└── README.md                         # This file
```

Each file does one job. The folder structure is the architecture.

---

## Methodology credit

Wedge Coach is built using **Interpretable Context Methodology (ICM)** by Jake Van Clief and David McDermott (Eduba / University of Edinburgh, 2026). Reference: [https://github.com/RinDig/Interpretable-Context-Methodology-ICM-](https://github.com/RinDig/Interpretable-Context-Methodology-ICM-).

Five ICM principles applied here:

1. **One stage, one job** — `identity.md` says who, `rules.md` says how, `examples.md` shows what good looks like, the `reference/` files carry stable knowledge
2. **Plain text as the interface** — every file is markdown a human can read and edit
3. **Layered context loading** — the model can read only what's relevant per session; nothing forces it to load every file every time
4. **Every output is an edit surface** — diagnoses, persona profiles, and wedge syntheses are designed to be editable artifacts you can save or revise
5. **Configure the factory, not the product** — set up the folder once; run unlimited drills with the same configuration

---

## License

MIT. Fork it, adapt it for your vertical, ship better pitches.
