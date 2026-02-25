---
name: consulting-problem-structuring
description: >
  Internal consulting sub-skill for problem definition, de-anchoring, and
  issue tree coaching (B2 modules). Activated by consulting-playbook dispatcher
  when B2 signals detected - client anchored on solution, unclear objective,
  scope disputes, issue tree needed. Do not invoke directly; use consulting-playbook.
---

# Context Intake From Dispatcher
Receive and restate:
- Situation
- Stage
- Time pressure
- Matched module (`B2 A` or `B2 B`)
- Confidence and routing reason

Before starting any coaching steps, update `blueprint/Blueprint-YYYY-MM-DD.md`:
- Fill `**Module:**` with the matched B2 module name.
- Fill `**Archetype:**` with the pattern from the routing table (omit under tight deadline).
- Fill `**Routing reason:**` with one sentence explaining why this module was selected.
- Fill `**Signal confidence:**` with High / Medium / Low.
- Fill `**Time pressure:**` with the user's stated constraint.
- Fill `## 1. Situation Summary` with a paraphrase confirmed back to the user before proceeding.

# SOP Reference Files
Before coaching, load the relevant reference file:
- **B2 A** (de-anchoring, problem definition): read `references/b2a-de-anchoring.md`
- **B2 B** (issue tree, hypothesis tree, workplan): read `references/b2b-issue-tree.md`

These files contain exact SOP techniques (agree→reframe→expand script, influence toolkit sequence, ghost charting method, move-the-needle math, fast-fail gates). All coaching content must come from these files, not generic LLM consulting knowledge.

# B2 A: Client Alignment, De-Anchor, and Guiding Question
## Core method
- Separate objective from preferred lever.
- Use `agree -> reframe -> expand` to de-anchor without relationship damage.
- Reframe with objective structure before choosing tactics.
- Define success, scope, constraints, precision level, and sign-off path.
- Distill one guiding question at the right specificity.
- Run client alignment check before any deep tree-building.

## B2 A coaching checklist
1. State objective in one sentence.
2. List at least 2-3 alternative drivers.
3. Clarify constraints, deliverable shape, and decision owner.
4. Draft guiding question as a decision question.
5. Confirm alignment with stakeholder language.
6. Propose a short diagnostic scan and decision checkpoint.

# B2 B: Issue Tree, Hypothesis Tree, and Feasibility
## Core method
- Build a MECE issue tree first for legitimacy and coverage.
- Prune branches using move-the-needle math and benchmark gaps.
- Use hypothesis trees when speed is needed and priors are credible.
- Convert big gaps to dollars before prioritizing.
- Apply fast-fail feasibility gates (regulatory, IT, capability, timeline, cost).
- Convert surviving leaves into leaf-level workplan and ghost-charted outputs.

## B2 B coaching checklist
1. Build first-level MECE branches.
2. Score branch upside (order-of-magnitude).
3. Prune low-impact branches.
4. Build "what must be true" conditions for top hypotheses.
5. Check feasibility kill criteria early.
6. Define leaf workplan: analysis, end-product, data, timeline, owner.

# Pattern-Adaptive Delivery
Match delivery style to the routed archetype.

## Diagnostic Tree mode
- Lead with branching questions.
- Use if/then forks to expose root cause, blockers, and choice points.
- Stop when one branch clearly dominates.

## Linear Process mode
- Give a strict step order and required outputs per step.
- Use for execution clarity, handoffs, and pacing.

## Heuristic mode
- Give compact rules-of-thumb and trigger phrases.
- Use for high-friction conversations and fast judgment under ambiguity.

# Adaptive Depth by Time Pressure
- `tight deadline`: provide full checklist upfront, fastest path, and immediate next action.
- `moderate timeline`: guide step-by-step with checkpoint after each major step.
- `exploratory`: coach deeply, explain pattern choice, and compare alternatives.

# Pattern Trigger
If user says `explain pattern` or `why this approach?`, state:
- Active archetype
- Why it fits the current signal
- Why alternatives are second-best now

# Report Mode: Problem Framing Document Blueprint
Use when dispatcher flags deliverable-building behavior.

## Stage 0: Skeleton
Create section skeleton for a problem framing document:
- Objective and decision question
- Scope and constraints
- Working hypotheses
- Issue tree snapshot
- Prioritization logic
- Required analyses and owners
- Risks and mitigations
- Decision checkpoints

## Stage 1: Section blueprint
For requested section, provide:
- Required argument logic
- Evidence required
- Quality bar and failure modes

## Stage 2: Quality gate
Pass only if:
- Objective is explicit and testable
- Scope is defensible
- Tree is MECE
- Prioritization is impact-led
- Feasibility blockers are addressed

# Consulting Blueprint Section Mapping (B2)
Always keep all 8 sections.

- `1. Situation Summary`: objective, context, anchor risk, constraints.
- `2. Framework / Approach Selected`: B2 A or B2 B plus pattern.
- `3. Decision Logic`: why this module, confidence, key assumptions.
- `4. Step-by-Step Playbook`: de-anchor sequence or tree-build/prune workflow.
- `5. Evidence Required`: benchmark inputs, definitions, feasibility checks, missing data.
- `6. Quality Gates`: objective clarity, MECE test, move-the-needle threshold, kill criteria.
- `7. Missing Gaps`: unresolved assumptions, unconfirmed constraints, blocked stakeholders.
- `8. Next Action`: immediate next meeting/question/analysis with owner and timing.