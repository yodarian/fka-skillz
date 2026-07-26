# FKA Skillz — Domain Context

**FKA Skillz** is a collection of reusable engineering skills, agents, and prompts for AI-assisted development workflows (GitHub Copilot and beyond).

## Core Concepts

- **Skill**: A focused, reusable problem-solving workflow (e.g., `tdd`, `diagnosing-bugs`, `code-review`). Skills encode domain knowledge and best practices.
- **Agent**: A specialized AI agent with a specific expertise area or workflow (e.g., the Explore agent for codebase navigation).
- **Prompt**: System and user-facing prompts that customize AI behavior for specific contexts.
- **Test environment**: The Laravel project under `laravel/` serves as a living test bed for validating skills in real projects.

## Repository Structure

```
fka-skillz/
├── .agents/                      # AI agents
│   └── skills/                   # Collection of skills (.agents/skills/)
├── .github/                      # GitHub-specific configuration
│   ├── copilot-instructions.md   # Central Copilot config
├── docs/                         # Documentation
│   ├── adr/                      # Architectural decisions
│   └── agents/                   # Agent/skill configuration (triage, domain, issue tracker)
├── laravel/                      # Test Laravel project for skill validation
└── README.md
```

## Key Terms

- **Matt Pocock skills**: A reference implementation of engineering workflows (TDD, code review, debugging) designed for AI agents. This repo collects and adapts them.
- **Issue tracker**: Where work items are tracked. This repo uses **local markdown** (`.scratch/` directory) for issues and specs.
- **Triage**: The process of categorizing and prioritizing work using canonical role labels (`needs-triage`, `ready-for-agent`, etc.).
- **ADR** (Architectural Decision Record): A document capturing a significant architectural choice and its rationale (stored in `docs/adr/`).
- **CONTEXT.md** (this file): The glossary and domain overview for this repo.

## Current Maturity

FKA Skillz is actively developed. Skills and agents are continuously refined and validated in the Laravel test environment before being considered stable.
