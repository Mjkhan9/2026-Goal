# 08 — Automations

Code, scripts, prototypes, and demos. Isolated from the strategic/operating side so the repo doesn't turn into a messy codebase.

## Subfolders

- `scripts/` — small, focused utilities (data cleanup, formatting, generators).
- `prototypes/` — early-stage, throwaway builds exploring an idea.
- `demos/` — polished-enough artifacts used for outreach, sales, or proof.
- `experiments/` — technical experiments that may or may not survive.

## Rules

- Each subproject lives in its own folder with its own `README.md` stating: what it does, how to run it, dependencies, status.
- Prefer boringly simple stacks. Pick the smallest tool that solves the problem.
- Never commit secrets. Use `.env.example` for configuration and keep real values local.
- If a prototype graduates into a real product, move it to its own repo — do not let it balloon inside this operating repo.
