# Consulting Playbook Skills

Consulting playbook skills route ambiguous client situations into structured modules, coach rigorous thinking, and maintain a living Consulting Blueprint so teams make faster, defensible decisions under real project pressure daily.

## Skill Library
- `consulting-playbook`: Dispatcher and only user-facing entry point; runs intake, confidence routing, and blueprint initialization.
- `consulting-problem-structuring`: Internal B2 coaching for de-anchoring, guiding-question clarity, and issue/hypothesis trees.
- `consulting-data-insights`: Internal B1 coaching for stakeholder interviews, data credibility checks, and synthesis.
- `consulting-strategy-development`: Internal B3 coaching for project control and high-impact recommendation development.

## Installation
Copy these folders into `~/.claude/skills/`:
- `consulting-playbook/`
- `consulting-problem-structuring/`
- `consulting-data-insights/`
- `consulting-strategy-development/`

## Invocation
Use only `consulting-playbook` as the entry point. The dispatcher invokes sub-skills internally based on routed signals and confidence logic.

## Consulting Blueprint
A Consulting Blueprint is the single working artifact created and updated during coaching.
Find it in `blueprint/Blueprint-YYYY-MM-DD.md`.

Optional: add `blueprint/` to `.gitignore` if you do not want to track working Blueprint files.