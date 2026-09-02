# Templatization — multi-model review

Panel: Claude Fable 5.1 (lead) · Gemini 3.1 Pro High (Antigravity) · GPT-5.2/Codex. Date: 2026-09-03.

Question put to the panel: are `interview-prep/` (Track A, self-directed) and `web-engineer-prep/` (Track B, mentor+beginner) proof that LEARNING-SYSTEM.md can be templatized, so the next learning path is low-friction to set up? Both packages took 5–6 review rounds to get the artifacts right; is that churn evidence for a template or against one?

Stage 1 (this section) settles the templatization claim. Stage 2 (below) grounds the substrate question in Notion's current featureset.

---

## Stage 1 — Is it templatizable?

### Executive summary

**Not proof; sufficient evidence for a thin skeleton plus a setup procedure.** Both external legs and the lead converged after one debate round. Antigravity opened with "the premise is false, the friction is the work" and reversed on the evidence below. Codex opened at "strong evidence for a reusable skeleton, not proof" and held. The thing that resolved it: three lessons were learned twice, once per package, under different reader models — and a lesson paid for twice is template-carryable by definition.

### Consensus findings

1. **"Proof" is too strong.** n=2 across Track A and Track B with different reader models (self vs mentor+beginner) shows the skeleton survives different readers. It cannot distinguish "reusable skeleton" from "same owner and same reviewers re-deriving a house style." The test is a **third instance, preferably Track C** in a non-programming domain (law, trading, a new engineering discipline). It confirms if it needs the same artifact grammar and loop with only contents swapped; it falsifies if it needs a new standing artifact, new cadence, or heavy explanatory scaffolding before the three §3 files work. (All three legs.)

2. **Three lessons were learned twice.** Each is a template line, not a domain finding:
   - Reviewer/mentor reasoning must leave the runner's reading path — web-engineer-prep round 6 ("provenance bookkeeping moved out of the beginner's files"), interview-prep 2026-08-29 (study-plan.md 268 → 178 lines, reasoning → CHANGELOG).
   - The error log must fire on **any** AI use, not only on a miss — web-engineer-prep round 6, interview-prep 2026-08-29 (all three reviewers found the same §8 gap).
   - The competency list must be a real file with a proof/score column — web-engineer-prep round 1, interview-prep 2026-08-29 (it had lived inside study-plan.md for seven weeks and needed two signposts to say "the rubric is your competency list").

3. **The churn splits roughly in half.** Of ~11 rounds across both packages, a §12-Minimal skeleton would have removed or shortened 4–6 (Codex) to 6 (Antigravity): the framework audit, the simplicity pass, and web-engineer-prep rounds 1, 2, 4, 6. It would **not** have touched the expensive ones: the 2026-07-22 role check against market data, the 2026-08-01 agentic-coding ownership gap (which pushed §2 "mixed-track" upstream into the framework itself), the freeCodeCamp-vs-Colt course decision with live verification, and gap-detection mechanics. Those are the substantive work of instantiation and no template pre-empts them.

4. **What the skeleton carries** (constant across both packages):
   - Files: `README.md` (index), `competency-list.md`, `error-log.md`, `CHANGELOG.md`; `prerequisite-sketch.md` for Track B, or a named Track-A substitute (implementation intention) with the "if fundamentals are missing, build the sketch" rule.
   - Columns: competency rows as "I can …" with Proof, Date, Score; error log `Date | What I got wrong | What I thought was true | What is actually true | Why | AI use | Route | Confidence-before`, append-only, row written before the lookup.
   - Rules: attempt first, AI critiques not answers; log every AI use; delayed retrieval (same-session counts as never); weekly review with the §11 keep/cut test; reasoning and sign-off records live outside the operating path; route on present-tense cold ability, never on provenance.
   - Track B mentor variant: the course owns the sequence, the mentor detects gaps, `C/G/R` marks, `G` lines must name a teaching source, Keep/Split/Replace, Friday gathers / Saturday judges, mentor bookkeeping in a separate file.

5. **What stays bespoke:** domain and target role; the resource spine (CFSD/Colt vs ADRs/NeetCode/Anki/Hello Interview); competency contents and pass bars; the hours budget; the evidence model (mentor-reviewed vs self-directed interview artifacts); the specific gaps each package found.

6. **The setup procedure is half the template.** Codex's point, accepted by the lead: the owner's goal — reduce friction setting up the next path — is only met if the template includes a *procedure* that front-loads the substantive questions the skeleton cannot answer: pick the track; name the reference-answer source (§3.4); do the budget arithmetic; define the reader/owner model; run the per-item cold test for Track A or AI-assisted material; name the review cadence. Without it the skeleton removes the cheap rounds and leaves the expensive ones exactly where they were.

7. **§3 / §11 / §12 do not forbid a template — they bound it.** A template that ships only the three mandated artifacts with the right columns is not "tooling before the artifacts"; it is the artifacts. The line is crossed by dashboards, relations, status rollups, progress aesthetics, automations, or pre-filled domain wisdom — anything that makes maintaining the system feel like doing the work. Notion has a larger temptation surface than markdown here (Codex); a markdown template can violate §11 too if it preloads essays and bureaucracy.

### Debated items

| Item | Positions | Lead's verdict |
|---|---|---|
| Is the churn evidence for or against? | Antigravity round 1: against — "the friction is a feature." Codex round 1: for, at the artifact/loop layer only. | **For, at the structural layer; irrelevant at the substantive layer.** Antigravity reversed in round 2 on the twice-learned-lesson evidence. |
| Size of the win | Antigravity round 2: large ("removes the structural tax entirely"). Codex: medium (4–6 of 11 rounds). | **Medium-to-large; does not change the action.** Count the rounds honestly: the skeleton removes the rounds that were cheap and annoying, not the ones that were expensive. |
| Substrate | Codex: markdown is the lower-friction default and matches §3 literally; Notion earns only error-log filters and a weekly-review view, and only once there are rows to review. Antigravity round 1: a Notion template defaults the learner to Advanced-tier bureaucracy on day one. | **Open — stage 2 question.** The owner named Notion; the panel's prior is markdown. Research must answer it against Notion's current featureset, not from prior. |

### Falsifiers recorded

- **Codex:** the third instance cannot be set up with the same minimal kit and procedure, with bespoke work limited to source selection, competency content, budget, and pass bars. If it needs a new standing artifact model, the skeleton is too narrow.
- **Antigravity (revised):** the skeleton induces box-ticking — pre-formatted files make the learner treat gap analysis as a form to fill, skipping the L0/L1 work of finding their actual deficits. If that shows up in the third instance, the template removed the friction of structure at the cost of the friction of learning.
- **Lead:** the template grows. If the second version of the skeleton has more files than the first, §11 has already lost.

### Provenance

- Antigravity round 1: read framework §§2, 3, 11, 12; web-engineer-prep/README.md in full; interview-prep/CHANGELOG.md in full; `git log --stat`. Round 2: re-read both CHANGELOGs and both competency-list / error-log files. No web.
- Codex round 1: read framework §§2, 3, 11, 12; all four web-engineer-prep files; interview-prep README, CHANGELOG, competency-list, error-log, parts of study-plan; `git log --stat -4`. Round 2: re-read §§3, 11, 12 and both changelogs. No web.
- Lead: read framework §§2, 3, 11–14 and section index; both READMEs; interview-prep CHANGELOG; `git log --stat`; file line counts. No web in stage 1 (pure reasoning over files; parity does not bind).

No bare-GO or stale-context verdicts this stage; both legs disclosed provenance unprompted after the prompt demanded it.

---

## Stage 2 — Substrate: Notion vs a copyable markdown folder

Method: each leg ran its own research (assume-parity). Lead: `deep-research` skill, three workers, 1 pass, ~50 sources, all full-page fetches. Codex: fresh session, 18 primary URLs opened. Antigravity: web search, but provenance stated "via search summaries" — snippet-level; its numeric claims were re-verified by the lead's workers before counting (see Debated items).

### Executive summary

**Copyable markdown folder (git template repo) for the skeleton. Notion not as the substrate.** All three legs landed here independently; the lead's research corrected two of the external legs' supporting claims (in Notion's favour) without moving the verdict. Notion's real strengths for this skeleton — cheap error-row capture, scheduled repeats, grouped views — do not earn their place at six-week scale under §11, and Notion's costs land exactly on the two things this owner does that a typical learner doesn't: keep git as the source of truth, and run multi-model reviews where agents read files by path.

### Consensus findings (with sources)

**What Notion can do for the skeleton (verified)**
- A public page with "Duplicate as template" carries sub-pages into the duplicator's workspace; databases with fixed schema and inline guidance ship that way. [notion.com/help/duplicate-public-pages; notion.com/help/guides/the-ultimate-guide-to-notion-templates]
- Database buttons' `Add page to` action — creates a pre-filled row (relation, today's date) — is on all plans. `Send webhook` / `Send mail` are paid; `Send Slack` is Plus+. Created time is auto-set and not editable. [notion.com/help/database-buttons; notion.com/help/buttons; notion.com/help/database-properties]
- Database templates can repeat daily/weekly/monthly/custom (launched 2022-11-08, still documented). **No primary page states a plan gate**; inferred Free, unconfirmed. [notion.com/help/database-templates; notion.com/help/guides/automate-work-repeating-database-templates]
- Date property has a `Remind` control; `@remind` inline. Scheduled automation triggers are paid. Free plan automations = Slack-notification only; Free users can *use* automations shipped in a template but not create or edit them. [notion.com/help/reminders; notion.com/help/database-automations; notion.com/pricing]
- Layouts apply to every page in a database, never per view. [notion.com/help/layouts]
- Forms are on all plans; conditional logic is Business+. **Footgun, verbatim:** "If you're sharing a form that is part of a template you have duplicated … set up a separate version of the form from scratch so that all of your form responses go to you and not the original form's creator." [notion.com/help/forms]
- Views: table/board/timeline/calendar/list/gallery/chart; group and sub-group; date filter `is within` has this/last/next-week presets (secondary source only). Free = 1 chart. [notion.com/help/views-filters-and-sorts; landmarklabs.co]

**Markdown round-trip (verified — lossy both ways)**
- Import: headings, lists, code blocks, standard links survive; anchor links and non-standard extensions do not; folder structure only survives if zipped. **Tables are not mentioned on the help page**; two 2026 blogs contradict each other (simple table vs database) and neither shows a test. Unresolved without a hands-on import. [notion.com/help/import-data-into-notion; bulkmd.app; blog.markdowntools.com 2026-06-26]
- Export: full-page databases → CSV with markdown subpages; only current or default view; callouts → HTML; form views can't export; filenames and links carry 32-hex IDs and only resolve if the whole tree is exported. [notion.com/help/export-your-content; raccoon.page 2026-06-13]
- Programmatic workspace export exists only via the Enterprise Admin API (`POST /v1/spaces/{id}/exports`, scope `workspace:export`, help page calls it Enterprise beta). [developers.notion.com/reference/admin/enqueue-space-export; notion.com/help/organization-level-controls]
- The REST markdown endpoints (added 2026-02-26; `GET`/`PATCH /v1/pages/:id/markdown`) work for internal tokens and PATs — but tables come back as `<table>/<tr>/<td>` XML, not pipes, so "git as source of truth" needs a maintained converter either way. [developers.notion.com/guides/data-apis/working-with-markdown-content; …/enhanced-markdown; …/page/changelog]

**Agent access (verified — corrects both external legs)**
- Current `Notion-Version` is **2026-03-11** (not 2025-09-03, which is when databases became containers and schema/rows moved to `/v1/data_sources`). Rate limit: ~3 req/s average per connection plus a plan-scaled workspace limit. [developers.notion.com/reference/versioning; …/docs/upgrade-guide-2025-09-03; …/reference/request-limits]
- Hosted MCP (`https://mcp.notion.com/mcp`) requires interactive OAuth; "working on support for non-interactive authorization." Listed clients include Claude Code, Codex, Antigravity, Cursor, VS Code; **Gemini CLI is not listed.** PATs are REST-only, not compatible with hosted MCP. [developers.notion.com/docs/get-started-with-mcp; …/guides/get-started/personal-access-tokens]
- The open-source `notion-mcp-server` is "no longer actively maintained" / "may sunset"; it still works with `NOTION_TOKEN` for unattended use. [developers.notion.com/docs/hosting-open-source-mcp; github.com/makenotion/notion-mcp-server README]
- **Correction:** hosted `notion-update-page` supports `update_content` — batched exact-match `old_str`/`new_str` (≤100 ops, any miss fails the whole call) — i.e. partial edits, not whole-page replacement. Antigravity's "block-level replacement only" blocker is stale; StackOne's Jan-2026 deep dive predates the feature. [developers.notion.com/guides/mcp/mcp-supported-tools]
- 2026-09-01: the REST API now enforces the Free-plan block limit for internal connections. [developers.notion.com/page/changelog]

**Plans (verified)**
- Free: unlimited blocks for one workspace owner; **1,000-block workspace cap once there are 2+ owners** (3-day grace; trash doesn't reduce the count; Free workspaces can only add people as owners); 10 external guests. Plus $10 / Business $20 per member per month billed yearly (≈$12 / $24 monthly, secondary). Notion Agent / AI Meeting Notes / Enterprise Search are "Limited Trial" on Free and Plus, included on Business+. Forms: Basic (Free) → Custom (Plus) → conditional logic (Business). [notion.com/pricing; notion.com/help/understanding-block-usage]
- **Unresolved:** the pricing page's "Developer platform" rows (Public API, Webhooks, CLI) read as Business/Enterprise-only in 3 of 4 fetches, while developer docs (PAT creation restricted *by default* only on Business/Enterprise; Free block limit enforced via the API as of 2026-09-01) imply Free/Plus can use the API. Needs a human look at the rendered page. [notion.com/pricing; developers.notion.com/docs/create-a-notion-integration; …/page/changelog]
- MCP: no plan gate stated anywhere; multi-source SQL and richer search filters require Business+ with Notion AI. [notion.com/help/notion-mcp; developers.notion.com/page/changelog]

**§11 temptation surface (verified)**
- Gridfiti "Student OS": 12 databases (Classes, Assignments, Flashcards, Readings, Tasks, Timetable, Student CRM, Extracurriculars, Internships, College Apps, Spending, Journal) plus dashboard and Pomodoro widget, $19. "Simple Second Brain Life Planner": 13 tracking systems. "Supreme Second Brain": 30+ prebuilt templates. The gallery's default shape is the §11 failure mode. [shop.gridfiti.com; notion4management.com 2026-08-23]

**The markdown alternative (verified)**
- GitHub template repositories: "Use this template" creates a repo with the same files and a single initial commit; no plan gate. [docs.github.com/…/creating-a-repository-from-a-template]
- **Obsidian Bases** (core plugin, GA 2025-08-18 in 1.9.10; group-by, summaries, list layout 2025-11-11; kanban 2026-09-02 early access): table/cards/list views with global and per-view filters (AND/OR/NOT), multi-property sort, group by one property, formulas — over ordinary `.md` files, reading YAML frontmatter; `.base` files are YAML and embeddable. Obsidian is "free without limits." **Constraint:** Bases rows are *files*, not rows of a pipe table — so getting views over the error log means one note per error, which collides with §3.3's "One file. Append-only." [obsidian.md/help/bases, /bases/views, /bases/syntax, /help/properties; obsidian.md/changelog; obsidian.md/pricing]

### Lead synthesis

1. The only Notion feature either leg said earns its place — grouped/filtered views for the weekly review — now has a free markdown-native equivalent (Bases), and at six-week scale (tens of rows, not hundreds) it isn't needed at all. Antigravity's own falsifier is the escalation trigger: adopt Bases (or a 20-line script over the pipe table) only when weekly pattern-spotting demonstrably fails because the table is too dense.
2. Notion's two costs land precisely on this owner's workflow: (a) git as the source of truth needs a converter (`<table>` XML ↔ pipes) plus either Enterprise export or per-page REST calls; (b) the multi-model loop needs OAuth-interactive hosted MCP (Gemini CLI unlisted) or REST+PAT per leg. Both are maintained integrations — §11 artifacts that must earn their place, and haven't.
3. The mentor variant on Notion Free has a trap: Person 1 must be a **guest**, not an owner, or the 1,000-block cap lands on a beginner's workspace.
4. The pricing-page ambiguity on Public API is the one fact that could change the cost picture ($20–24/member/month for agent access if Business-only). It does not change the verdict; markdown wins on (2) regardless.

---

## Stage 3 — Consensus sign-off

Both legs re-dispatched with the consensus claims C1–C5 (fresh Codex session; Antigravity challenged on provenance and required to open primary pages — it did, listed three, and accepted the `update_content` correction).

### Signed off by all three

- **C1 substrate: copyable markdown folder / git template repo, not Notion.** No blockers.
- **C2 views are an escalation, not a default.** Obsidian Bases or a small script over the pipe table, adopted only when weekly pattern-spotting demonstrably fails. No blockers.
- **C3 resolved in Notion's favour, no effect on verdict.** The pricing page renders plan eligibility as SVG icons, which is why text fetches read the Developer-platform rows as Business-only. developers.notion.com states PAT creation is open to Free workspace owners and the REST API enforces the Free block limit — so the API is on Free. The only "Requires Notion credits" row is Workers (Beta). Lead confirmed via a rendered scrape; incidental: Plus is free for students/educators (1 member).
- **C5 test and falsifiers.** Third instance = Track C, non-programming. Both legs name the same most-likely failure: pre-formatted files inducing box-ticking instead of gap analysis.

### Debated: C4, the deliverable

| Point | Codex | Antigravity (High) | Lead's casting vote |
|---|---|---|---|
| `CHANGELOG.md` as a standalone file | Keep | **Cut** — meta-bookkeeping; web-engineer-prep proves an H2 at the bottom of README suffices | **Keep.** The twice-learned rule is *separation from the runner's reading path*, and the README is the runner's index. web-engineer-prep's changelog lives at the bottom of the **mentor's** file, i.e. outside the learner's path — which is the rule working, not a counter-example. A self-directed package has no mentor file, so a separate file is the only out-of-path place; interview-prep paid a full review round (2026-08-29) for not having one. An empty file has no maintenance cost, which is what §11 measures. |
| Schedule file (`study-plan.md`) | Not required — Track B folds cadence into the mentor README and the sketch's weekly table; Track A needs one because a 6-week countdown with external drills is heavy | **Missing** — both packages needed a home for daily sequencing | **Slot, not file.** Both packages needed a *place* for budget + cadence; only one needed a file. README gets a `## Plan` section (budget arithmetic table, week rows). Rule in the template: split to `study-plan.md` only when the section exceeds a screen. |
| Drill/content file (`question-bank.md`) | Cut from the generic skeleton — Track A content, not substrate | **Missing** — web-engineer-prep survived without one only because freeCodeCamp is a self-grading spine; a Track C domain with no test suite (law, history) has nowhere to put custom drills, and competency proofs degrade into subjective box-ticking | **Accept, as a conditional branch of the setup procedure.** §3.4 already requires naming a source of worked examples and reference answers *before* studying. The procedure's "name the reference-answer source" step forks: external source (course, textbook with answer key, test suite) → no file; self-built → create `drill-bank.md` (`Question \| Grounding artifact \| Answer-key pointer \| Cold mark`). It is the one file the skeleton may grow at setup, decided by a question the procedure already asks. This is not a new standing artifact; it is §3.4 made executable. |
| `Scored` column in the error log | **Add** — interview-prep's log says the gap between `Confidence-before` and `Scored` is the reliable calibration signal; C4 dropped `Scored` | — | **Accept.** |

Divergence on C4 persisted after the round; per protocol the lead's vote is recorded and the item is handed to the owner to ratify (see Actionable Recommendations, item 2).

### Ledger note

Antigravity's stage-2 answer disclosed snippet-level provenance ("via search summaries") and carried one stale blocker (whole-block replacement) — logged as a re-ask that succeeded rather than `stale-context`, because it disclosed its method unprompted and reversed on evidence. No `bare-GO` this run; every leg returned blockers or a falsifier in every round.

---

## Actionable recommendations

1. **Build the template as a markdown directory, not in Notion.** Put it at `learning-system/template/` — it versions with the framework, not with the examples (moved there from `learning-prep/` after the build). Files: `README.md` (index + setup checklist + `## Plan`), `competency-list.md`, `prerequisite-sketch.md`, `error-log.md`, `CHANGELOG.md`; plus `mentor/README.md` in the mentor variant; plus `drill-bank.md` only when setup finds no external reference-answer source. Columns and one-line rules as listed in Stage 1 finding 4, with `Scored` added to the error log. Twice-learned lessons go as one-liners inside the file they concern.

2. **Ratify or overturn the lead's C4 vote** — keep `CHANGELOG.md` as a file; schedule is a README section that splits by rule; drill file is a setup-time branch. Antigravity holds this at High severity; Codex holds the opposite. Your call.

3. **The setup checklist is the half that removes the expensive rounds** — not the files. In order: 10-minute blank-page test → track; name the reference-answer source (→ drill-bank branch); budget arithmetic against the real hours; reader/owner model (who writes, who reads); per-item cold test if any material was AI-assisted; review cadence; date of the first §11 keep/cut test. Each is a question one of the two existing packages paid a review round to discover.

4. **Test it on a Track C, non-programming path before calling it a template.** Confirms if only contents change. Falsifies if a new standing artifact, new cadence, or file growth is needed — or if the pre-formatted files produce box-ticking.

5. **Notion, if ever:** only for the Track B beginner who wants mobile capture, and only Free with the mentor as a *guest* (an owner triggers the 1,000-block cap). Keep git as the source of truth; don't attempt round-trip.

6. **Do not build views now.** Escalate to Obsidian Bases (one note per error) or a 20-line script over the pipe table only when a weekly review demonstrably fails to find patterns in the table.

---

## Stage 4 — Owner's pushback: runtime and re-reading

Owner, after Stage 3: (P1) no learner will edit markdown by hand — finalized artifacts get imported into Notion or some UI; (P2) each new path months apart means re-reading the 67 KB framework, and *that* is the friction, not the files. Both accepted by the lead; Stage 2's "not Notion" was answered for the author and never separated from the learner's runtime, and Stage 1's "setup checklist" understated what the procedure has to carry. One debate round on three revisions.

### R1 — Source vs runtime

**Holds, with one rule that both legs' falsifier forces: the compile is one-shot per path; never re-import.** Markdown + CSV is the source (git, panel-reviewed, agents by path): database schemas as CSV-shaped tables, guidance as markdown, the intake. Notion or any UI is the runtime, compiled once at path start (CSV → database, which Notion imports reliably; md → pages). The learner writes all the *content* there — every "I can" line with its proof, date and score, every error-log row, the week's target lines — and never the *shape*: columns, files, guidance text, rules. Content flows back read-only — API `query data source` or database → CSV, the one export Notion does losslessly.

Both legs independently named the same break: Notion's CSV import creates rows and never upserts (verified at notion.com/help/import-data-into-notion), so a mid-path re-import duplicates rows or strands learner data, and any runtime-only schema edit (a new `Route` value) makes the git source stale. Antigravity: blocker. Codex: holds if the runtime is disposable. **Lead's vote:** this is exactly how both existing packages already lived — authored once, then run. Mid-path structural changes happen in the runtime; if one turns out to be a twice-learned lesson it is back-ported to the source by hand for the *next* path, via CHANGELOG. Nothing structural ever flows back automatically, so there is no upsert problem to solve. Antigravity's mentor-variant trap is overstated: the 1,000-block cap triggers on a second *owner*; a mentor added as a guest (Free allows 10) does not trigger it — verified at notion.com/help/understanding-block-usage.

### R2 — The intake

**Answers P2 only if its output is prescriptive, not descriptive** (both legs, same test: if a field says "see §5," it failed). The intake is the framework compiled into a decision tree; inputs and the derived fields it must emit:

| Input | Derived fields the package must contain, verbatim |
|---|---|
| `track` (A/B/C, from the 10-minute blank-page test; §2) | "I can" phrasing rule; which artifacts (Track A swaps the sketch for an implementation intention); sequence constraint for the track (§5 step order, e.g. Track B: worked example → completion problem → blank file, never skip) |
| `domain_class` (procedural / conceptual / judgment; §9, §9.1) | Judgment → decision log with process-before-outcome grading and calibration loop; otherwise not |
| `reader_model` (self / mentor+learner) | File split (mentor bookkeeping out of the learner's files); cadence owner; Friday-gathers/Saturday-judges |
| `reference_answer_source` (external course / textbook key / test suite, or none; §3.4) | None → `drill-bank.md` (Question, Grounding artifact, Answer-key pointer, Cold mark) |
| `ai_assisted_material` (yes/no; §2 mixed-track) | Yes → per-item cold gate before any re-reading; relabel rule |
| `hours_budget` | Session protocol with exact durations (§6); first-30-days table with adds/removes/metric per week (§13); the AI-policy prompt text (§8: critique or completion problem, never the answer); the diagnostic threshold (§10: same error three times → stop, do X) |

### R3 — A generator skill

**Deferred behind the Track C instance; the intake ships now as a form Claude runs, not a skill.** Antigravity: High — "automating a process you haven't stabilized manually"; the generator will confidently mis-track a Track C domain (trading as Track A recall instead of §9.1 judgment) and the owner will stop reviewing. Codex: not §11-violating in principle — web-engineer-prep's README *is* a human doing this compilation on Saturdays — but it fails the moment it becomes a project; falsifier: can it produce a usable package in under an hour with no custom debugging? **Lead's vote:** both are right, and they compose into a build trigger. Today: `template/INTAKE.md` is a form; the owner answers it in a Claude session, and Claude — not the owner — reads the framework and fills the derived fields. That shifts the re-reading to the model now, at zero build cost. Build `/learning-path` only after three hand-compiled packages (A, B, C) exist with their intake answers recorded; the skill's exemplars are those three. If it ever needs more than an hour to produce a package, it has become the tool.

### Track C (unchanged, reinforced)

Both legs: a generator built on two programming packages will assume every domain has a compiler or a test suite for feedback. Of the owner's three candidates, Codex's ordering: **music theory** is the cleanest test (conceptual/procedural, non-programming, low-stakes); trading tests §9.1 judgment but is noisy and high-stakes; backend is too close to web engineering to falsify anything.

### Provenance

Antigravity: read framework §§2, 5, 8, 9.1, 11 and both READMEs; one web lookup (CSV import page). Codex: framework lines 325–440, web-engineer-prep README lines 1–115; no web. Lead: prior stage research; block-limit and guest facts from Stage 2 workers.

---

## Actionable recommendations (revised after Stage 4)

1. **Source is markdown + CSV in `learning-system/template/`; runtime is whatever UI the learner uses, compiled once per path.** Never re-import. The learner authors all rows in the runtime (competency lines, error rows, weekly targets); rows flow back via API query or database→CSV; columns, files, guidance and rules never flow back.
2. **Files in the source:** `INTAKE.md` (the R2 form, with the derived-field table above as its output contract), `README.md` (index + `## Plan`), `competency-list.md`, `prerequisite-sketch.md`, `error-log.md` (with `Scored`), `CHANGELOG.md`; `mentor/README.md` in the mentor variant; `drill-bank.md` only when the intake finds no external answer key; `decision-log.md` only for judgment domains (§9.1 — added at build, panel split on file vs schema block; lead sided with Codex: a schema block is not an append-only surface). Tables marked `Database:` are the Notion import; unmarked tables are page content.
3. **Ratify the lead's C4 vote** (Stage 3) — keep `CHANGELOG.md`; schedule as a README section; drill file as an intake branch.
4. **Run the intake with Claude in the loop for the next path; do not build the skill yet.** Build trigger: three hand-compiled packages with recorded intake answers.
5. **Make the third path music theory, not backend.** Backend cannot falsify the template; music theory can.
6. **Notion runtime rules:** mentor as guest, never owner, on Free; CSV import for databases, markdown for guidance; agents read via hosted MCP (interactive OAuth) or REST + PAT; nothing structural is edited in Notion without a CHANGELOG line for the next compile.

---

## Stage 5 — Build and sign-off

Owner ratified the C4 vote and asked for `template/` to be built and panel-signed. Built 2026-09-03; gauntlet roster for a docs-only change is Codex, plus Antigravity under the equal-at-bats trial. Four rounds to sign-off.

| Round | Codex | Antigravity | What changed |
|---|---|---|---|
| 1 | NO-GO: "last table = database" fails on README/INTAKE/sketch; `Mentor` never asked; `Files` needs scattered logic; sketch §3 Track-B-specific; keep `decision-log.md` as a file; 60-min row lacks "schedule retrieval later" | NO-GO: same compile failure on the sketch's three tables; week rows dropped from `## Plan` (C4 violation); `Budget` not prescriptive; fold `decision-log.md` into INTAKE; `Route` jargon fails the beginner floor; CHANGELOG conflation | Compile rule → explicit `**Database: <name>**` captions with a file→databases→page map in README; `Weeks:` table in the output block; Q6 budget worksheet with "the bar" defined; Q3 asks the mentor's name; Files derivation table; `Route` → `forgot` / `never-learned` / `unknown`; sketch defers to the intake's who-sets-the-order rule; CHANGELOG runtime note assigned to the reviewer. **Split on decision-log resolved for the file** (a schema block is not an append-only surface); Antigravity accepted in round 2 |
| 2 | 0 blockers. Should-fix: weekly-review day not asked; weeks 5+ under-specified | 0 blockers. Should-fix: `Session protocol` field has no block routing. **Falsifier: Track C + Q4 none → drill-bank pointers anchored to sources the learner can't judge** | Q6 asks the day; **weeks 5+ are not written at intake** — each weekly review writes the next row (Add = the log's top pattern + undone lines; Remove = the thing to stop); block-routing rule by hours band; **Track C + none = stop**, feedback source is competency #1 (§5), in Q4, the Files table, the output block and drill-bank.md |
| 3 | Should-fix: Track C/none leftovers in Files table and output block; study days not asked | **Blocker:** mentor-sequence deadlock when a Track C learner names the mentor as feedback source. Should-fix: 120-min block opens without recall; 30-min shape vs routing. **Falsifier: "all ten steps" / "start at step 4" reference a loop the plan never contains** | Leftovers fixed; Q6 asks study days; mentor owns ordering iff named as feedback source; 120-min opens with recall; 30-min = "practice, or one small new item"; **the ten-step core loop written into INTAKE** with move-on / if-not columns, and track rows name steps |
| 4 | **GO.** Nits: "stop" should not delete the base five; mentor "section titles" line. Falsifier: a Track C feedback source that can critique but not sequence | **GO.** No nits. Falsifier: an asynchronous feedback source stalls a Track C session at FEEDBACK | Both nits taken. Falsifier answered with one line in the Track C loop cell: batch DEFINE→RETRIEVE across the week, grade together, then PRACTICE — the mentored package's Saturday, generalised |

**Verification run** (docs-only, so the evidence is structural): every `Database:` caption is followed by a table header; every file README links to exists; the output block contains no `§` pointers; no stale `Route` names remain. Nine files, ~400 lines.

**Falsifiers carried into the first Track C use:** (1) pre-formatted files induce box-ticking instead of gap analysis; (2) the feedback source can grade but cannot order, and "feedback source sets the order" overfits the mentor/course case; (3) the skeleton needs a file this template doesn't have.

### Ledger note

No `bare-GO` in any round: every leg returned blockers, should-fixes, nits, or a falsifier. Round 2's Track C falsifier (Antigravity) and round 3's ten-steps falsifier (Antigravity) were the two findings that changed the template most; the compile-rule failure was found independently by both legs in round 1.
