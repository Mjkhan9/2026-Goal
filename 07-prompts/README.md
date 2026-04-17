# 07 — Prompts

AI operating instructions kept under version control so they improve over time instead of being retyped in every chat.

## Subfolders

- `system/` — global / persistent system prompts (identity, role, repo-wide behavior).
- `tasks/` — task-specific prompts (e.g. "draft a cold email", "evaluate a niche", "review a proposal").
- `personas/` — role-based prompts (e.g. "strategist", "copy reviewer", "technical implementer").

## Standard prompt file format

```
# <Prompt name>

- Use for:
- Inputs required:
- Expected output:
- Model / tool notes:
- Last revised: YYYY-MM-DD

---

<prompt body>
```

## Rules

- Version prompts by editing in place and noting the revision date; keep older versions only if they offered meaningfully different behavior.
- When a chat-derived prompt proves useful, move it here. Do not let good prompts die in chat history.
- Reference prompts by path when using them (e.g. _using `07-prompts/tasks/niche-evaluation.md`_).
