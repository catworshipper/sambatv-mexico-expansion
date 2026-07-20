# SambaTV — Mexico Expansion: Strategic Data Operations Blueprint

Single-file, interactive HTML report for stakeholders (CTO — Jaya Aswani, COO — Alvir Navin) covering SambaTV's potential expansion of data operations into Mexico.

## Contents

Six sections following the strategic decision memo: cost vs. scarcity, hiring hubs (CDMX / Monterrey / Guadalajara), compensation benchmarks, real employment cost (taxes & 2026 labor laws), retention drivers, and the execution roadmap (EOR → entity).

Three source documents unfold on click, placed where they continue the narrative:

- **Salary Benchmarks** — inside Section 3 (Compensation)
- **Employer Branding: The Plata Case** — inside Section 5 (Retention)
- **Comparison of EOR Partners** — inside Section 6 (Execution)

## Tech notes

- `index.html` is fully self-contained: no build step, no CDNs, no external dependencies. Charts are pure CSS (a Chart.js CDN silently failed for end users in a previous project, so this is deliberate).
- Colors follow SambaTV report conventions: navy `#16233B` / blue `#2F6FB2` primary, red `#A2242F` for risk, green `#1F7A54` for opportunity.

## Deploy (GitHub Pages)

1. Push this folder to a GitHub repo.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Share the resulting URL (avoids the Google Drive raw-HTML preview problem).
