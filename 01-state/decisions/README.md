# Decisions

Lightweight **Architecture Decision Record (ADR)** style log for any meaningful choice — strategic, commercial, or technical.

## Rules

- One decision per file.
- Filename format: `NNNN-short-title.md` (zero-padded sequential, e.g. `0001-pick-first-niche.md`).
- Never delete a decision. To change direction, write a new record that **supersedes** the old one and update the old file's status.
- Keep each record under ~30 lines. Specific > exhaustive.

## Template
Use `0000-template.md` as the starting point.

## Statuses
- `proposed` — under consideration
- `accepted` — active
- `superseded by NNNN` — replaced by a later decision
- `deprecated` — no longer relevant but preserved for history
