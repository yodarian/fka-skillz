# Agents

This document describes the agents and specialized workflows available in this repository.

## Agent skills

### Issue tracker

Issues and specs live as markdown files in `.scratch/`. See `docs/agents/issue-tracker.md`.

### Triage labels

Default triage label vocabulary (canonical roles). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context repo with domain overview in `CONTEXT.md` and architectural decisions in `docs/adr/`. See `docs/agents/domain.md`.

## Available Agents

- **Explore** — Fast read-only codebase exploration and Q&A. Use for discovering patterns, finding code, and answering questions about the codebase.

## Skills by Category

### Discovery & Planning
- `domain-modeling` — Build and sharpen the project's domain model.
- `research` — Investigate a topic and capture findings as markdown.
- `triage` — Categorize and prioritize work items.
- `wayfinder` — Plan complex multi-ticket efforts.

### Development
- `tdd` — Test-driven development (red-green-refactor).
- `implement` — Guided implementation with spec.
- `prototype` — Build throwaway prototypes to test ideas.

### Code Quality
- `code-review` — Review changes against standards and spec.
- `diagnosing-bugs` — Systematic bug diagnosis and fixing.
- `improve-codebase-architecture` — Refactor and improve module design.

### Conversational
- `grilling` — Challenge assumptions and stress-test thinking.
- `grill-with-docs` — Grilling with domain context.
- `to-spec` — Break down specs into implementation tickets.
- `to-tickets` — Convert issues or ideas into structured tickets.

### Support & Guidance
- `ask-matt` — Ask Matt Pocock a question (reference).
- `handoff` — Prepare work for human handoff.
- `teach` — Learn a topic or skill.
- `writing-great-skills` — Guidelines for creating new skills.

---

For more details on each skill or agent, see the corresponding `.agents/skills/<name>/` or `.agents/<name>/` directory.
