# 09 — Clients

Per-client engagement folders. Empty until there are real clients.

## Rules

- One subfolder per client. Use a **codename** or slug (e.g. `acme-co`) — avoid real names if the repo is shared beyond private access.
- Copy `_template/` as the starting structure for each new engagement.
- Sensitive materials go under `<client>/private/` or `<client>/_raw/` (already `.gitignore`d).
- When an engagement ends, keep the folder in place; only archive if it is truly dormant and unlikely to be referenced.

## Default client folder layout

```
<client-slug>/
├── README.md         # What this engagement is, status, contacts (redacted if needed)
├── brief.md          # The agreed problem and desired outcome
├── scope.md          # What's in, what's out, timeline, pricing
├── delivery/         # Work product
└── assets/           # Client-provided material
```
