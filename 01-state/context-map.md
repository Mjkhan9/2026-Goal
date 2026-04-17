# Context Map — Repo ↔ Claude Project

Short, explicit mapping between Claude Project concepts and files in this repo. Purpose: eliminate translation friction when uploading files into Claude Projects or referencing them in a Claude Code / Cursor session.

When a Claude Project is set up for this initiative, its **knowledge files** and **custom instructions** should mirror the files below. Whenever these files change here, update the mirror.

## Concept → File map

| Claude Project concept | Repo file |
|---|---|
| Project / custom instructions | `07-prompts/claude-project/instructions.md` (authored here, pasted into Claude Project) |
| Master brief / north star | `00-compass/north-star.md` |
| Operating principles | `00-compass/operating-principles.md` |
| Roadmap / phased plan | `00-compass/roadmap.md` |
| Glossary | `00-compass/glossary.md` |
| Current state / current focus | `01-state/current-focus.md` |
| Next actions | `01-state/next-actions.md` |
| Handoff / resume context | `01-state/handoff.md` |
| Weekly review log | `01-state/weekly-review.md` |
| Decision log | `01-state/decisions/` (plus `0000-template.md`) |
| Behavioral contract for AI tools | `AGENTS.md` + `CLAUDE.md` |

## What to upload to a Claude Project (minimum viable context set)

1. `CLAUDE.md`
2. `AGENTS.md`
3. `00-compass/north-star.md`
4. `00-compass/operating-principles.md`
5. `00-compass/roadmap.md`
6. `01-state/current-focus.md`
7. `01-state/next-actions.md`
8. `01-state/handoff.md`
9. `01-state/context-map.md` (this file)

Add domain folders (`02-research`, `03-offers`, etc.) only when the current task touches them — avoid flooding the Claude Project with inactive context.

## What to paste into the Claude Project's Custom Instructions field

The file at `07-prompts/claude-project/instructions.md` is the source of truth for that field. Edit it in the repo, then copy-paste into Claude. Never edit only in Claude without reflecting the change here.

## Cursor

Cursor reads `AGENTS.md` and `CLAUDE.md` automatically from the repo root. Any Cursor-specific rules live under `07-prompts/cursor/` and can be exported into `.cursor/rules/` when a rule is worth enforcing at the editor level.

## Update rule

If a filename, folder name, or operating concept changes, update this map in the **same commit**. An outdated context map is worse than no map.
