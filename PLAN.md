# Story Factory — Build Plan

**Date:** 2026-10-10 · **Status:** BUILT — lean v1 skill live at
`~/workspace/skills/story-factory/SKILL.md` (2026-10-10). the author:
"machinery in place and ready" for the first idea; no pilot idea yet.
**Commission:** "A consistent pipeline I can throw any idea into and develop it into something interesting," integrating with the existing chapter pipeline.
**Research basis:** four tracks under `~/workspace/story-factory/research/` —
`track-a-frameworks.md` (22 published story frameworks), `track-b-community.md`
(webserial craft, Sanderson/Writing Excuses, TV bibles, discovery writers),
`track-c-ai-pipelines.md` (9 GitHub systems, 8 papers, 8 products),
`track-d-local-audit.md` (existing chapter pipelines + integration seam).

---

## 1. The converged answer

Every source surveyed — craft books, webserial forums, TV writers' rooms,
research papers, and shipped AI pipelines — converges on the same shape:

1. **The pipeline's job is slots, order, and gates — not creativity.**
   Track A: "every framework treats [the idea→concept steps] as falsifiable
   gates, not creative exercises. Creativity happens in *filling* the slots;
   the pipeline's job is the slots, the order, and the gates."
2. **Planning dominates everything downstream.** Three independent ablations
   agree: removing the outline hurt quality 4–5× more than removing any
   prose-rewrite stage (StoryWriter 4.3→2.5 vs −0.3 per rewrite removal;
   Re3's plan removal was catastrophic, its edit module ~no effect). DOC:
   deeper plans increase *interestingness* (+20.7%), not just coherence.
   **For any fixed budget, spend it upstream.**
3. **The idea→concept transition is a 7-operation sequence** every framework
   agrees on: capture spark → classify the idea (MICE) → attach
   protagonist+problem (LOCK) → name opposition → decide the change →
   compress into a premise line → stress-test for sustainability.
4. **Snowflake is the chassis.** Ingermanson's 10-step fractal expansion
   (sentence → paragraph with three disasters + ending → character sheets →
   synopsis → scene list → draft) is the only surveyed framework that is
   already a full idea→draft pipeline; other frameworks supply the
   *contents* of each expansion step.
5. **Codification must be queryable, not prose.** NovelCrafter's Codex
   (database, not prose), Arc Ledgers (promises separate from facts),
   canon-as-versioned-DB with change proposals, editable knowledge graphs
   as the authoring surface. Track B: "a Google Doc is not a bible, it is
   a graveyard."
6. **Deterministic orchestration; model judgment only at the content
   level** (InkOS v1→v2 lesson). Two immune systems: deterministic checks
   first (plantable-failure-testable), LLM judge second.
7. **Over-formalizing macro-structure is a trap.** devhxj/novelist's author
   *retired* his own heavy upstream assembly machinery: "the author
   controls the macro structure and AI refines and expands." Interviews +
   coverage gates + human confirmation won. The factory must not become
   process replacing judgment.

**Creative-authority boundary (the author, 2026-10-10):** two domains.
*Projects in development* (the factory): **the author is the creative
authority** — every creative decision is his; Sol is not brought in.
*Projects in progress* (the chapter pipeline): **Sol is the creative
lead** — packets, prose, revisions (standing 2026-10-06 rule, unchanged).
Atlas's factory lane: interview design, capture, verification, mechanical
gates. Atlas assembles and organizes the author's decided answers into
documents; Atlas never invents creative content — undecided slots stay
OPEN. Sol enters at the Stage 6 handoff, receiving the bootstrap bundle
as creative lead.

---

## 2. The seven stages

Each stage: purpose · inputs · outputs · gate. Gates are falsifiable —
a stage either passes with evidence or sends the idea back.

### Stage 0 — INTAKE (idea capture & normalization)

- **Purpose:** no idea gets lost; every idea enters in a standard shape.
- **Input:** raw idea text, any length/form (what-if, image, character,
  scene-vision, theme itch).
- **Process (Atlas):** file under `stories/<slug>/ideas/<idea>.md`; tag seed
  type — concept/theme, character, setting, image/scene-vision
  (fantasy-writers.org seed taxonomy); record date, source, the author's
  own words verbatim. Honest scope hypothesis: "if the idea only supports
  a short, expand only the idea, not the ambition."
- **Output:** intake file — spark + seed type + source + scope hypothesis.
- **Gate:** none. Intake never rejects; it classifies.

### Stage 1 — INTERSECTION & TRIAGE

- **Purpose:** one idea is not a book (Sanderson). Find what the idea
  actually is before developing it.
- **Input:** intake file.
- **Process (the author, via Atlas-designed interview):** identify 2–3
  constituent ideas in or adjacent to the spark; Atlas poses the collision
  as interview questions — bounded alternatives with practical
  consequences, never steering; the author decides. Then three-pillar triage
  (Sanderson): rate setting / plot / character strength honestly; name the
  dominant pillar and the thin ones; decide fix vs shelve for each thin
  pillar.
- **Output:** intersection note — the ideas, their collision, triage
  verdict.
- **Gate:** TRIAGE — if no productive collision and no fixable pillar, the
  idea returns to the idea file (shelved, never deleted). First fail-fast.

### Stage 2 — PREMISE DEVELOPMENT (the 7-operation sequence)

- **Purpose:** turn the intersected idea into a workable story concept.
- **Input:** intersection note.
- **Process (the author creative; Atlas holds the slots, interviews, captures):**
  1. Classify via **MICE** — what kind of story does this want to be?
     (A milieu idea developed with event machinery breaks.)
  2. Attach protagonist + problem (**LOCK** L+O): protagonist placed at a
     friction point of the setting, wanting something *right away*.
  3. Name the opposition (**LOCK** C): designed, not just named — Truby's
     character web (each supporting character positioned against the
     hero's moral problem).
  4. Decide the change: what transforms? (MICE closure rules; hook as the
     opposite of the resolution.)
  5. Compress into the **premise line** — Weiland template
     (situation / lead / objective / conflict / opponent / disaster) +
     theme line: Story Grid controlling idea ("[value] results when
     [condition]") or Truby moral argument.
  6. Layer **elemental genres** (Writing Excuses S11): dominant emotional
     engine + 2–3 supporting layers — this names which promises the story
     is making.
  7. Stress-test: Ingermanson's **three disasters + ending**; Truby's 7
     steps as a checklist; Hardy's **premise-novel test** (if the
     protagonist can be removed and the story still happens, it is not a
     premise yet).
- **Output:** concept brief — premise line, LOCK slots, MICE class,
  designing principle, moral argument / controlling idea, genre blend,
  three disasters + ending; OPEN markers where undecided (never silently
  filled).
- **Gate:** COMPLETENESS — every slot filled or explicitly OPEN;
  premise-novel test passed; three disasters named. Restricted-critic pass:
  every claim traces to author input; no filled OPENs.

### Stage 3 — CONCEPT CODIFICATION (the story brief)

- **Purpose:** freeze the concept into a stable, checkable document before
  worldbuilding expands it.
- **Input:** concept brief.
- **Process (Atlas writes the brief strictly FROM the author's decided answers
  — the Glyphbound capture pattern: organizing decisions, never inventing;
  where open, record as open; the author approves the brief):** the story
  brief; **promise inventory** (Sanderson's four
  types — tone, story, character/conflict, structural — plus genre and
  medium as promises); **ending intent** as a first-class artifact;
  story-form decision (serial vs novel vs shorts; length target; cadence).
- **Output:** `STORY.md` — premise, concept brief, promise inventory,
  ending intent, story-form decision.
- **Gate:** STANDINGS SEED — every author verdict becomes a ruling in
  `standings/rulings-<project>.md` (same-day rule); restricted critic
  checks traceability.

### Stage 4 — BIBLE BUILD (world/character codification)

- **Purpose:** codify world and cast as queryable canon, not prose.
- **Input:** story brief.
- **Process:** (a) knowledge architecture FIRST (the Glyphbound
  `creature-knowledge-architecture` pattern: per-domain organization,
  Markdown+YAML frontmatter, anti-duplication rules); (b) Atlas assembles
  entries strictly from the interview record — nothing canon until
  accepted, no invention beyond the author's answers, PROPOSED status line on
  every file; creative expansion happens as further interview rounds, not
  as drafted invention; (c) the
  six-part register: cast register (onion sheet per character —
  outer/inner personality, circle, trauma, breakpoint, cloud, pursuit,
  nuance), series timeline, world-rules document, places file,
  **continuity log** (when each fact became true, which installment
  established it, who knows it, whether still current), open-threads
  register; (d) foreshadowing ledger + **Arc Ledger** (reader promises
  tracked separately from world facts) seeded from the promise inventory.
- **Output:** `bibles/` tree — all PROPOSED until the author accepts each
  file.
- **Gate:** ACCEPTANCE — the author accepts bible files (or delegates);
  restricted critic: every entry traces to author input or is marked
  OPEN/proposed.

### Stage 5 — ARC PLAN (resolution-first outline)

- **Purpose:** produce the series plan the chapter pipeline's intake
  requires as input #1.
- **Input:** bibles seed, ending intent.
- **Process:** MICE thread map (nesting diagram; threads close in reverse
  order); resolution-first outlining — chapter-scale tools (Harmon's
  Story Circle, Wells' 7-point) for episode-shaped units, novel-scale
  tools (Truby 22, Save the Cat beats, Weiland percentages) for arcs;
  **per-beat affective function** (Tian et al.: arc position,
  turning-point placement, tension direction, arousal/valence target —
  +40% reported on suspense/arousal); mystery threads stated plainly with
  payoff horizons; per-chapter one-line contract + handoff; Big-P/little-p
  arc stack.
- **Output:** `series-plan.md` — arcs, chapter list with contracts +
  handoffs, mystery threads + payoff horizons.
- **Gate:** COVERAGE — every promise in the inventory has a planned payoff
  location; every chapter has a contract; independent outline critique
  (CRPLAN pattern — critique the plan where it is cheap, before any
  chapter pipeline runs).

### Stage 6 — HANDOFF (chapter-1 intake readiness)

- **Purpose:** the factory's exit is operational, not aesthetic.
- **Input:** all upstream artifacts.
- **Process (Atlas):** assemble the bootstrap bundle — premise record +
  doctrines, series plan, bibles seed, voice profile seed (POV/tense/
  register decision), `continuity.md` seed, defect-log seed, originality
  receipt (6-gram comparison vs searched comparables), story-form
  decision; run a dry chapter-1 intake against it.
- **Output:** handoff manifest.
- **Gate:** EXIT CRITERION — **chapter-1 intake passes Phase 0 without
  improvisation.** One verifiable sentence; the existing pipeline is the
  judge.

### Discovery branch (for ideas that resist outlining)

Premise sentence + promise audit (Stages 0–3) are still required; the
resolution-first outline is skipped. Write from a character in a scene,
outline *as you go*, cycle (jump back, re-read, fix, surge forward), cut
dead ends (Dean Wesley Smith); capture line-for-scene after discovery
(Lisle — the outline is a floor, not a ceiling). Mid-story idea changes
go through **What-If branching** (Versatile): premise change →
per-scene keep/rewrite/drop plan → reviewable before anything moves.

---

## 3. The gates system (cross-cutting, every stage)

1. **Completeness gates** — slots filled or explicitly OPEN. Nothing
   silently filled, ever (Glyphbound interview discipline).
2. **Falsifiable tests** — premise-novel test, Doorway of No Return,
   three-disasters, controlling-idea sentence. A test that cannot fail is
   decoration.
3. **Independent-critic passes** — restricted context; Tier M (mechanical,
   tool-grounded) runs ungated; Tier O (opinion) only on gaps named by an
   external critic or the author. The critic diagnoses; it never revises.
4. **Human choice cards at decision points** — author picks
   beats/directions from presented options with recorded reasons; corpus
   coverage honestly labeled (devhxj pattern).
5. **Scored loops with plateau/decline stopping** (gesaku) — modify →
   evaluate → keep/discard at every phase instead of fixed cycle counts.
6. **Deterministic checks before model judgment** — contradiction rules,
   regex slop screens, and completeness checks run first and are
   positive-control tested; the LLM judge comes second.
7. **Proposed-vs-accepted status discipline** — every factory file carries
   the status line until the author accepts it; bibles accept only accepted
   canon.

---

## 4. Integration with the chapter pipeline

The factory sits **upstream of chapter-workflow/serial-workflow Phase 0
(intake)**. The handoff is 1:1 against intake's inputs:

| Factory output | Satisfies intake input |
|---|---|
| Premise record + author doctrines | intake authority context; `rulings-<project>.md` seed |
| `series-plan.md` (chapter contracts + handoffs) | serial-intake input #1: the arc plan's entry per chapter |
| Bibles seed | intake: affected bible records |
| Voice profile seed | intake: voice profile |
| `continuity.md` seed | intake: serial continuity file |
| Story-form decision | pipeline variant + cadence selection |
| Defect-log seed | intake: risk selection source |
| Originality receipt | chapter-workflow intake: originality PASS |

The factory fills exactly the blank the `universal-fiction-pipeline-DRAFT`
names but never defines: its "day-one gate" requires premise, doctrines,
bibles seed, and series plan — with no phase for producing them.

---

## 5. What NOT to build (the failure catalog)

Lifted from Track C §4c — each has a named corpse:

- Post-hoc fact extraction + automated correction as the consistency
  strategy (Re3's Edit module barely moved human metrics).
- Brainstorm without selection — directions generated, nothing evaluated
  (Sudowrite's gap).
- Lorebook-only memory — drifts past ~15k words without outline
  machinery (NovelAI).
- Inert planning artifacts — stages whose output no later stage consumes
  (Plottr). Every factory stage's output must be consumed by a named
  downstream gate.
- Chat-orchestrated autonomy without gates — volume, no quality control
  (terminal-velocity).
- Heavy upstream assembly machinery — retired by its own author; process
  replacing judgment (devhxj/novelist).
- Natural-language orchestration kernels — replaced by deterministic
  scheduling (InkOS v1→v2).
- One-click generation with no taste gate — coherent, predictable,
  slop-marked (KDP generators).

---

## 6. Open gaps the factory must invent (no prior art)

1. **A taste/interest gate for the idea itself.** The literature measures
   generation quality, never whether a premise is *worth developing*.
   Starting design: human choice cards + scored gates at Stage 1 and
   Stage 2, with the author as the final taste gate. Placement of his review
   is a build decision (see §8).
2. **Mid-story re-planning.** Every surveyed system freezes its outline;
   none has a validated re-planning mechanism. What-If branching is the
   closest instrument; the factory needs it as a first-class stage, not
   an afterthought.
3. **Evaluation is the binding constraint.** No validated automatic metric
   for coherence/pacing/relevance exists. The factory's answer: cheap
   proxy gates (completeness, falsifiable tests, deterministic checks) +
   deliberate human review placement, never a claim that a score *is*
   quality.

---

## 7. Build recommendation

A `story-factory` orchestrator skill plus phase skills mirroring the
`serial-*` conventions (`factory-intake`, `factory-premise`,
`factory-codify`, `factory-bible`, `factory-arcplan`, `factory-handoff`),
reusing without re-inventing: restricted-critic briefs, Tier M/Tier O
discipline, standings/rulings with the same-day rule, the deterministic
audit pattern with positive controls, the blind-A/B protocol for
competing directions, run-manifest + status-line conventions, and the
Markdown+YAML knowledge architecture. Sol-invocation appears only at the
Stage 6 handoff. **Pilot on a fresh idea** — do not
retrofit Glyphbound or Ghost Weights; prove the factory on something new,
then judge it by its own exit criterion: does chapter-1 intake pass
without improvisation, and does Sol's first packet need fewer
corrections?

---

## 8. Decisions needed from the author before a build

1. **Lean vs full** — ANSWERED 2026-10-10: lean v1 first (Atlas
   recommendation, no objection); expand after the interview loop is
   proven on a real idea.
2. **Sol's shape in the loop** — ANSWERED 2026-10-10: Sol is not in the
   factory; he becomes creative lead at the Stage 6 handoff. ANSWERED
   2026-10-10: yes — Sol gets a review pass on the bootstrap bundle at
   handoff, scoped strictly to "can I run packets from this?" (not
   creative input).
3. **Discovery branch** — DEFERRED to v2 (Atlas recommendation, no
   objection).
4. **Pilot idea** — a fresh idea of his (he is the creative engine now, so
   the pilot needs an idea he's willing to develop), or should Atlas
   propose test ideas for him to react to?
5. **Taste-gate placement** — REFRAMED 2026-10-10: the author authors
   throughout, so gates are his in-session verdicts rather than
   between-stage reviews. ANSWERED 2026-10-10: guiding interview — live
   sessions, Atlas guides with bounded alternatives and consequences,
   the author decides.
6. **universal-fiction-pipeline-DRAFT** — should the factory supersede /
   absorb that draft, or stay a separate proposal?
