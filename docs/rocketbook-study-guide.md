# Rocketbook Integration Guide
### Doctoral Pathway — Professor Mark Maine

*Covers: Rocketbook Everyday Planner + Rocketbook Core*  
*Last updated: May 2026*

---

## The Core Principle

Two notebooks, two distinct jobs. The **Everyday Planner** governs time — it holds your schedule, your weekly rhythm, your milestones, and your task queues. The **Core notebook** governs content — it holds everything you think and learn: lecture notes, problem set scratch work, Adler reading worksheets, and research reflections. Neither bleeds into the other. When you pick up the Planner, you're managing the pathway. When you pick up the Core, you're doing the work.

---

## Notebook 1: Rocketbook Everyday Planner

### Role in the Pathway

The Everyday Planner is your operational command center. It keeps your protected 7–8 am blocks visible, tracks OCW course progression week by week, and holds your reading queue and milestone horizon. Because it's undated, you can skip weeks without penalty — important during semester disruptions or travel.

---

### Weekly Spread → Study Rhythm

Each Monday, open to a fresh weekly spread before you do anything else. Fill it in like this:

| Day | Block | Entry |
|---|---|---|
| Mon | 7–8 am | 6.1200J Lec [#] — [topic] |
| Tue | 7–8 am | Reading — [author/title, Adler level] |
| Wed | 7–8 am | 6.1200J PS [#] |
| Thu | 7–8 am | Adler worksheet — [paper] |
| Fri | 7–8 am | GitHub commit — [prefix] summary |

Keep the entry brief — this is a pointer, not a note. The Core holds the notes. Use the remaining weekly space for anything that migrates into your morning block during the week (a rescheduled meeting, a reading that carries over).

After Friday's commit, scan the weekly spread and send it to **OneDrive** (or Google Drive). File it as `week-YYYY-MM-DD.jpg` in your session logs folder. This gives you a visual record of every week actually studied.

---

### Monthly Spread → OCW Course Tracker

Use one monthly spread per OCW course. For **6.1200J** (May 18 – August 3, 2026), label the spread "6.1200J Discrete Math" and mark the 10 weeks across the month grids:

- Week 1–2: Propositions, Logic, Proofs
- Week 3–4: Induction, State Machines
- Week 5–6: Number Theory, Cryptography
- Week 7–8: Structures, Counting
- Week 9: Probability
- Week 10: Review + Course Reflection

Check off each week as Friday's commit lands. This monthly view makes it immediately visible if you fall behind and need to compress.

---

### Annual Spread → Doctoral Milestone Horizon

Use the two annual spreads as a long-range milestone map. Mark the following across the timeline:

- **May 18, 2026** — 6.1200J begins
- **Aug 3, 2026** — 6.1200J complete
- **Fall 2026** — 6.006 Algorithms begins
- **Jan 15, 2027** — Ed.D. applications due
- **Aug 2027** — Ed.D. enrollment
- **May 2031** — Dissertation defense
- **Aug 2031** — Ed.D. conferred

You don't need to mark every milestone — just enough that when you open the annual spread, you can see where you are in the arc.

---

### List Pages → Reading Queue + Paper Pipeline

The Planner's List pages connect to the Rocketbook app's **Smart Lists** feature, which means checked items sync digitally. Use them as follows:

**List 1 — Current Reading Queue** (active books and papers in rotation)  
**List 2 — Instapaper Inbox** (articles clipped but not yet read)  
**List 3 — Adler Worksheet Queue** (papers queued for analytical reading)  
**List 4 — GitHub Commit Log** (brief record of what was committed each Friday — useful for month-end summaries)

Check items off as they move through the pipeline. Scan each list page monthly and upload to OneDrive for archiving.

---

### Dot-Grid Pages → Dissertation Thinking

The Planner's dot-grid pages are for non-scheduled intellectual work: brainstorming research questions, sketching the relationship between your four research angles, mapping dissertation topic candidates. Date and title each page when you use it. Scan and send to OneDrive. These pages are not part of the weekly rhythm — use them when something crystallizes and you need to think on paper.

---

### Destination Setup for the Planner

In the Rocketbook app, configure the Planner's scan destinations as follows:

| Symbol | Destination | Purpose |
|---|---|---|
| ☆ | OneDrive — `/weekly-scans/` | Weekly spread archive |
| ✉ | Email (self) | Send to Zotero or share with advisor |
| ♦ | Google Drive (backup) | Secondary archive |
| ⊕ | OneDrive — `/monthly-scans/` | Monthly spread and milestones |

Adjust remaining symbols as your workflow develops.

---

## Notebook 2: Rocketbook Core

### Role in the Pathway

The Core is where you think on paper. Every lecture, every problem set, every Adler reading session happens here. The Smart Title Bar and Smart Tags built into each page mean your scanned content arrives in your digital system already labeled and searchable — reducing the friction between handwritten work and your GitHub repository.

---

### Smart Title Bar → File Naming Convention

Write your title in the Smart Title Bar using the same `[prefix]` convention as your Git commits:

```
[ocw] 6.1200J — Lec 3 — Induction
[read] Guzdial 2015 — Chapter 2 — Inspectional
[ps] 6.1200J — PS 2 — Number Theory
[reflect] 6.1200J — Week 4 Reflection
```

When scanned, the Rocketbook app uses this bar to auto-name the file. The result is a scan named exactly as your commit message would be — making it easy to attach the scan to the right session log entry.

---

### Smart Tags → Research Angle Tagging

Use the Smart Tag bubbles at the bottom of each Core page to tag by research angle. Establish four consistent tags matching your four doctoral research angles:

| Tag | Research Angle |
|---|---|
| `trauma-cs` | Trauma-informed cybersecurity for vulnerable populations |
| `pastoral-sec` | Cybersecurity as pastoral care / stewardship |
| `ai-discern` | AI discernment, disinformation, literacy |
| `compliance` | Compliance frameworks in security education |

For OCW content, use the course code as a tag (`6.1200J`, `6.006`, etc.). For reading sessions, tag by research angle. A single page can carry two tags if the content spans angles.

---

### Monday: Lecture Notes (6.1200J)

Write lecture notes by hand. This is intentional — handwriting encodes mathematical content more durably than typing, and you're working through Discrete Math starting tomorrow. Use the following structure per page:

- **Title bar**: `[ocw] 6.1200J — Lec [#] — [topic]`
- **Tag**: `6.1200J`
- **Top quarter**: Key definitions and theorems — boxed
- **Middle**: Worked examples and your own notation
- **Bottom**: One "so what" sentence — why this concept matters for the course arc

After the session, scan immediately and send to your **session logs destination** (see Destination Setup below). Do not let scans accumulate — same-day scanning is the discipline.

---

### Wednesday: Problem Set Scratch Work

Use the Core for all PS scratch work. Even work you abandon or restart is worth keeping — the false starts reveal your reasoning process, which matters for doctoral-level reflection.

- **Title bar**: `[ps] 6.1200J — PS [#] — [topic area]`
- **Tag**: `6.1200J`
- Circle problems that took more than one attempt. When you write up the clean solution in markdown for the repo, reference what went wrong in the scratch work.

Scan Wednesday's pages on Friday before committing. The scan goes into the same session logs destination.

---

### Tuesday / Thursday: Adler Reading Sessions

The Adler 4-level reading method (Inspectional → Analytical → Syntopical) maps naturally to Core pages. Use a consistent page structure:

**Inspectional Read (Tuesday)**  
- Title bar: `[read] [Author Year] — Inspectional`
- Bibliographic info top-right
- X-ray: What is the book/paper doing? (2–3 sentences)
- Key terms identified
- Decision: proceed to Analytical? Y / N

**Analytical Read (Thursday, if proceeding)**  
- Title bar: `[read] [Author Year] — Analytical — Part [n]`
- Main argument in one sentence
- Structure of the argument (list the logical moves)
- Agreements and disagreements — your voice, not summary
- Connection to dissertation candidate topic (A / B / C / D)
- Tag with research angle

Scan Thursday pages the same day. These go to the **Zotero destination** — the scan attaches to the Zotero item for that paper.

---

### Destination Setup for the Core

| Symbol | Destination | Purpose |
|---|---|---|
| ☆ | OneDrive — `/session-logs/scans/` | Lecture notes + PS scratch work |
| ✉ | Zotero (via email-to-Zotero or Google Drive handoff) | Adler worksheets + reading notes |
| ♦ | Google Drive — `/doctoral-backup/` | Full backup destination |
| ● | OneDrive — `/reflections/` | Course and phase reflections |
| ▲ | OneNote (optional) | Quick capture during non-study hours |

Configure the remaining two symbols as your research destinations develop (e.g., a dissertation notes folder once that work begins).

---

## Friday Commit Integration

Friday's 7–8 am block is the closing ritual for the week. The Rocketbook workflow integrates here directly:

1. **Scan all unsent Core pages** from the week — lecture notes, PS work, reading pages
2. **Scan the weekly Planner spread**
3. **Update session log** in the repo (`ocw-portfolio/6.1200J-discrete-math/notes/`) — reference the scanned filenames
4. **Update weekly log** (`independent-study/Pre-Program/weekly-log.md`)
5. **Update reading log** (`research/reading-logs/2026-05.md`) with any papers read this week
6. **Commit** with `[log]` or multiple prefixes as appropriate

The Rocketbook scans become the evidence of work. The commit is the record that the work happened.

---

## Monthly Maintenance (End of Month)

At the end of each month, do a brief Rocketbook review before erasing pages:

1. Confirm all Core pages have been scanned — check your OneDrive folder against what you remember writing
2. Scan any Planner list pages that changed during the month
3. Erase Core pages with the damp cloth — only after confirming scans are in OneDrive
4. Erase Planner weekly and list pages — keep monthly and annual spreads until the course or phase ends
5. Update `COWORK-CONTEXT.md` if anything structural changed in your workflow

Do not erase a page until the scan is confirmed in its destination folder.

---

## Quick Reference

| Notebook | When | What | Scan Destination |
|---|---|---|---|
| Everyday Planner | Monday | Weekly spread setup | — |
| Core | Monday | Lecture notes | OneDrive `/session-logs/scans/` |
| Core | Tuesday | Adler inspectional | Zotero |
| Core | Wednesday | PS scratch work | OneDrive `/session-logs/scans/` |
| Core | Thursday | Adler analytical | Zotero |
| Planner + Core | Friday | Scan all, then commit | OneDrive, then GitHub |
| Planner | Monthly | Course tracker check | OneDrive `/monthly-scans/` |

---

*This guide is part of the `doctoral-pathway` repository documentation.*  
*Commit tag: `[docs]`*
