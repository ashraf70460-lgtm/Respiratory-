# COPD GOLD 2026 Assistant

GOLD 2026 COPD clinical decision support and consultant learning hub by Dr. Ashraf Ahmed.

- Static single-page app: `index.html` (no server, no build step).
- All patient data stays in each visitor's own browser (localStorage). Nothing is sent to a server.
- Every recommendation needs clinician confirmation; sources are labelled with GOLD 2026 page references.

## Publish on Vercel
1. vercel.com → Add New → Project → Import `Respiratory-` from GitHub.
2. Framework preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy. Every push to `main` redeploys automatically.

`vercel.json` adds clean URLs and security headers (CSP, no framing).
