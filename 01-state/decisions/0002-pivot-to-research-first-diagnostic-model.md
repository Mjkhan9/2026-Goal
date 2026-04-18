# 0002 — Pivot to research-first, diagnostic-led Houston SMB model

- **Date:** 2026-04-17
- **Status:** accepted
- **Owner:** Mohammad Jawad Khan
- **Supersedes:** direction implied by `00-compass/north-star.md` prior to this commit

## Context
After drafting the north star and first action queue around the "Entra / M365
Identity Hygiene Audit for SMBs" hypothesis, it became clear the project had
narrowed prematurely. The prior direction:

- Anchored on operator expertise (Entra/M365) before any diagnostic data
  confirmed that Houston SMB buyers have that problem as a priority.
- Assumed a specific deliverable, ICP vertical, and pricing band before a
  single discovery conversation had taken place.
- Conflated "this seems like a fit" with "this is the right thing to test first."

Good strategy at this stage is to research first, then let observed patterns
drive which interventions to offer. Committing to a specific deliverable before
accumulating diagnostic volume is just guessing with more documentation.

## Decision
Shift to a research-first, diagnostic-led model:

1. The immediate work is sourcing and diagnosing Houston-area SMBs — not
   building a predefined offer.
2. Intervention types remain broad. Diagnosis determines what each business
   actually needs. No category is pre-selected as the lead offer.
3. Narrowing to a specific vertical or deliverable is deferred until
   diagnostic patterns from real businesses justify it.
4. The prior path (Entra/M365 audit hypothesis) is archived, not deleted.
   It may re-emerge if diagnostics confirm identity/access issues are common
   and prioritized by buyers in this market.

## What this does NOT mean
- This is not a license to be unfocused. The target geography (Houston-area
  SMBs) and the research method (per-business diagnostic briefs) are both
  specific.
- It does not invalidate the operator's Microsoft/Entra background. That
  remains a real capability. It just should not drive offer selection before
  demand is observed.

## Consequences
- **Positive:** Avoids the failure mode of building the wrong offer well.
  Builds real market knowledge. Intervention choice is grounded in evidence.
- **Negative / costs:** Takes longer to have a "product" to sell. Requires
  discipline to log diagnostics rather than jump to delivery.
- **Reversibility:** Easy. If diagnostics surface a clear Entra/M365 pattern,
  Path A can be revived using the archived files.

## Archived path
`99-archive/path-a-entra-m365-audit/` — preserved for reuse if evidence warrants.
