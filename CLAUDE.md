# CLAUDE.md — Operating Guide for Claude Code & Claude Projects

Companion to [`AGENTS.md`](./AGENTS.md). Both files are consistent; this one is written in the vocabulary Claude tools tend to use and is intended to be the first file Claude loads.

If `AGENTS.md` and `CLAUDE.md` ever diverge, `AGENTS.md` wins — this file must be updated to match.

---

## What this repo is

A private operating system for an AI-leveraged second-income initiative. It is the **canonical source of truth** for strategy, live operating state, research, offers, outreach, delivery, reusable assets, prompts, and code. Treat it as the long-term memory of the business. Chats are disposable; this repo is not.

## Read these first (in order)

1. `00-compass/north-star.md` — mission, thesis, 12-month intent.
2. `00-compass/operating-principles.md` — non-negotiable rules of engagement.
3. `01-state/current-focus.md` — the one thing being worked on now.
4. `01-state/next-actions.md` — the near-term action queue.
5. `01-state/handoff.md` — resume context if picking up cold.
6. `01-state/context-map.md` — mapping between Claude Project concepts and files in this repo.
7. The `README.md` of the folder you are about to modify.

## How to interpret operating state

- `01-state/` is the **live layer**. If it contradicts a chat thread, the files win.
- `00-compass/` is the **evergreen layer**. If a decision contradicts a principle here, surface it — either the principle needs to be revised via a decision record, or the decision is wrong.
- `01-state/decisions/` is the **decision log**. Past choices live here and must not be silently overwritten; supersede instead.

## Where to place work

| Task | Folder |
|---|---|
| Redefining direction, principles, or roadmap | `00-compass/` |
| Updating what's happening now / next / handoff / decisions | `01-state/` |
| Researching a niche, market, competitor, or signal | `02-research/` |
| Shaping an opportunity or offer | `03-offers/` |
| Prospecting, messaging, proposals | `04-outreach/` |
| SOPs, playbooks, checklists, QA | `05-delivery/` |
| Reusable templates, case studies, proof, brand | `06-assets/` |
| System/task/persona prompts, Claude Project instructions, Cursor rules | `07-prompts/` |
| Scripts, prototypes, demos, experiments | `08-automations/` |
| A specific client engagement | `09-clients/<client-slug>/` |
| Parking inactive material | `99-archive/` |

Do **not** create new top-level folders without explicit instruction.

## Working rules

- Prefer editing existing files over creating new ones.
- Use Markdown, `kebab-case` filenames, dated when relevant.
- When finishing a unit of work, update `01-state/current-focus.md`, `01-state/next-actions.md`, and (if switching tools / ending a thread) `01-state/handoff.md`.
- When a meaningful choice is made, add a record in `01-state/decisions/` using `0000-template.md`.
- Never fabricate business facts, case studies, clients, metrics, or testimonials.
- Never commit secrets, API keys, or client-identifying data.

## Tone

Operator-grade. Direct, specific, testable. No hype. Concrete over abstract. Cite sources in research.

## Pointer summary

- Full behavioral contract: [`AGENTS.md`](./AGENTS.md)
- Repo↔Claude Project vocabulary: [`01-state/context-map.md`](./01-state/context-map.md)
- Top-level map: [`README.md`](./README.md)
