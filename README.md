# thrillmot/agent-skills

A collection of [skills.sh](https://www.skills.sh)-compatible agent skills published by [thrillmot](https://thrillmot.com).

These skills run inside any agent that loads skills.sh — Claude Code, Cursor, Codex, Cline, Continue, Aider, Windsurf, and others. Each skill is a single `SKILL.md` file with YAML frontmatter declaring when and how the agent should load it.

## Skills in this collection

| Skill | Purpose |
|---|---|
| [`logmind`](skills/logmind/SKILL.md) | Teach agents when and how to log architectural decisions in projects using [logmind](https://logmind.dev). Activates whenever an agent works in a project with `.logmind/config.yml` or an `AGENTS.md`/`CLAUDE.md` mentioning logmind. |

## Install

Pick a single skill:

```bash
npx skills add https://github.com/thrillmot/agent-skills --skill logmind
```

Or install the whole collection:

```bash
npx skills add https://github.com/thrillmot/agent-skills
```

Browse on skills.sh: <https://www.skills.sh/thrillmot/agent-skills>

## Adding a new skill to this collection

1. Create `skills/<name>/SKILL.md` with frontmatter (`name`, `description`).
2. Add a row to the table above.
3. Open a PR.

## License

MIT.
