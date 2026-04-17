# 07 — Prompts

AI operating instructions kept under version control so they improve over time instead of being retyped in every chat. This folder is organized by **tool surface** and **prompt type**, so nothing gets dumped into a single pile.

## Subfolders

### Tool-surface prompts (paste into a specific tool)
- `claude-project/` — text that belongs in a Claude Project's **Custom Instructions** field. Source of truth lives here; Claude Project is a mirror.
- `cursor/` — Cursor-specific rules / system prompts. Promote to `.cursor/rules/` when a rule is worth enforcing at the editor level.

### Reusable prompts (not tied to a tool)
- `system/` — master / persistent system prompts (identity, repo-wide behavior, tone).
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

- **Tool surface first, then type.** If a prompt is meant for a specific tool's dedicated surface (Claude Project instructions, Cursor rules), it goes in the tool folder. Everything else goes in `system/`, `tasks/`, or `personas/`.
- **One prompt per file.** Filename in `kebab-case`, descriptive.
- **Edit in place.** Update the `Last revised` date. Keep older versions only if they offered meaningfully different behavior.
- **No dying in chat.** When a chat-derived prompt proves useful, move it here.
- **Reference by path** when using a prompt (e.g. _"using `07-prompts/tasks/niche-evaluation.md`"_).
- The Claude Project's Custom Instructions field is a **mirror** of `claude-project/instructions.md`. Never edit only in Claude — reflect the change here in the same session.
