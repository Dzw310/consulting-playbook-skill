# Consulting Playbook

Practical coaching for messy consulting problems.

This skill helps you think clearly, choose the right next steps, and keep your work organized when a project feels unclear or high pressure.

## What You Get
- A guided conversation that asks a few focused questions first
- A clear plan for what to do next
- A single working file that is updated as you progress:
  - `blueprint/Blueprint-YYYY-MM-DD.md`

## Best For
- Client conversations that are stuck on one idea
- Problems that feel broad or hard to structure
- Conflicting data or unclear conclusions
- Recommendation work that needs stronger logic
- Tight timelines where you need to move now

## Install
Copy `consulting-playbook/` into your skills folder:

- Codex: `~/.codex/skills/consulting-playbook/`
- Claude Code: `~/.claude/skills/consulting-playbook/`
- Agents runtime: `~/.agents/skills/consulting-playbook/`

Or install from GitHub:

```bash
npx skills add Dzw310/consulting-playbook-skill@consulting-playbook
```

## Quick Start
Invoke:

```text
$consulting-playbook
```

Example:

```text
Use $consulting-playbook. I am currently facing: a client insists pricing is the only fix.
```

## How To Use It Well
1. Describe your situation in one sentence.
2. Share where you are in the work (early framing, data gathering, analysis, or recommendation).
3. Say how urgent it is.
4. Follow the next step in the generated blueprint.

## Output File
The skill creates and updates:

```text
blueprint/Blueprint-YYYY-MM-DD.md
```

If you do not want to track this working file in git, add `blueprint/` to `.gitignore`.

## License
MIT. See [LICENSE](LICENSE).
