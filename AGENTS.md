# Documentation project instructions

## About this project

- Internal Mintlify docs for **adorabl** support
- Pages are MDX with YAML frontmatter
- Configuration lives in `docs.json`
- Source app: https://github.com/stellarone/sherpa-e9c75a24
- Supabase project: `linqdstukqayvducxguc` (name: `sherpa`)

## Terminology

- Use "organization" / "org" for tenancy
- Use "customer" for AR parties (`ar_customers`)
- Use "supplier" for AP parties (`ap_suppliers`)
- Use "journal entry" / "JE" with `entry_code`
- Prefer status values that match live check constraints

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, table/column names, and code references

## Content boundaries

- Internal support only — not customer-facing marketing
- No secrets, tokens, vault payloads, or webhook signing keys
- Data model docs must be generated from the **live** Postgres schema; migrations are secondary cross-check only
- Do not document break-glass admin procedures that bypass RLS without escalation guidance
