# 0001 - Use Numbered Business Decisions

- Decided by: Jane Founder
- Date: 2026-01-15

## Context

We kept revisiting the same choices every week and forgetting why we picked our current direction.

## Decision

Every major business decision gets a numbered Markdown file in `decisions/`. Each file lists:
- The decision in plain words
- The top 2 to 4 reasons why
- Who decided and the date

Old decision files are never edited or renumbered. To reverse a decision, add a new file that supersedes the old one.

## Why

1. Stops repeating the same debates.
2. Gives AI agents and new teammates the real reason behind our current rules.
3. Makes it obvious when an old assumption broke.

## Consequences

- Agents check `decisions/` before recommending strategy changes.
- Code and technical architecture decisions still live in each software repo under `docs/adr/`.
