# AGENTS

This repository contains a minimal scaffold for an agentic CommitCoach system.

## Current agent modules

The `agents/` package currently includes placeholders:

- `agents/planner.py`
- `agents/reflection.py`
- `agents/accountability.py`

At the moment, these files are scaffolds and do not contain concrete implementations.

## Entry point

- Main entry point: `app.py`
- Run locally:

```bash
python app.py
```

## Suggested agent responsibilities

- **Planner**: break down goals into actionable steps.
- **Reflection**: review outcomes and suggest improvements.
- **Accountability**: track commitments and completion status.

## Extending agents

When implementing an agent module, keep each agent focused on one responsibility and provide a clear callable interface so agents can be orchestrated from `app.py`.
