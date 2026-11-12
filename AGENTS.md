# ClinicOS agent conventions

This repository currently contains a **static interactive prototype**, not a production clinic management system.

## Safety
- Never use real patient data, real identities, live payment details, or secrets.
- Never call this prototype PDPL-, ZATCA-, or NPHIES-compliant.
- Only fictional information is permitted in source files and deployment previews.

## Development
- Entry point: `index.html`; no dependencies or build step.
- Local preview: `python3 -m http.server 8000` and open `http://localhost:8000`.
- Automated test, migration, and seed commands do not exist for this static demo.
- Check changes in English and Arabic (RTL), desktop and tablet layouts.
- Ensure the branch selector scopes every list and patient record.
- Record clinical and financial actions only in browser memory.

## Next steps
When building production Phase 1, scaffold a separate Next.js/TypeScript implementation with PostgreSQL/Prisma, server-side scoped RBAC, encryption, append-only audit events, Vitest and Playwright. Do not quietly treat the static demo as the production backend.

## Decisions
- Multi-branch demo: two fictional Riyadh branches
- Three synthetic doctors across four specialties
- Insurance visual workflow only; NPHIES stub
- On-prem is the eventual production target; this hosted static demo has no real patient data.
