# How We Use Company Brain

This repo is our single source of truth for how we think and what we decided. Every agent working across our other repos can read it to understand our context.

## Why a Git repo instead of Notion

Coding agents can read, search, and update Markdown files in seconds. You get full history for free, no lock-in, and every rule lives in `AGENTS.md` right next to the files.

## Our day-to-day workflow

### 1. Principles outrank impulses
We keep a short list of operating principles in `principles/`. Whenever we plan something big or debate a move, we ask our agent to check the plan against `principles/`. If a plan breaks a principle, the agent flags it.

### 2. Decisions stop the ping-pong
We used to change our minds every week and forget why we chose the first path. Now every major decision gets a short numbered file in `decisions/`:
- What we decided
- The top 2 to 4 reasons why
- Who decided and the date

We never edit old decisions. If we change direction later, we add a new numbered file that supersedes the old one and explains what changed.

### 3. Gate every new project
Before starting a new big project, we force ourselves to answer `next-project/checklist.md` and list our assumptions in `next-project/assumptions.md`. Most bad ideas die right here before costing months of work.

### 4. Save voice notes and internal calls
We drop transcripts of important internal calls and voice notes into `transcripts/`. After each batch of calls, an agent extracts the top takeaways into that folder's `learnings.md`.

Important privacy rule: only sync meetings where every participant is on your internal allowlist. Keep external calls out of the shared transcript sync unless everyone agreed.

### 5. Grow `AGENTS.md` from real mistakes
Every time an agent makes a mistake (wrong tone, wrong fact, skipping a step in a skill), we add a one-line dated rule to `AGENTS.md`. Over a few weeks the repo stops repeating mistakes.
