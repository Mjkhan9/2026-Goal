# 01 — State

Live operating state. **This folder must always reflect reality.** If it doesn't, the repo is lying and no AI (or future you) can trust it.

## Files

- `current-focus.md` — the single most important thing being worked on right now.
- `next-actions.md` — the short, concrete action queue.
- `weekly-review.md` — rolling log of weekly reviews.
- `handoff.md` — context any AI/session needs to pick up work cold.
- `decisions/` — decision records (ADR-style). Every meaningful choice gets one.

## Rules

- Update `current-focus.md` and `next-actions.md` at the end of every working session.
- Write a `handoff.md` update before stopping work mid-thread or switching tools.
- Never delete a decision record — supersede it with a new one instead.
- Keep each file scannable in under a minute.
