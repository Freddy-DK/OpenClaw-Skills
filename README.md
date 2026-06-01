# OpenClaw Skills

A collection of OpenClaw skills for use with AI agents and automation workflows. Each subfolder contains a self-contained skill with its own `SKILL.md` and supporting files.

## Skills

| Skill | Description |
|-------|-------------|
| [GitHub-Projects-V2](GitHub-Projects-V2/) | Manage GitHub Projects v2 boards using the `gh project` CLI — list backlog items, set fields, create issues, and more. |

## Usage

Add this repository (or an individual skill folder) as a skill reference in your agent configuration. The agent will use the instructions in the skill's `SKILL.md` whenever a matching task is detected.

## Repository structure

```
<skill-folder>/
  SKILL.md          # Full skill instructions (required)
  skill-card.md     # Short metadata card (optional)
  CHANGELOG.md      # Version history (optional)
```

## Contributing

To add a new skill, create a folder at the repo root containing at minimum a `SKILL.md` with frontmatter (`name`, `description`) and the skill instructions.
