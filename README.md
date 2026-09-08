# JOANA

> Five elite engineers in one mind — planner, backend architect, implementer,
> frontend engineer, and security lead — fused into a single self-contained
> agent skill. **One file. No references. No dependencies.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Format](https://img.shields.io/badge/format-Agent%20Skill-blue)](SKILL.md)
[![Dependencies](https://img.shields.io/badge/dependencies-zero-success)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## The five lenses

| Lens | Discipline | Leads on |
|---|---|---|
| **Jasmine** | Planner & Strategist | vague asks, sequencing, scope control, pre-mortems |
| **Oliver** | Backend & Systems Architect | APIs, data models, failure modes, scaling |
| **Alex** | Implementation & Craft | code, tests, debugging, refactoring |
| **Nathan** | Frontend & Experience | UI, accessibility, performance, component states |
| **Amy** | Security & Trust | threat modeling, auth, secrets — and a ship veto |

## Install

**Claude Code (project):** copy `SKILL.md` to `.claude/skills/joana/SKILL.md`

**Claude Code (personal):**
```bash
git clone https://github.com/SulphArk/J.O.A.N.A.-skill.git ~/.claude/skills/joana
```

**claude.ai:** Settings → Capabilities → Skills → upload the skill.

## Use it

Just talk to the agent — JOANA picks its lead lens from the ask:

| You say | Mode |
|---|---|
| "Plan a multi-tenant SaaS buildout" | PLAN — Jasmine leads |
| "Design the billing API" | ARCHITECT — Oliver leads |
| "Fix the flaky checkout bug" | DEBUG — Alex leads |
| "Build the settings page" | BUILD — Nathan leads |
| "Audit auth before launch" | SECURE — Amy leads |

## What makes it different

- **Shift-left security** — Amy shadow-reviews every lens's output continuously and holds an explicit veto.
- **Panel Protocol** — all five lenses cross-examine work before it ships; disagreements surface, not average.
- **SHIP gate** — one Definition of Done checklist spanning planning through security, so "done" is verifiable.

## Story Time
There is actually a girl I know from my school Joana (idk if that's like the right spelling) but yeah i was lazy and chose her name and i wanted to put Jasmine in the team and i didnt know where to put her so based on her name I made this skill


## License

[MIT](LICENSE)
