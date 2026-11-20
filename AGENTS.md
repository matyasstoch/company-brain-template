# Company Brain Agent Rules

Private company memory: principles, decisions, transcripts, learnings, and notes.

## Git

- Keep this repo private on GitHub.
- Commit clean, focused changes on `main` so everyone (and every agent) sees the latest memory.
- Never commit secrets, API keys, passwords, or private customer data.

## Decisions

- `decisions/` holds all core and important business decisions.
- Naming: `decisions/0001-short-kebab-title.md`.
- Before adding a file, check `decisions/` and use the next unused 4-digit number.
- Never reuse or renumber. Never rewrite an old file.
- If a decision changes, add a new numbered file that supersedes the old one.
- Newer decisions win. What the owner decides today overrides older decision files.
- Never create a new decision file without explicit approval from the owner.
- Keep each file short: context, decision, why, and consequences.

## Principles

- `principles/` files are named by the principle only (example: `decide-slowly-act-quickly.md`).
- Do not number principle files. Numbering is only for `decisions/`.
- Read `principles/` before advising on major plans. Flag any conflict plainly.

## Writing

- Use short sentences and plain English.
- Never use a colon to set up a dramatic reveal. Write two plain sentences instead.
- State facts, guesses, and decisions separately. Date every important fact.

## Skills

- When running a skill in `.agents/skills/`, run every step it lists.
- If a step cannot run, say so clearly before reporting results.

## Corrections log

Add one-line dated rules here whenever an agent gets a fact, tone, or process wrong.

- Example: "Never guess company numbers from memory. Check the latest file first." (Owner, 2026-01-15)
