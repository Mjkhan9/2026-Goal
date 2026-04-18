# Houston SMB Diagnostics

Primary working surface for Phase 1 — Research & Diagnose.

The purpose of this folder is to accumulate real, per-business diagnostic
briefs on Houston-area small businesses. These briefs drive offer design —
they are not produced after an offer is chosen.

## How this folder works

1. Identify candidate businesses using `_sourcing-parameters.md` as the
   filter. Add them to `_candidate-pool.md`.
2. For each business, run a signal scan (website, Google Business Profile,
   social, reviews, booking, contact flow) and complete a brief using
   `_template.md`.
3. Save each brief as `YYYY-MM-DD-<business-slug>.md` in this folder.
4. After each brief, update `_pattern-log.md` with any intervention types
   observed.
5. After roughly 10 briefs, review `_pattern-log.md` for emerging patterns.
   Use patterns — not prior assumptions — to decide what to offer.

## Files in this folder

| File | Purpose |
|---|---|
| `_template.md` | Per-business diagnostic brief template |
| `_intervention-taxonomy.md` | Reference list of intervention types — keep broad |
| `_sourcing-parameters.md` | How to find and filter candidate businesses |
| `_candidate-pool.md` | Running list of identified businesses |
| `_pattern-log.md` | Cross-business patterns observed over time |

## Rules
- No fabricated businesses, names, or research.
- Each brief must be based on publicly visible information.
- Conclusions go at the top of each brief, not buried at the bottom.
- Do not narrow the taxonomy until diagnostics justify it.
