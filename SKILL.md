

# Story Factory (lean v1)

Turn any raw idea into a developed story concept the chapter pipeline can
consume without improvisation. Single orchestrator skill; one stage per
interview round.

Research basis (read before extending this skill, not on every run):
`~/workspace/story-factory/research/` (four tracks) and
`~/workspace/story-factory/STORY-FACTORY-PLAN.md`.

## Purpose

The pipeline's job is slots, order, and gates — not creativity. Every
stage forces the same discipline: fill each slot with the author's decided
material, mark what is undecided OPEN, and pass a falsifiable gate before
moving on. Nothing is silently invented, ever.

## Creative-authority boundary (read first, applies to every stage)

- **Projects in development (this skill): the author is the creative
  authority.** Every creative decision is his. Sol is not brought in.
- **Projects in progress (chapter pipeline): Sol is the creative lead**
  (standing 2026-10-06 rule, unchanged).
- **Atlas's lane:** interview design, capture, verification, mechanical
  gates. Atlas assembles and organizes the author's decided answers into
  documents. Atlas never invents creative content — undecided slots stay
  OPEN, never filled with plausible text.
- Sol enters once, at Stage 6, for a scoped review of the finished
  bundle: "can I run packets from this?" — not creative input.

## The guiding interview (interaction protocol, every stage)

- Atlas asks; the author decides. Run one stage per interview round; end each
  round with that stage's gate. Do not stack stages.
- Pose creative questions as **bounded alternatives (2–4 options)** with
  the **practical consequences** of each, in plain language, without
  steering. Alternatives must be derived from the author's stated material.
  Purely illustrative options must be labeled illustrative and carry no
  weight.
- **Capture answers verbatim** in the interview record, attributed and
  dated. Separate the author's words from Atlas's framing, always.
- Explanations of craft (what a premise line is, why MICE matters) are
  Atlas's lane and are welcome — teaching the machinery is not inventing
  content.
- If the author stalls on a slot, offer to mark it OPEN and move on. OPEN is
  a valid gate outcome; a filled-with-guess slot is never valid.

## Workflow

Project root: `~/workspace/stories/<slug>/`. Every file carries
`**Status:** PROPOSED — not accepted canon.` until the author accepts it.

### Stage 0 — INTAKE

**Purpose:** no idea gets lost; every idea enters in a standard shape.
**Input:** raw idea text, any length or form (what-if, image, character,
scene-vision, theme itch).
**Process (Atlas):** file it at `stories/<slug>/ideas/<idea>.md`; tag the
seed type — concept/theme, character, setting, image/scene-vision;
record date, source, the author's words verbatim. Add an honest scope
hypothesis: if the idea only supports a short, say so — expand the idea,
not the ambition.
**Output:** intake file — spark + seed type + source + scope hypothesis.
**Gate:** none. Intake never rejects; it classifies.

### Stage 1 — INTERSECTION & TRIAGE

**Purpose:** one idea is not a book. Find what the idea actually is.
**Input:** intake file.
**Process (guiding interview):** identify 2–3 constituent ideas in or
adjacent to the spark; pose the collision — what conflicts and
relationships emerge when they meet? Then three-pillar triage: rate
setting / plot / character strength honestly; name the dominant pillar
and the thin ones; for each thin pillar, the author decides fix vs shelve.
**Output:** intersection note — the ideas, their collision, triage
verdict.
**Gate:** TRIAGE — if no productive collision and no fixable pillar, the
idea returns to the idea file (shelved, never deleted). Failing this gate
is a useful verdict.

### Stage 2 — PREMISE DEVELOPMENT

**Purpose:** turn the intersected idea into a workable story concept.
**Input:** intersection note.
**Process (guiding interview, seven operations in order):**
1. **Classify** via MICE — Milieu, Inquiry, Character, or Event? A milieu
   idea developed with event machinery breaks; name the dominant thread.
2. **Attach protagonist + problem** (LOCK: Lead + Objective) — place the
   protagonist at a friction point of the setting; they want something
   specific *right away*.
3. **Name the opposition** (LOCK: Confrontation) — designed, not just
   named: who or what actively prevents the objective, and why?
4. **Decide the change** — what is different at the end? (Hook as the
   opposite of the resolution.)
5. **Compress into the premise line** — *After (setup), a (specifics)
   (lead) is in (situation). To (objective), they must (conflict)
   against (opponent) before (disaster).* Add the theme line:
   "[value] results when [condition]."
6. **Layer elemental genres** — the dominant emotional engine + 2–3
   supporting layers. This names which promises the story is making.
7. **Stress-test** — name **three disasters and an ending**; run the
   premise-novel test (if the protagonist can be removed and the story
   still happens, it is not a premise yet).
**Output:** concept brief — premise line, LOCK slots, MICE class,
designing principle, theme line, genre blend, three disasters + ending;
OPEN markers where undecided.
**Gate:** COMPLETENESS — every slot filled or explicitly OPEN;
premise-novel test passed; three disasters named. Then a restricted
critic pass: every claim traces to the author's stated material; no filled
OPENs. The critic diagnoses; it never revises.

### Stage 3 — CONCEPT CODIFICATION

**Purpose:** freeze the concept into a stable, checkable document before
worldbuilding expands it.
**Input:** concept brief.
**Process (Atlas):** write the story brief **strictly from the author's
decided answers** — organizing decisions, never inventing. Build the
**promise inventory** (tone, story, character/conflict, structural
promises, plus genre and medium as promises). Record **ending intent**
as a first-class artifact. the author decides the story form: serial vs
novel vs shorts, length target, cadence. the author approves the brief.
**Output:** `STORY.md` — premise, concept brief, promise inventory,
ending intent, story-form decision.
**Gate:** STANDINGS SEED — every the author verdict becomes a ruling in
`~/workspace/standings/rulings-<project>.md` (same-day rule). Restricted
critic checks traceability.

### Stage 4 — BIBLE BUILD

**Purpose:** codify world and cast as queryable canon, not prose.
**Input:** story brief.
**Process:** (a) knowledge architecture FIRST — per-domain organization,
Markdown+YAML frontmatter, anti-duplication rules (the Glyphbound
`creature-knowledge-architecture` pattern); (b) Atlas assembles entries
**strictly from the interview record** — creative expansion happens as
further interview rounds, never as drafted invention; (c) the six-part
register: cast register (per character: outer/inner personality, circle,
trauma, breakpoint, cloud, pursuit, nuance), series timeline,
world-rules document, places file, **continuity log** (when each fact
became true, which installment established it, who knows it, whether
still current), open-threads register; (d) seed the foreshadowing ledger
and the **Arc Ledger** (reader promises tracked separately from world
facts) from the promise inventory.
**Output:** `bibles/` tree — all PROPOSED until the author accepts each file.
**Gate:** ACCEPTANCE — the author accepts bible files (or delegates).
Restricted critic: every entry traces to his answers or is marked
OPEN/proposed.

### Stage 5 — ARC PLAN

**Purpose:** produce the series plan the chapter pipeline's intake
requires as input #1.
**Input:** bibles seed, ending intent.
**Process (guiding interview):** draw the MICE thread map (threads nest;
close in reverse order of opening). Outline **resolution-first**: pick
the ending, then build backward (chapter-scale: Story Circle / 7-point;
arc-scale: Truby 22 / Save the Cat beats / percentage beats — whichever
fits the story form). Annotate each beat's **affective function**: arc
position, turning point, tension direction, emotional target. State
mystery threads plainly with payoff horizons. Write the per-chapter
one-line contract + handoff.
**Output:** `series-plan.md` — arcs, chapter list with contracts +
handoffs, mystery threads + payoff horizons.
**Gate:** COVERAGE — every promise in the inventory has a planned payoff
location; every chapter has a contract. Independent outline critique
before anything moves downstream (critique the plan where it is cheap).

### Stage 6 — HANDOFF

**Purpose:** the factory's exit is operational, not aesthetic.
**Input:** all upstream artifacts.
**Process (Atlas):** assemble the bootstrap bundle — premise record +
doctrines, series plan, bibles seed, voice profile seed (POV/tense/
register decision), `continuity.md` seed, defect-log seed, originality
receipt (6-gram comparison vs searched comparables), story-form
decision. Run a dry chapter-1 intake against it. Then Sol's scoped
review: "can I run packets from this?" — feasibility only, no creative
input; his findings return as a punch list, not a rewrite.
**Output:** handoff manifest.
**Gate:** EXIT CRITERION — **chapter-1 intake passes Phase 0 without
improvisation.** The existing pipeline is the judge.

## Output contract

A finished factory run produces, at `~/workspace/stories/<slug>/`:
`ideas/`, `STORY.md`, `bibles/`, `series-plan.md`, interview records,
and the handoff manifest — every file status-lined, every the author verdict
mirrored to `~/workspace/standings/rulings-<project>.md`. The run is done
when the Stage 6 gate passes.

## Operating rules

1. The boundary at the top of this file is load-bearing. When in doubt
   about whether Atlas may write something, the answer is no — ask
   the author, mark it OPEN, move on.
2. Gates are falsifiable. A gate that cannot fail is decoration; if a
   check passes vacuously, say so and fix the check.
3. Tier M (mechanical, tool-grounded) checks run ungated. Tier O
   (opinion) passes may target only gaps named by an external critic or
   the author — never self-diagnosed gaps.
4. Every stage's output must be consumed by a named downstream gate.
   Inert documents are cut.
5. Proposed-vs-accepted status discipline on every file, every stage.
6. Deterministic checks before model judgment; positive-control test any
   new mechanical check before trusting it.

## Deferred (not in lean v1)

- Discovery branch (outline-as-you-go for ideas that resist outlining).
- Full (non-lean) expansion: per-stage phase skills, scored loops with
  plateau/decline stopping, multi-branch simulation.

## Changelog

- 2026-10-10: lean v1 built from the Story Factory research + plan.
  the author's creative-authority boundary (development = his; in-progress =
  Sol's); guiding-interview format; Sol's scoped handoff review. Discovery
  branch and full expansion deferred.
## Available connectors

Use `muse.connector_search` to find the current connector docs before following
recovered instructions.
