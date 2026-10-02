# adorabl Support Docs

Internal Mintlify documentation for adorabl support engineers.

## Contents

- Orientation and systems map
- Support intake / escalation / safe investigation
- Troubleshooting runbooks (bank rec, AP, AR, GL, inventory, integrations)
- Data model generated from the **live** Supabase Postgres schema (`linqdstukqayvducxguc`)
- Integrations (Plaid, Trackstar/Shopify, EasyPost)

## Development

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

Validate:

```bash
mint validate
```

## Data model source of truth

The data model section is derived from live database introspection (tables, columns, PKs, FKs). Migrations are not the primary source.

## Safety

Do not commit secrets, access tokens, or customer PII into this repository.
