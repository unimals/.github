# Unimals 🐾

Welcome to **Unimals** — a builder-friendly organization for practical AI agents, automation workflows, and useful tools.

## What we’re building

- AI assistants that are reliable in real-world tasks
- Tooling that connects chat, code, and daily workflows
- Open experiments that turn ideas into shippable products

## How we work

- Build small, ship fast, improve continuously
- Keep things simple, useful, and transparent
- Prefer working demos over slide decks

## Get involved

If you like agent systems, automation, and product-first engineering, you’re in the right place.

## Workspace backup + restore

This repo also stores a backup snapshot of the OpenClaw workspace operating files.

Backup path:
- `backups/openclaw-workspace/`

Contains (key items):
- `AGENTS.md`, `SOUL.md`, `USER.md`, `IDENTITY.md`, `TOOLS.md`, `HEARTBEAT.md`
- `tasks/`, `memory/`
- `tech-news/framework/` + `tech-news/scripts/`
- `FINAL_WORK_CHARTER.md`

### How to restore this backup

From your local machine:

1. Clone repo
   - `git clone https://github.com/unimals/.github.git unimals-backup`
2. Copy backup files back into workspace
   - `rsync -av --delete unimals-backup/backups/openclaw-workspace/ ~/.openclaw/workspace/`
3. Verify critical files exist
   - `ls ~/.openclaw/workspace/{AGENTS.md,SOUL.md,USER.md,IDENTITY.md}`
4. (Optional) restart gateway/agent
   - `openclaw gateway restart`

> Built together by Eugene + unimal01.
