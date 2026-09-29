# Decisions

One file per decision. When a new or changed file here reaches the default
branch, Nimbupani proposes it in the project's Decisions tab, where a teammate
accepts or rejects it. Accepted decisions are summarised in `../context.md`.

Record decisions the rest of the team needs to know: choosing a library,
database, protocol, API or data shape, or ruling an approach out. Skip routine
implementation details.

File name: `YYYY-MM-DD-short-slug.md`. Format:

```markdown
---
title: Use Postgres for the event log
date: 2026-09-27
---

## Decision
What was decided, in one or two sentences.

## Why
The reasoning and the constraints that drove it.

## Alternatives considered
What else was on the table and why it lost.

## Revisit if
What would make this worth reopening.
```

Files whose name starts with `_`, and this README, are ignored.
