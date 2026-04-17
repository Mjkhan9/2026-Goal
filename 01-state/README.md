# 01 — State

Live operating state. **This folder must always reflect reality.** If it doesn't, the repo is lying and no AI (or future you) can trust it.

## Files

- `current-focus.md` — the single most important thing being worked on right now.
- `next-actions.md` — the short, concrete action queue.
- `weekly-review.md` — rolling log of weekly reviews.
- `handoff.md` — context any AI/session needs to pick up work cold.
- `context-map.md` — mapping between Claude Project concepts and this repo's files. Update whenever filenames or operating concepts change.
- `decisions/` — decision records (ADR-style). Every meaningful choice gets one.

## Lifecycle

These files are **not** accessories. They are the live operating layer of the business, and every working session should touch at least one of them.

- **Start of session:** read `current-focus.md` → `next-actions.md`. If resuming cold, also read `handoff.md`.
- **During session:** when a meaningful choice is made, add a decision record in `decisions/` using `0000-template.md`.
- **End of session:** update `current-focus.md` and `next-actions.md`. If stopping mid-thread or switching tools, rewrite `handoff.md` so the next session starts at zero friction.
- **Weekly:** add an entry to `weekly-review.md`.

## Rules

- This folder must always reflect reality. If it doesn't, the repo is lying and no AI (or future you) can trust it.
- Never delete a decision record — supersede it with a new one instead.
- Keep each file scannable in under a minute.
- If a filename or concept changes, update `context-map.md` in the **same commit**.
