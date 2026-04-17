# 2026-Goal

Private operating repository for a serious, AI-leveraged second-income initiative.

This repo is the **canonical source of truth** for strategy, state, research, offers, outreach, delivery, reusable assets, prompts, and any code or automations produced along the way. It is designed to be used equally by a human operator and by AI tools (Claude, ChatGPT, Cursor, Claude Code, and similar).

---

## Operating model (short version)

- Sell business **outcomes**, not abstract AI.
- Use AI as **leverage** across research, drafting, coding, QA, and docs.
- Prefer **fixed-scope, repeatable, high-ROI** offers.
- Progression: **service → system → recurring → product**, only after real-world proof.
- Everything important lives in **files**, not chat threads.

See `00-compass/` for the full thesis and principles.

---

## Repo map

| Folder | Purpose | Change rate |
|---|---|---|
| `00-compass/` | North-star, principles, roadmap, glossary | Rarely |
| `01-state/` | Current focus, next actions, decisions, handoff context | Constantly |
| `02-research/` | Niches, markets, competitors, signals | Often |
| `03-offers/` | Opportunities, offer drafts, active offers | Often |
| `04-outreach/` | Targets, messages, proposals, pipeline | Often |
| `05-delivery/` | SOPs, playbooks, checklists, QA | As systems mature |
| `06-assets/` | Templates, case studies, proof, brand | Accumulates |
| `07-prompts/` | System, task, and persona prompts | Accumulates |
| `08-automations/` | Scripts, prototypes, demos, experiments | As needed |
| `09-clients/` | Per-client engagements (future) | Per engagement |
| `99-archive/` | Parked / historical material | Rarely |

Root files:

- `README.md` — this file.
- `AGENTS.md` — behavioral contract for any AI tool working in this repo (source of truth).
- `CLAUDE.md` — Claude-native onboarding guide; stays consistent with `AGENTS.md`.
- `.gitignore`, `.editorconfig` — repo hygiene.

Key operating pointers:

- Repo ↔ Claude Project vocabulary: `01-state/context-map.md`
- Where to start a session: `01-state/current-focus.md` → `01-state/next-actions.md` → `01-state/handoff.md`

---

## How to use this repo

**Starting a new session (human or AI):**
1. Read `00-compass/north-star.md` for intent.
2. Read `01-state/current-focus.md` and `01-state/next-actions.md` for present state.
3. If resuming after a gap, read `01-state/handoff.md`.
4. Work in the folder that matches the task.
5. When a meaningful choice is made, record it in `01-state/decisions/`.

**Adding content:**
- Prefer Markdown.
- Keep filenames lowercase, hyphen-separated, descriptive.
- Short, explicit, dated where relevant (e.g. `2026-04-weekly-review.md`).
- Do not dump into the repo root — pick the correct domain folder.

**Separating evergreen from volatile:**
- Anything that defines **who / why / how at a high level** → `00-compass/`.
- Anything that changes **week to week** → `01-state/`.
- Everything else → its functional domain.

---

## Status

Scaffold initialized. Content is intentionally minimal until real work fills it.
