---
name: consulting-strategy-development
description: >
  Internal consulting sub-skill for strategy project management and
  recommendation development coaching (B3 modules). Activated by
  consulting-playbook dispatcher when B3 signals detected - project risks,
  recommendation quality, go-to-market, pricing, team issues.
  Do not invoke directly; use consulting-playbook as entry point.
---

# Context Intake From Dispatcher
Receive and restate:
- Situation
- Stage
- Time pressure
- Matched module (`B3 A` or `B3 B`)
- Confidence and routing reason

Before starting any coaching steps, update `blueprint/Blueprint-YYYY-MM-DD.md`:
- Fill `**Module:**` with the matched B3 module name.
- Fill `**Archetype:**` with the pattern from the routing table (omit under tight deadline).
- Fill `**Routing reason:**` with one sentence explaining why this module was selected.
- Fill `**Signal confidence:**` with High / Medium / Low.
- Fill `**Time pressure:**` with the user's stated constraint.
- Fill `## 1. Situation Summary` with a paraphrase confirmed back to the user before proceeding.

# SOP Reference Files
Before coaching, load the relevant reference file:
- **B3 A** (project management, activity planning): read `references/b3a-project-management.md`
- **B3 B** (recommendations, GTM, pricing): read `references/b3b-recommendations.md`

These files contain exact SOP techniques (3-metric lead-time prioritization, 8-step task de-black-box, skill-will matrix, 5-upgrade recommendation checklist, move-the-needle math with cannibalization, STP→4Ps sequence, 4-part robust recommendations framework). All coaching content must come from these files, not generic LLM consulting knowledge.

# B3 A: Managing Strategy Projects
## Core method
- Prioritize by lead time and dependency risk, not deadline alone.
- De-black-box vague tasks into executable sub-steps with owners.
- Use IT/data request discipline with early sample-pull hedge.
- Build and pressure-test activity plan: granularity, critical path, staffing, milestone realism.
- Manage communication and buy-in as a parallel workstream.
- Run strong client launch discipline to reduce skepticism and friction.
- Handle tornado moments through scope-time-resource option framing.
- Manage team performance with skill-will diagnosis and de-risked delegation.

## B3 A coaching checklist
1. Identify long-lead, low-control dependencies.
2. Decompose hidden sub-tasks and bottlenecks.
3. Lock calendars and data request samples early.
4. Build one-page activity plan with milestones/owners.
5. Pressure-test critical path and staffing fit.
6. Map buy-in stakeholders and pre-wire risk points.
7. Define tornado response options.
8. Set delegation checkpoints and buffer deadlines.

# B3 B: Developing High-Impact Recommendations
## Core method
- Build GTM logic in sequence: STP before 4Ps.
- Choose segments using appeal, size/growth, targetability, adoption timing.
- Design product strategy by feasible x appealing fit and adoption sequence.
- Treat timing debates as option problems when downside asymmetry is high.
- Use recommendation critique checklist: specificity, impact math, risk/mitigation, implementation realism.
- Quantify move-the-needle impact and include cannibalization.
- Synthesize competitors with 80/20 value proposition logic.
- Fuse quant + qual to uncover hidden drivers.
- Ensure brand-consistent strategic choice.
- Design pricing tiers with explicit cost-to-serve analysis.
- Capture bonus insights as appendix-level opportunities.
- Use interim recommendation pack when decisions are needed with partial information.

## B3 B coaching checklist
1. Define decision and segment priority.
2. Build STP then 4Ps logic chain.
3. Quantify net impact with explicit assumptions.
4. Evaluate risks and mitigation plan.
5. Specify implementation path, owners, and milestones.
6. Check brand alignment and organizational fit.
7. Surface missing analyses that could change recommendation.

# Pattern-Adaptive Delivery
Match delivery style to routed archetype.

## Diagnostic Tree mode
- Use branching logic for trade-offs, risk forks, and failure modes.

## Linear Process mode
- Use sequential flow from diagnosis to implementation roadmap.

## Heuristic mode
- Use concise decision rules for speed, skepticism control, and executive communication.

# Adaptive Depth by Time Pressure
- `tight deadline`: give full action checklist immediately, with minimal viable quantification and risk controls.
- `moderate timeline`: stepwise coaching with milestone checks.
- `exploratory`: deep coaching with alternatives, options framing, and rationale.

# Pattern Trigger
If user says `explain pattern` or `why this approach?`, state:
- Active archetype
- Why it fits current strategic signal
- Why alternatives are secondary now

# Report Mode: Strategy/Recommendation Deck Blueprint
Use when dispatcher flags deliverable-building behavior.

## Stage 0: SCQA skeleton
Create strategy deck skeleton with:
- Situation
- Complication
- Question
- Answer
- Strategic options
- Recommendation
- Risk mitigation
- Implementation roadmap
- Financial impact

## Stage 1: Section blueprint
For requested section, provide:
- Argument structure
- Required evidence and calculations
- Skeptic questions to pre-answer

## Stage 2: Skeptic-proof quality gate
Pass only if:
- Recommendation is specific and quantified
- Alternatives were considered
- Risks and mitigations are explicit
- Implementation is realistic
- Brand/organizational fit is clear

# Consulting Blueprint Section Mapping (B3)
Always keep all 8 sections.

- `1. Situation Summary`: strategic objective, timeline, constraints, stakeholder dynamics.
- `2. Framework / Approach Selected`: B3 A or B3 B plus pattern.
- `3. Decision Logic`: rationale, assumptions, confidence level, option logic.
- `4. Step-by-Step Playbook`: project-control or recommendation-build sequence.
- `5. Evidence Required`: dependency checks, market evidence, impact assumptions, cost inputs.
- `6. Quality Gates`: critical path integrity, skeptic-proof test, risk controls, implementation viability.
- `7. Missing Gaps`: unresolved data, untested assumptions, dependency uncertainty.
- `8. Next Action`: immediate owner/action/checkpoint to maintain momentum.