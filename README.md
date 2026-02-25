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
Each folder is protocol-ready with a `SKILL.md` entry file.

## Public Installation (GitHub)
Install from GitHub with the Skills CLI:

```bash
npx skills add Dzw310/consulting-playbook-skill@consulting-playbook
```

All-in-one install (PowerShell):

```powershell
@(
  "consulting-playbook",
  "consulting-problem-structuring",
  "consulting-data-insights",
  "consulting-strategy-development"
) | ForEach-Object { npx skills add "Dzw310/consulting-playbook-skill@$_" }
```

If your installer/source expects explicit adds for all folders:

```bash
npx skills add Dzw310/consulting-playbook-skill@consulting-playbook
npx skills add Dzw310/consulting-playbook-skill@consulting-problem-structuring
npx skills add Dzw310/consulting-playbook-skill@consulting-data-insights
npx skills add Dzw310/consulting-playbook-skill@consulting-strategy-development
```

## Invocation
Use only `consulting-playbook` as the entry point. The dispatcher invokes sub-skills internally based on routed signals and confidence logic.

## Public Usage Rules
- Entry point: `$consulting-playbook`
- Internal only: `$consulting-problem-structuring`, `$consulting-data-insights`, `$consulting-strategy-development`
- Sub-skills are dispatcher-invoked and not intended as direct user entry points.

## Quick Start
Example first prompt:

```text
Use $consulting-playbook. I am currently facing: a client anchored on pricing as the only fix.
```

## Consulting Blueprint
A Consulting Blueprint is the single working artifact created and updated during coaching.
Find it in `blueprint/Blueprint-YYYY-MM-DD.md`.

Optional: add `blueprint/` to `.gitignore` if you do not want to track working Blueprint files.
