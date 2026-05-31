# GitHub-Projects-V2

A [Copilot skill](https://code.visualstudio.com/docs/copilot/chat/chat-customization) for managing GitHub Projects v2 boards using the `gh project` CLI. Designed for use with AI agents and automation workflows that need to interact with GitHub Projects from the command line.

## What it does

This skill teaches an AI agent how to:

- **List backlog items** — query project items with filters (status, assignee, open/closed)
- **Set project fields** — update status, iteration, priority, story points, dates, etc.
- **Add comments to issues** — post comments on issues from the project board
- **Create issues** — create new issues and add them to a project
- **Create sub-issues** — link child issues to a parent using the `gh-sub-issue` extension or GraphQL

## Requirements

- [`gh` CLI](https://cli.github.com/) installed and authenticated
- `project` scope on the token — run `gh auth refresh -s project` if commands fail with auth errors

## Files

| File | Purpose |
|------|---------|
| [SKILL.md](SKILL.md) | Full skill instructions with command examples and patterns |
| [skill-card.md](skill-card.md) | Short metadata card (description, use case, requirements, output format) |

## Usage

Add this repository as a skill reference in your agent configuration. The agent will use the instructions in `SKILL.md` whenever it needs to manage GitHub Projects v2 boards, items, or fields.
