# ClinicOS — Interactive prototype

A responsive, bilingual (English/Arabic) clinic management UI demonstration for a fictional multi-branch outpatient clinic in Saudi Arabia.

## View
Open `index.html` in a browser, or deploy this repository to Vercel as a static site.

## Demo interactions
- Switch between Riyadh Main and Riyadh North
- Switch English / Arabic (RTL)
- Search fictional patient records and register fictional patients
- Book appointments, with a same-doctor/same-time conflict check
- Check in patients and advance them through a fictional waiting queue
- Fill out vitals and draft SOAP notes
- Review fictional invoices and simulate payments
- Explore an insurance register and branch settings

## Important — demo only
**Not a production healthcare system.** No authentication, enforced RBAC, database, persistent clinical records, audit trail, backup, ZATCA compliance, NPHIES connectivity, or clinical security controls.

All fictional edits are stored in the browser session memory and reset on reload. Never enter real patient information, payment details, or secrets.

## Production roadmap
The approved production foundation uses Next.js App Router, TypeScript, PostgreSQL, Prisma, branch-scoped authorization, audited clinical records, and on-prem Docker.

## Deploy to Vercel
Use the **Other** framework preset, root directory `./`, and no build command. Vercel serves the root `index.html`.
