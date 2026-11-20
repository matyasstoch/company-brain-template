# Company Brain

Private memory for your company or personal work. Principles, decisions, meeting transcripts, learnings, and external notes live here as plain Markdown files.

## Quick setup prompt

Paste this into your coding agent (Claude Code, Codex, Cursor, or Cloudroom) inside this folder:

```text
Read README.md, HOW-WE-USE-IT.md, and AGENTS.md in this repo. Ask me 5 short questions about my business or work (who I am, my current main project, my team if any, my 3 biggest operating principles, and what kind of calls I record). Then replace all example content in this repo with my real setup and remove placeholder notes.
```

## Map

- [principles/](principles/) - How you operate. One unnumbered file per principle.
- [decisions/](decisions/) - Core business decisions, numbered `0001-short-kebab-title.md`. Never rewrite or renumber. Supersede with a new file.
- [next-project/](next-project/) - The [checklist](next-project/checklist.md) and [assumptions](next-project/assumptions.md) you fill out before committing to a new big project.
- [transcripts/](transcripts/) - Internal call transcripts grouped by topic, each folder with a `learnings.md` file, plus `voice-notes/`.
- [notes/](notes/) - Notes from outside sources (podcasts, talks, articles, experts you follow).
- [.agents/skills/](.agents/skills/) - Reusable workflows your agents follow.
- [HOW-WE-USE-IT.md](HOW-WE-USE-IT.md) - How we actually run this repo day to day.

## Rules

Read [AGENTS.md](AGENTS.md) before editing anything here.
