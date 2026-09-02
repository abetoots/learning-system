# <path name> — learning path

Copied from `~/learning-system/template/` on <date>. The template owns the **shape** of these files; you own everything written in them. Framework: `~/learning-system/LEARNING-SYSTEM.md` — consulted by section number only when the intake says so.

## Files

| File | What it is | Who writes it | When |
|---|---|---|---|
| [INTAKE.md](INTAKE.md) | Six questions that compile the framework into the `## Plan` block below | you, once | before anything else |
| [competency-list.md](competency-list.md) | "I can…" lines with proof, date, score | learner | end of every session; weekly review |
| [prerequisite-sketch.md](prerequisite-sketch.md) | the answer-key contract, what must be true first, this week's targets | learner holds the pen; mentor supplies the judgment | week 0, then weekly |
| [error-log.md](error-log.md) | append-only rows; the *why* column is the point | learner | any miss, any stall over 10 min, **any AI use** |
| [CHANGELOG.md](CHANGELOG.md) | review rounds, what changed, what was rejected | reviewer | review rounds only. Not needed to run the plan |
| [drill-bank.md](drill-bank.md) | questions with answer-key pointers — **only if INTAKE Q4 = none** | learner | week 0, then as the log finds gaps |
| [decision-log.md](decision-log.md) | pre-action thesis, process graded before outcome — **only if INTAKE Q2 = judgment** | learner | before every decision |
| [mentor/README.md](mentor/README.md) | the mentor's operating doc — **only if INTAKE Q3 = mentor** | mentor | Saturday |

Delete the conditional files the intake strikes. Add nothing until the plan has run two weeks and you can name the problem the addition solves (§11).

## Setup

1. Answer [INTAKE.md](INTAKE.md). Twenty minutes, in a Claude session or by hand.
2. Paste its output block into `## Plan` below. Every field must be a value, not a pointer.
3. Delete the conditional files the intake struck.
4. Write the first five competency lines and sign the answer-key contract in the sketch.
5. Compile to your runtime (below). Name Monday's first item before you stop.

## Plan

<!-- paste the INTAKE output block here, including the Weeks table -->

Rule: if this section outgrows one screen, move it to `study-plan.md` and leave a link here.

## Runtime

The learner does not run this plan in markdown. Compile once, at path start. Tables marked **Database:** are databases — the header row is the schema, import as CSV. Everything else in a file is that file's guidance page. Unmarked tables (this file, the intake, the contract in the sketch) are page content, not databases.

| File | Databases | Page |
|---|---|---|
| competency-list.md | `competency-list` | guidance above it |
| prerequisite-sketch.md | `prerequisites`, `weekly-targets` | §1 contract stays a page |
| error-log.md | `error-log` | guidance above it |
| drill-bank.md | `drill-bank` | guidance above it |
| decision-log.md | `decision-log` | guidance above it |
| mentor/README.md | `provenance` | the Saturday protocol |
| README.md, INTAKE.md, CHANGELOG.md | — | README and `## Plan` are pages; INTAKE and CHANGELOG stay in git |

**Never re-import.** A structural change mid-path (a new column, a new `Route` value) is made in the runtime and gets one line in `CHANGELOG.md` — written by the reviewer, not the learner — so the next compile carries it. Rows flow back read-only (API query, or database → CSV).

Notion Free: the mentor joins as a **guest**, never a second owner — a second owner triggers the 1,000-block cap.
