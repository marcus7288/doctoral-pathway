# Rocketbook Worked Example — Week 1
## May 18–22, 2026 · 6.1200J Begins · HPL2 Phase 1

*This document shows exactly what to write in each notebook for a complete study week. Everything here is real — drawn from the actual first week of 6.1200J and the Phase 1 reading sequence. Use it as a template until the rhythm becomes automatic.*

---

## Sunday Evening: Set Up the Weekly Spread

Before Monday's session, open the **Everyday Planner** to a fresh weekly spread and fill in the five study blocks. This takes three minutes.

```
WEEK OF: May 18, 2026
```

| Day | Entry |
|-----|-------|
| MON | [ocw] 6.1200J — Lec 1 — Propositions & Logical Connectives |
| TUE | [read] National Academies 2018 (HPL2) — Inspectional |
| WED | [ocw] 6.1200J — PS 1 — Propositions & Logic |
| THU | [read] National Academies 2018 (HPL2) — Analytical — Ch. 2 |
| FRI | [log] Week 1 — scan all Core pages, commit |

Leave the rest of the weekly spread blank. Any rescheduled tasks or overflow notes go here during the week — but not in the Core.

---

## Monday, May 18 — Lecture Day

### In the Planner
Nothing new. The weekly entry you wrote Sunday is enough.

### In the Core

Open to a fresh page. Before writing a single note:

**Smart Title Bar:**
```
[ocw] 6.1200J — Lec 1 — Propositions & Logical Connectives
```

**Smart Tag bubble:**
```
6.1200J
```

Now structure the page in three zones:

---

**TOP ZONE — Definitions & Theorems (boxed)**

Draw a light box around this section as you write. These are reference anchors — they should stand out visually.

```
┌─────────────────────────────────────────────────────────────┐
│ PROPOSITION: A statement that is either TRUE or FALSE       │
│   — not a question, command, or opinion                     │
│                                                             │
│ COMPOUND PROPOSITION: built from simpler ones using         │
│   connectives: ¬ (NOT)  ∧ (AND)  ∨ (OR)  → (IMPLIES)      │
│   ↔ (IFF)                                                   │
│                                                             │
│ TRUTH TABLE: enumerates truth values for all combos of      │
│   propositional variables                                   │
└─────────────────────────────────────────────────────────────┘
```

**MIDDLE ZONE — Examples & Working**

Work through the examples from the lecture in your own notation. Don't copy — work them. If you get stuck, write down where you got stuck. That confusion is data.

```
Example: "If it rains, then the ground is wet."
  P = "It rains"       Q = "Ground is wet"
  Written: P → Q

  Converse:  Q → P    (not equivalent!)
  Inverse:   ¬P → ¬Q  (not equivalent!)
  Contrapositive: ¬Q → ¬P  (IS equivalent to P → Q)

  Truth table for P → Q:
  P    Q    P→Q
  T    T     T
  T    F     F   ← only false case
  F    T     T
  F    F     T
```

**BOTTOM ZONE — "So What"**

One sentence. Write it in plain English, not notation. This is the thing you'll remember.

```
So what: The contrapositive is the only transformation of an implication
that preserves truth — every proof by contradiction leans on this.
```

---

**After the session:** Scan this page immediately. Symbol ☆ → OneDrive `/session-logs/scans/`. File will auto-name from the Smart Title Bar:
`[ocw] 6.1200J — Lec 1 — Propositions & Logical Connectives`

---

## Tuesday, May 19 — Research Reading Day

*Phase 1 reading: HPL2 is the anchor text. Week 1 is an inspectional read — you're X-raying the whole book, not reading every word. Goal: understand the structure, identify the four highest-priority chapters, and decide how to sequence the analytical read.*

### In the Planner
Nothing new. Weekly entry stands.

### In the Core

**Smart Title Bar:**
```
[read] National Academies 2018 — HPL2 — Inspectional
```

**Smart Tag bubble:**
```
ai-discern
```
*(HPL2 has direct relevance to your AI literacy research angle — how people learn to evaluate AI-generated content is a learning science question)*

**Page Structure — Adler Inspectional Read:**

```
BIBLIOGRAPHIC INFO:
  National Academies of Sciences, Engineering, and Medicine. (2018).
  How people learn II: Learners, contexts, and cultures.
  National Academies Press. [Free PDF: nap.edu]
  Zotero key: NationalAcademies2018

X-RAY (What is this book doing?):
  Synthesizes contemporary learning science across cognitive psychology,
  neuroscience, cultural studies, and educational research. Updates the
  2000 HPL volume. Argues that learning is inseparable from context,
  identity, culture, and development — not just cognition. The
  theoretical foundation for all HPL2-themed CS education scholarship.

STRUCTURE (chapter scan — 10 minutes):
  Ch. 1 — Introduction: why HPL2, what's new
  Ch. 2 — Development: how learners change over time ← PRIORITY
  Ch. 3 — Memory: encoding, retrieval, forgetting
  Ch. 4 — Motivation & Identity: belonging, self-efficacy ← PRIORITY
  Ch. 5 — Metacognition: learning how to learn
  Ch. 6 — Culture & Context: situating learning ← PRIORITY
  Ch. 7 — Assessment: measuring what matters
  Ch. 8 — Technology: tools change learning ← PRIORITY
  Ch. 9 — Implications for practice

KEY TERMS IDENTIFIED:
  — Transfer-appropriate processing
  — Culturally sustaining pedagogy
  — Epistemic cognition
  — Productive failure (Kapur)

PROCEED TO ANALYTICAL? ✓ YES
  Priority order: Ch. 2 → Ch. 4 → Ch. 6 → Ch. 8
  Begin analytical read: Thursday (Ch. 2)
```

**Scan:** Symbol ✉ → Zotero (attach to NationalAcademies2018 item). Same day.

---

## Wednesday, May 20 — Problem Set Day

*6.1200J Problem Set 1 covers Propositions and Logic — the content from Monday's lecture.*

### In the Planner
Nothing new.

### In the Core

**Smart Title Bar:**
```
[ps] 6.1200J — PS 1 — Propositions & Logic
```

**Smart Tag bubble:**
```
6.1200J
```

**Page approach:**

Work every problem in this notebook. Keep your scratch work — including the false starts. When you abandon an approach, draw a single diagonal line through it and write a one-word note on why (e.g., "wrong direction," "didn't account for F→T case"). That record becomes the raw material for the course reflection at week 10.

For any problem that takes more than one attempt, circle it in the margin when you finally get it. These circled problems tell you exactly what concepts need reinforcement.

```
Problem 1.1: Determine the truth value of:
  (P ∧ Q) → (P ∨ Q) for all truth assignments

  Attempt 1: Try P=T, Q=F
    LHS: T ∧ F = F
    F → anything = T ✓

  Attempt 2: Try P=F, Q=F
    LHS: F ∧ F = F
    F → anything = T ✓

  Is LHS ever true? Yes: P=T, Q=T
    LHS: T ∧ T = T
    RHS: T ∨ T = T
    T → T = T ✓

  Conclusion: Tautology — always true.
  Intuition: If both are true, certainly at least one is true. ✓
```

*Continue through all problems in this format. When the page fills, open a new page and continue with the same title bar + tag.*

**Scan:** Symbol ☆ → OneDrive `/session-logs/scans/`. Hold until Friday — scan all Wednesday work together before committing.

---

## Thursday, May 21 — Adler Analytical Day

*Begin analytical read of HPL2, Chapter 2: Development. This is where you slow down and actually read — not inspectional.*

### In the Planner
Nothing new. If you didn't finish the PS on Wednesday, note it here as a carry-over.

### In the Core

Open two pages if you need them — analytical reading generates more than inspectional.

**Smart Title Bar (each page):**
```
[read] National Academies 2018 — HPL2 — Analytical — Ch. 2 — Pt. 1
```

**Smart Tag bubbles:**
```
trauma-cs     pastoral-sec
```
*(Ch. 2 on development is directly relevant to how trauma affects cognitive development — this is the theoretical grounding for your Boys Ranch research angle)*

**Page Structure — Adler Analytical Read:**

```
MAIN ARGUMENT (one sentence):
  Cognitive and social development are not background conditions for
  learning — they ARE learning, and instruction that ignores developmental
  stage produces either boredom or cognitive overload.

STRUCTURE OF ARGUMENT:
  1. Development is not linear — it is domain-specific and culturally shaped
  2. Prior knowledge interacts with developmental stage (Vygotsky's ZPD)
  3. Adolescent and adult learners bring metacognitive capacity that
     children don't — but instructors often don't leverage it
  4. Institutional contexts can either support or suppress development

KEY PASSAGE (p. 47, paraphrase):
  "Learners at all levels are active constructors of knowledge, not
  passive recipients — but what they construct depends heavily on what
  developmental resources they bring."

AGREEMENTS:
  — The ZPD framing is directly applicable to CS1: every student arrives
    with a different zone. Lecture-only instruction hits almost nobody at
    the right level. This is empirical support for differentiated pacing.

DISAGREEMENTS / QUESTIONS:
  — Ch. 2 assumes relatively stable institutional contexts. High-risk
    youth (Boys Ranch population) experience context disruption that
    resets developmental baselines repeatedly. HPL2 doesn't address this.
    This is a gap I can speak to from practice.

CONNECTION TO DISSERTATION TOPICS:
  Topic A (Faith-integrated CS pedagogy): ✓ Contextualization theory in
    missiology works analogously — meet the learner in their cultural
    development, not an imagined standard learner.
  Topic C (CS equity in Christian liberal arts): ✓ Developmental stage
    interacts with identity formation — belonging crises in CS are
    partly developmental, not just cultural.

RESEARCH ANGLE TAG: trauma-cs
  The gap I noted (context disruption in high-risk youth) is a potential
  dissertation contribution. No HPL2-adjacent literature addresses
  trauma's effect on CS learning readiness.
```

**Scan:** Symbol ✉ → Zotero (attach to NationalAcademies2018). Same day, before end of evening.

---

## Friday, May 22 — GitHub Commit Day

*The closing ritual. Everything from this week becomes part of the permanent record.*

### Step-by-Step Sequence

**1. Confirm all Core pages are scanned**

Go through the week mentally:
- Monday lecture notes → scanned Monday (☆ → OneDrive) ✓
- Tuesday inspectional → scanned Tuesday (✉ → Zotero) ✓
- Wednesday PS work → not yet scanned — **do it now** (☆ → OneDrive)
- Thursday analytical → scanned Thursday (✉ → Zotero) ✓

**2. Scan the weekly Planner spread**
Symbol ☆ → OneDrive `/weekly-scans/`
Filename (auto from Smart Title Bar area): `week-2026-05-18`

**3. Open the session log in VS Code**

File: `ocw-portfolio/6.1200J-discrete-math/notes/`
Create: `2026-05-18-lec01.md`

```markdown
# Session Log — 6.1200J Lecture 1
**Date:** May 18, 2026  
**Topic:** Propositions and Logical Connectives  
**Duration:** 60 minutes  

## What We Covered
Propositions, truth values, five logical connectives (¬ ∧ ∨ → ↔),
truth tables, compound propositions, converse/inverse/contrapositive.

## Key Insight
The contrapositive (¬Q → ¬P) is the only transformation of P → Q
that preserves logical equivalence. This is the backbone of proof
by contradiction — came up immediately and will recur throughout.

## Problem Set Status
PS 1 in progress — completed problems 1.1–1.4. Problem 1.3 took
two attempts (confused myself on the biconditional truth table).
Circled for review.

## Scan
[ocw] 6.1200J — Lec 1 — Propositions & Logical Connectives → OneDrive
[ps] 6.1200J — PS 1 — Propositions & Logic → OneDrive
```

**4. Update the weekly log**

File: `independent-study/Pre-Program/weekly-log.md`

```markdown
## Week of May 18, 2026

**OCW:** 6.1200J Lecture 1 complete. Topic: Propositions & Logical
Connectives. PS 1 in progress — approx. 70% done.

**Reading:** HPL2 (National Academies, 2018) — Inspectional complete
(Tue). Analytical read begun, Ch. 2 — Development (Thu). Key gap
identified: HPL2 doesn't address how context disruption (trauma,
instability) resets developmental baselines. Potential contribution.

**Tags used this week:** 6.1200J  trauma-cs  pastoral-sec

**Carry-overs:** Finish PS 1 (next Wed session).
```

**5. Update the reading log**

File: `research/reading-logs/2026-05.md`

```markdown
## May 22, 2026

- National Academies (2018) — *How People Learn II* — Inspectional ✓
  Status: Analytical begun (Ch. 2). Priority chapters: 2, 4, 6, 8.
  Zotero: NationalAcademies2018
  Tags: trauma-cs, pastoral-sec
  Gap noted: trauma/context disruption not addressed
```

**6. Commit**

```bash
git add .
git commit -m "[ocw] 6.1200J Lec 1 — Propositions & Logical Connectives
[ps] 6.1200J PS 1 in progress
[log] Week 1 — reading log + weekly log updated
[read] HPL2 inspectional complete, analytical Ch. 2 begun"
git push origin main
```

Multi-prefix commits are fine when a Friday lands multiple file types. List each prefix on its own line in the commit message body.

---

## What the Week Produced

By end of Friday, you have:

- One lecture session log in the repo, linked to a scan in OneDrive
- One PS session in progress with scratch work preserved and scanned
- One complete inspectional read of HPL2 logged in Zotero and the reading log
- One partial analytical read of HPL2, Chapter 2, with a potential research gap identified and tagged `trauma-cs`
- A weekly log entry covering all activity
- A GitHub commit that timestamps all of it permanently

Next Monday you open a fresh weekly spread and begin Lecture 2.

---

## Common First-Week Mistakes

**Writing too much in the Planner.** The Planner entry is a label, not a note. If you find yourself writing sentences in the weekly spread, that content belongs in the Core.

**Not scanning the same day.** The scan discipline is where the system breaks down. Wednesday's PS work sat unscanned until Friday — that's acceptable once as a worked example, but in practice scan it Wednesday evening. If a scan is missing and you've already wiped the page, it's gone.

**Skipping the "so what" sentence.** It feels like extra work after an hour of lecture. It isn't — it's the most important sentence on the page. The Core notes record what was said. The "so what" records what you understood.

**Treating the Adler template as a checklist.** The analytical read structure (main arg, structure, agreements, disagreements, connection to topics) is a discipline, not a form. Write more where the text is speaking to your research. Write less where it isn't. The template is a floor, not a ceiling.

---

*This document is part of the `doctoral-pathway` repository documentation.*  
*Commit tag: `[docs]`*
