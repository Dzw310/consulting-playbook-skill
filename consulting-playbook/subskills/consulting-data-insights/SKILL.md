---
name: consulting-data-insights
description: >
  Internal consulting sub-skill for data collection, expert interviews, and
  analysis coaching (B1 modules). Activated by consulting-playbook dispatcher
  when B1 signals detected - dodging stakeholders, conflicting data sources,
  synthesis gaps. Do not invoke directly; use consulting-playbook as entry point.
---

# Context Intake From Dispatcher
Receive and restate:
- Situation
- Stage
- Time pressure
- Matched module (`B1 S1` or `B1 S2`)
- Confidence and routing reason

Before starting any coaching steps, update `blueprint/Blueprint-YYYY-MM-DD.md`:
- Fill `**Module:**` with the matched B1 module name.
- Fill `**Archetype:**` with the pattern from the routing table (omit under tight deadline).
- Fill `**Routing reason:**` with one sentence explaining why this module was selected.
- Fill `**Signal confidence:**` with High / Medium / Low.
- Fill `**Time pressure:**` with the user's stated constraint.
- Fill `## 1. Situation Summary` with a paraphrase confirmed back to the user before proceeding.

# SOP Reference Files
Before coaching, load the relevant reference file:
- **B1 S1** (interviews, stakeholder targeting): read `references/b1s1-interviews.md`
- **B1 S2** (data analysis, robustness): read `references/b1s2-data-analysis.md`

These files contain exact SOP techniques (5-filter stakeholder targeting, resistance handling, ghost charting template method, 80/20 assumption audit, definition drill, market research critique formula). All coaching content must come from these files, not generic LLM consulting knowledge.

# B1 S1: Data Collection, Interviews, and Expert Engagement
## Core method
- Start with stakeholder targeting by org map, not functional guesswork.
- Select interviewees by information ownership, bias counterweight, level altitude, buy-in value, and execution credibility.
- Under resistance, pivot from extraction to trust + access path.
- Use open questions first, then clarifying and probing questions.
- Handle talkative experts with precision prompts, paraphrase loops, and ghost-chart templates.
- Structure sessions as intro -> core -> close -> same-day documentation.

## B1 S1 coaching checklist
1. Build stakeholder map and targeting rationale.
2. Define interview objective and success signal.
3. Prepare resistance handling script.
4. Use clarifying/probing sequence to force useful numbers.
5. Co-create ghost chart when output ambiguity appears.
6. Confirm next steps and document immediately.

# B1 S2: Analyze Data to Draw Robust Conclusions
## Core method
- Validate external numbers: source, incentives, assumptions, recency, scope.
- Run definition drill before any comparison.
- Critique market research design: sample frame, comparability, attribute coverage, importance weighting.
- Apply 80/20: test high-impact assumptions first.
- Triangulate top-down and bottom-up where possible.
- Synthesize many datapoints into 2-3 executable conclusions with clear implications.

## B1 S2 coaching checklist
1. List critical assumptions and rank by impact.
2. Validate high-risk third-party numbers.
3. Align metric definitions across sources.
4. Audit sample quality and attribute relevance.
5. Convert key gaps into dollar impact.
6. Produce concise synthesis with next decision implications.

# Pattern-Adaptive Delivery
Match delivery style to routed archetype.

## Diagnostic Tree mode
- Use branching tests for data credibility and root-cause uncertainty.
- Prioritize disconfirming checks first.

## Linear Process mode
- Give ordered workflow from data intake to synthesis output.
- Define artifact at each step.

## Heuristic mode
- Use practical rules for interview dynamics, evidence quality, and skepticism control.

# Adaptive Depth by Time Pressure
- `tight deadline`: give full checklist immediately and run minimum viable validation.
- `moderate timeline`: execute one step at a time with frequent quality checks.
- `exploratory`: teach full rationale, alternatives, and anti-patterns.

# Pattern Trigger
If user says `explain pattern` or `why this approach?`, state:
- Active archetype
- Why it best fits the current data/interview signal
- Why alternative patterns are less efficient now

# Report Mode: Data/Analysis Report Blueprint
Use when dispatcher flags deliverable-building behavior.

## Stage 0: Skeleton
Create section skeleton:
- Objective and key questions
- Data sources and definitions
- Methodology and validation checks
- Findings and synthesis
- Risks, limitations, and confidence
- Decision implications and next tests

## Stage 1: Section blueprint
For requested section, provide:
- Required argument chain
- Evidence checklist
- Common logic failures to avoid

## Stage 2: Quality gate
Pass only if:
- Definitions are explicit and consistent
- Source credibility is defensible
- Findings are prioritized by impact
- Conclusion is actionable and not a data dump

# Consulting Blueprint Section Mapping (B1)
Always keep all 8 sections.

- `1. Situation Summary`: core data/interview challenge, stakeholders, decision context.
- `2. Framework / Approach Selected`: B1 S1 or B1 S2 plus pattern.
- `3. Decision Logic`: why this analysis path, confidence, key assumptions.
- `4. Step-by-Step Playbook`: interview/data-validation/synthesis sequence.
- `5. Evidence Required`: source checks, definitions, sample validity, triangulation needs.
- `6. Quality Gates`: credibility tests, consistency checks, synthesis standards.
- `7. Missing Gaps`: unresolved data, blocked access, uncertain assumptions.
- `8. Next Action`: next interview, data pull, validation test, or synthesis draft.