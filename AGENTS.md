# AGENTS.md — Operating Instructions for AI Tools

This file tells any AI system (Claude, ChatGPT, Cursor, Claude Code, etc.) how to behave when working inside this repository. Claude-family tools should also read [`CLAUDE.md`](./CLAUDE.md); if the two ever diverge, **this file wins** and `CLAUDE.md` must be updated to match.

## What this repo is

A private operating system for an AI-leveraged second-income initiative. It is **part strategy doc, part execution tracker, part asset library, part codebase.** Treat it as the canonical memory of the business.

## Default behavior

1. **Orient before acting.** On any non-trivial task, read in this order:
   - `CLAUDE.md` (if you are a Claude-family tool)
   - `00-compass/north-star.md`
   - `00-compass/operating-principles.md`
   - `01-state/current-focus.md`
   - `01-state/next-actions.md`
   - `01-state/context-map.md` (for Claude Project / tool vocabulary)
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

## Operating model for AI tools

This repository is currently in Phase 1 of a research-first,
diagnostic-led local-services practice for Houston-area small
businesses. AI tools working here must operate consistent with that
phase:

- Default to broad diagnostic curiosity. Do NOT pressure the operator
  to pick a single vertical, single deliverable, or single offer before
  diagnostic data justifies it. Narrowing is deferred and data-driven
  (see decision 0002).
- Interventions are drawn from the broad taxonomy in
  `02-research/houston-smb-diagnostics/_intervention-taxonomy.md` and
  selected per business. Do not narrow the taxonomy.
- Label every recommendation as: current best hypothesis, reasoned
  assumption, or validated pattern. Do not blur them.
- Do not moralize legitimate business logic. The ethics-level
  guardrails that apply are the ones listed in "What not to do" —
  no fabricated proof, no fabricated clients or metrics, no dishonest
  claims. Outside those, the operator owns judgment.
- Favor direct analysis, sharp diagnosis, useful structure, and
  practical artifacts over framework / three-options / consultant
  output.

## Tone & style for generated content

- Operator-grade. Direct, specific, testable.
- No hype, no generic "AI side hustle" language.
- Prefer concrete examples to abstract claims.
- Cite sources when doing research.
