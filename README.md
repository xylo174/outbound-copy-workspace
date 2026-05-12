# Outbound copy workspace

Paste-ready **cold email** copy for **PlusVibe** / **Smartlead**: sequences, spintax (`{{random|…}}`), merge-tag notes, and Node Partners sign-off patterns.

## For your friend

1. Clone: `git clone https://github.com/xylo174/outbound-copy-workspace.git`
2. Open `copy/` — every file is markdown you can copy from.
3. **Merge tags** used across templates: `{{first_name}}`, `{{company_clean}}`, `{{icp}}`, `{{service}}`, `{{sender_first_name}}`, `{{sender_last_name}}` (match these to your tool’s field names).
4. **Do not** paste real API keys, passwords, inboxes, or client secrets into this repo if you fork it; keep env vars local.

## Security / privacy

This pack is **copy and URLs only** (public site links like `adrevival.io`). It should not contain personal emails, credentials, or API tokens. If you ever spot something sensitive in a commit, rotate the credential and open an issue or remove it from history.

## Layout

| File | Contents |
|------|----------|
| `copy/node-partners-outreach-templates.md` | Short AI-outbound opener + merge versions + **F1–F3 follow-ups** + pointers |
| `copy/icp-service-ai-outbound-spintax.md` | Short ICP + service + AI outbound agents (PlusVibe spintax) |
| `copy/eric-nowoslawski-full-sequence.md` | Full Eric-style sequence, Node Partners footer |
| `copy/nowoslawski-icp-service.md` | Framework + sources + Eric blocks (some still say “Eric” in examples) |
| `copy/adrevival-private-management-sequence.md` | AdRevival-specific sequence |

## Spintax note

PlusVibe-style templates use **`{{random|a|b|c}}`**. Smartlead native spintax often uses **`{a|b|c}`** — convert if your ESP expects curly braces only.
