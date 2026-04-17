# 0001 — Retire root-level memory files; 01-state and 00-compass are canonical

- **Date:** 2026-04-17
- **Status:** accepted
- **Owner:** Mohammad Jawad Khan

## Context
The repo contained two parallel memory systems covering the same ground:
(a) root-level files — MASTER_BRIEF.md, CURRENT_STATE.md, NEXT_ACTIONS.md,
HANDOFF_CONTEXT.md — originally intended as the Claude Project upload set,
and (b) folder-based files — 00-compass/north-star.md, 01-state/current-focus.md,
01-state/next-actions.md, 01-state/handoff.md — which CLAUDE.md and
AGENTS.md treat as canonical. The two sets drifted almost immediately
after the first real edits, producing contradictory statements about
project state (niche selected vs. not, last-updated dates, next actions).

## Decision
Retire the four root-level memory files. The 00-compass/ and 01-state/
files become the single source of truth. Claude Project knowledge uploads
point to those files directly.

## Consequences
- **Positive:** One source of truth. Matches existing CLAUDE.md / AGENTS.md
  guidance. Eliminates the drift failure mode. Folder-based structure
  scales better as decision log and state files accumulate.
- **Negative / costs:** Claude Project upload set must be reconfigured to
  point at 00-compass/ and 01-state/ paths instead of root. Prior chat
  references to "MASTER_BRIEF.md" etc. become stale vocabulary.
- **Reversibility:** Easy — files are preserved in git history.

## Alternatives considered
- Keep root files, retire 01-state duplicates: rejected. CLAUDE.md and
  AGENTS.md already name 01-state as canonical; reversing that would
  require larger doc changes.
- Auto-generate root files from 01-state via script: rejected.
  Complexity not justified at current stage.

## Links
- 00-compass/north-star.md
- 01-state/current-focus.md
- 01-state/next-actions.md
- 01-state/handoff.md
- 01-state/context-map.md
