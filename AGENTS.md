# AGENTS.md — Operating Instructions for AI Tools

This file tells any AI system (Claude, ChatGPT, Cursor, Claude Code, etc.) how to behave when working inside this repository.

## What this repo is

A private operating system for an AI-leveraged second-income initiative. It is **part strategy doc, part execution tracker, part asset library, part codebase.** Treat it as the canonical memory of the business.

## Default behavior

1. **Orient before acting.** On any non-trivial task, read in this order:
   - `00-compass/north-star.md`
   - `00-compass/operating-principles.md`
   - `01-state/current-focus.md`
   - `01-state/next-actions.md`
   - The README of the folder you are about to modify.
2. **Place work correctly.** Every artifact has an obvious home (see root `README.md` and per-folder READMEs). Do not create new top-level folders without explicit instruction.
3. **Prefer editing over creating.** If a file already exists for a topic, extend it. Avoid duplicate or near-duplicate files.
4. **Write for both humans and future AI.** Use Markdown. Use clear headings. Prefer short, specific filenames in `kebab-case`.
5. **Record decisions.** When a meaningful choice is made (offer direction, niche pick, tooling, pricing, positioning), add a decision record under `01-state/decisions/` using `0000-template.md`.
6. **Keep state fresh.** When you finish a unit of work, update `01-state/current-focus.md`, `01-state/next-actions.md`, and when relevant `01-state/handoff.md` so the next session (human or AI) can resume instantly.

## What not to do

- Do not invent business facts, case studies, clients, metrics, or testimonials.
- Do not fill placeholder files with fabricated content.
- Do not reorganize the top-level structure unilaterally.
- Do not commit secrets, API keys, or client-identifying data.
- Do not treat this as a generic software repo — strategy and operating context come first.

## Domain cheatsheet

| If the task is about… | Work in |
|---|---|
| Why we exist, principles, long-horizon direction | `00-compass/` |
| What is happening right now, next steps, decisions, handoff | `01-state/` |
| Understanding a niche, market, competitor, or signal | `02-research/` |
| Shaping an opportunity or offer | `03-offers/` |
| Finding, messaging, or closing prospects | `04-outreach/` |
| How work is actually executed (SOPs, playbooks, QA) | `05-delivery/` |
| Reusable templates, case studies, proof, brand | `06-assets/` |
| Prompts, personas, AI instruction sets | `07-prompts/` |
| Scripts, prototypes, demos, experiments | `08-automations/` |
| A specific client engagement | `09-clients/<client>/` |
| Parking something no longer active | `99-archive/` |

## Tone & style for generated content

- Operator-grade. Direct, specific, testable.
- No hype, no generic "AI side hustle" language.
- Prefer concrete examples to abstract claims.
- Cite sources when doing research.
