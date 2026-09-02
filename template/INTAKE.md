# Intake

Six questions. The answers compile the framework into the `## Plan` block for `README.md` and decide which files exist. Answer in a Claude session (it reads the framework so you don't) or by hand using the tables below. **Output test: if any field in the block says "see §N," the intake failed.** Section numbers are for exceptions only.

## The questions

### Q1 — Track

Blank page, 10-minute timer, write everything you know about the target from memory.

| Result | Track | Meaning |
|---|---|---|
| Page fills, disorganised | **A — Reactivate** | Competent; not accessible under pressure. Testing is the study method from day one |
| Can't start; can name the field's major parts | **C — New domain** | Competent adult, new field. Binding step: a reliable feedback source *before* volume |
| Can't start; don't know the parts | **B — From zero** | Order, load, not quitting. Don't mix topics; don't chase the big picture; don't shop for tools |

### Q2 — Domain class

| Class | Domains | Emphasise | Watch for |
|---|---|---|---|
| **fact-heavy** | terminology, law, anatomy, vocab | spaced repetition; connect facts into a schema | orphan facts; over-carding |
| **procedural** | programming, maths, instruments, physical skills | worked example → completion problem → blank page, then build; interleave once competent; sleep between practice days | tutorial hell; autocomplete replacing retrieval; massing practice |
| **conceptual** | system design, theory (music theory, economics) | case studies as worked examples; contrasting cases ("why X not Y"); "given constraints, design Z" | memorising names instead of principles |
| **judgment** | trading, diagnosis, investing, management | `decision-log.md`: thesis, invalidation, confidence, size — locked before acting; process graded with the outcome hidden | outcome bias; volume teaching superstition |

Languages: block similar vocabulary, don't interleave it. Writing: volume plus expert critique.

### Q3 — Reader model

| Answer | Consequence |
|---|---|
| **self** | You write and read everything. The mocks or the course are your inspection; the monthly AI-off test is not optional |
| **mentor + learner** — write the mentor's name | Learner holds the pen on every learner file. Mentor's bookkeeping, provenance marks and review reasoning live in `mentor/README.md` — never in the learner's files. Mentor reads `error-log.md`, AI column included, every session |

### Q4 — Reference answer source

Something outside your head must be able to tell you you're wrong, before you start.

| Answer | Consequence |
|---|---|
| **external** — course with graded labs or a test suite; textbook with an answer key; a mentor who reviews; the world (compiler, failing test, recipe that comes out wrong) | Name it in `prerequisite-sketch.md §1`. No drill file |
| **none** — Track A or B | Create `drill-bank.md`. Every question gets its answer-key pointer *written from the source before the first cold attempt*. The pointers are the reference answer |
| **none** — Track C | **Stop.** In a new field you cannot yet tell a good source from a confident wrong one, so a drill bank you build yourself is an answer key you cannot check. Finding something that can grade you — a mentor, a graded course, a community that critiques work — is competency line #1 and comes before any volume |

"It runs" is a weak signal if the question was whether the design is any good.

### Q5 — AI-assisted material

Was any of the material you'll be reactivating built with an AI assistant (code, a report, a model)?

| Answer | Consequence |
|---|---|
| **no** | — |
| **yes** | Week 1 opens with a **cold gate**, before any re-reading: per item, blank page, present tense — what can you produce right now? `defends` → Track A for that item. `blank` → Track B for that item: name the target, build a completion problem from the source, and the item is done only when a cold pass opens a *later* session (same-session counts as never). Claims worded "I designed" become "I evaluated" / "I adopted" until the cold pass exists. Route on the present-tense result, never on who originated it |

### Q6 — Hours, deadline, cadence

Hours per week, honestly. **Which days you study**, and how long each. Deadline date, if any. **Which day is the weekly review** — a fixed day, protected. Then fill the worksheet — the budget was the hardest finding in the first package and it was pre-existing. **The bar** is the time limit written in your own "I can" lines (e.g. "in 20 minutes"); count each activity at that bar, not at the speed you hope for.

| Activity | Count per week | Minutes each, at the bar | Minutes per week |
|---|---|---|---|
| new-material sessions (60-min block) | | 60 | |
| practice / drill items | | <the bar> | |
| cold recall or mock attempts | | | |
| spaced-repetition deck review | 5–7 | 10–20 | |
| weekly review | 1 | 60 | 60 |
| **Total** | | | |

If the total exceeds hours × 60, **name what is cut**, in the block. A budget you cannot hit reads as personal failure, not a planning error.

## Compile tables

### Track → shape

| | A | B | C |
|---|---|---|---|
| "I can" phrasing | the *exact* performance: "I can explain X out loud in 4 minutes without notes" | small enough to succeed today; mentor checks the first list | best guess, marked provisional; revise at two weeks — the revision is the learning |
| `prerequisite-sketch.md §2` | replace with an implementation intention: *"When <cue>, I <action>. If blocked >10 min I write the error-log row before asking."* Build §2 only if fundamentals turn out missing | required; one week deep, agreed with the mentor | required; two levels deep, no further |
| Who sets the order | you, from the target performance | the course | the source you named in Q4; the binding constraint is feedback, not sequence |
| Core-loop order | start at RETRIEVE; heaviest on RETRIEVE, FEEDBACK, TRANSFER | DEFINE → ENCODE (worked example) → **completion problem** → RETRIEVE (blank page) → FEEDBACK (compare, log why) → PRACTICE with less help each time. No STRUGGLE, no mixing, until PRACTICE is comfortable | all ten, in order; the binding step is FEEDBACK — secure it before scaling volume. If the feedback source is asynchronous (a mentor, a forum), batch: run DEFINE→RETRIEVE on several items during the week, get them graded together, then PRACTICE the graded ones |
| Practice mix | blocked by category until the last stretch; then mixed and timed | blocked | blocked until competent |
| Deadline taper (A only) | final two weeks: full-format, timed, no notes, spoken if the test is spoken; mocks spaced across days; 8–9 h sleep in the last 48 h | — | — |
| Real risk | recognise everything, produce nothing under the clock | quitting; overload read as "not smart enough" | a confident wrong picture nobody corrects |

### The core loop (per topic)

The ten steps the track rows refer to. Written out so the plan never has to point elsewhere.

| Step | Do | Move on when | If not |
|---|---|---|---|
| 1 DEFINE | write the "I can…" line | concrete and testable | it's a topic — rewrite it smaller |
| 2 STRUGGLE | 10–15 min attempt before any instruction (optional; not for Track B early) | you know what you don't know | no traction — skip to 3 |
| 3 ENCODE | worked example + explain each step to yourself | you can explain it unaided | only recognise it — more self-explanation |
| 4 RETRIEVE | close everything; blank page; reproduce it | recall works, with effort | repeated blanks — back to 3 |
| 5 FEEDBACK | compare to the reference answer; write *why* you diverged | you can name the why | "I just forgot" — back to 3 |
| 6 PRACTICE | problems with less help each time; then mixed sets | familiar problems reliable | same error recurring — analyse, don't redo |
| 7 INTEGRATE | use it in something real | works under real constraints | can drill, can't build — more whole-task work |
| 8 SCHEDULE | space the review; card only atomic facts | holds across intervals | review overload — prune |
| 9 TRANSFER | an unlabelled problem, or teach it cold | novel problems succeed | fails when context changes — varied practice |
| 10 UPDATE | error log → next target | next targets come from real errors | empty log — you're not attempting hard enough |

### Files → from the answers

| Answer | File |
|---|---|
| always | README.md, competency-list.md, prerequisite-sketch.md, error-log.md, CHANGELOG.md |
| Q3 = mentor + learner | + mentor/README.md |
| Q4 = none, track A or B | + drill-bank.md |
| Q4 = none, track C | no file — keep the base five, but don't start the plan; the feedback source is competency line #1 |
| Q2 = judgment | + decision-log.md |

Strike the rest.

### Hours → session protocol

Durations are conventions; proportions are what matter. Every session opens with delayed recall of the *previous* session — that is the block that builds memory; the end-of-session reconstruction is a comprehension check, not retrieval. **Schedule the real retrieval of today's material for tomorrow or later.**

Which block, when: **60** for a session with new material · **30** for a short day — practice, or one small new item · **120** for a project or mixed-practice day. Under 5 hours/week: 30s and one 60. 5–15: 60s, one 120. Over 15: 120s on most days, 60s for new material. Map each Q6 study day to a block in the plan.

| Block | Shape |
|---|---|
| **30 min** | 3 recall of last session · 20 practice, or one small new item, self-explaining · 5 close the source and sketch what you covered · 2 log gaps. No rereading |
| **60 min** | 0–5 recall · 5–10 optional struggle attempt · 10–45 worked examples, self-explanation, generative notes · 45–55 close everything and reconstruct · 55–60 compare, log, card only atomic facts; put today's material in tomorrow's recall slot |
| **120 min** | 0–5 recall of last session, then the implementation intention incl. the stuck-rule · 5–55 project or interleaved practice · 55–65 real break · 65–105 deliberate practice on the weakness the first block exposed · 105–120 blank-page synthesis, one transfer attempt, error log |
| **Weekly review, 60 min** | no new material. Blank-page dump of the week · read the error log for **patterns, not entries** · prune the deck · one teach-it-cold or novel problem · update the competency list and next week's targets |

### AI policy (verbatim, into the block)

> Attempt first. Then: *"Here's my attempt. What's wrong with my reasoning?"* · *"Ask me questions until I find it myself."* · *"Give this worked example back with one piece removed and a comment saying what belongs there. Don't show me the finished version."* Never: *"What's the answer?"* / *"Fix this."*

Metric: share of AI requests asking for a **final answer** vs a hint, critique, or question. Count each request as you make it. Monthly: one representative problem with AI fully off; if it collapses, critique-only until it doesn't. Track C is most at risk — verify against primary sources until you have your own judgment.

### Diagnostic thresholds (into the block)

| Signal | Rule |
|---|---|
| Same misconception three rows running | one curriculum item, top of next week — not three mistakes |
| Answer-seeking share rising | cut to critique-only until it turns |
| Confidence most exceeds score in a category | that category is next week's syllabus; overconfident beats low-scoring for danger |
| "I just forgot" | only a diagnosis for `Route = forgot`; `never-learned` means go back to the example, more repetition won't help |
| Stalled line | in order: never worked on → smaller target; something must come first → add it ahead; too big → split |
| Weeks 3–4 feel worse | the mechanism working. Say it in advance |

### First 30 days → the Weeks table

Start from these four rows. That table is the schedule; there is no other.

**Weeks 5 and on are not written at intake.** Nobody can know week 6 before the log has rows. At intake, write only the total number of weeks and, for Track A, mark the last two as the taper (full-format, timed, no notes, mocks spaced across days). Every weekly review then writes the *next* row: **Add** = the error log's top pattern and the competency lines still undone; **Remove** = the one thing named to stop doing; **Metric** and **Checkpoint** carry over from week 4 (performance on unfamiliar problems; does confidence match performance). A row written more than one week ahead is a guess dressed as a plan.

| Week | Add | Remove | Metric | Checkpoint |
|---|---|---|---|---|
| 1 | blank-page recall after every session; self-explanation while reading; the cold gate if Q5 = yes | rereading and highlighting as methods | share of study time spent retrieving (>30%) | can you recall yesterday cold? |
| 2 | spacing: a deck for atomic facts only, ≤10–15 cards/day; prerequisite sketch | cramming; carding lookupable detail | review streak; deck stays lean (>20 min → prune) | are cards atomic and high-value? |
| 3 | deliberate practice on weak sub-skills with immediate feedback; the error log in anger | looking at solutions before a genuine attempt | error-log entries *analysed*, not logged | are the same errors recurring? |
| 4 | interleaved sets; weekly transfer challenge; confidence ratings before answers | labelled-only practice; answer-seeking AI use | performance on unfamiliar problems | does confidence match performance? |

## Output block

Paste into `README.md ## Plan`, every field a value:

```
Track: <A|B|C>            Domain class: <fact-heavy|procedural|conceptual|judgment>
Reader model: <self|mentor+learner>   Mentor: <name from Q3, or —>
Reference answer: <named source from Q4 · A/B: "none → drill-bank.md" · C: "none → stop; feedback source is competency #1">
AI-assisted material: <no | yes → cold gate in week 1>
Files: <from the Files table: the always-five plus the conditional ones the answers add>
Hours/week: <n>   Deadline: <date or —>   Weeks total: <n>
Budget: <the worksheet total> of <hours × 60>; cut: <what, if over; or —>
Session protocols: <day → block, for each study day, durations written out>
Who sets the order: <from the track row>
Core-loop order: <from the track row, written out>
"I can" phrasing rule: <from the track row>
AI policy: <the verbatim paragraph>
Thresholds: <the six rules>
Weekly review: <the Q6 day, 60 min, the five items>
First keep/cut test: <date, two weeks in — does each artifact still earn its place?>
Monday's first item: <exactly one thing — set in README Setup step 5>

Weeks:
| Week | Add | Remove | Metric | Checkpoint |
| 1–4 | the four seed rows, adjusted to the domain |
| 5–<n> | written by each weekly review, one row ahead; Track A: last two = taper |
```
