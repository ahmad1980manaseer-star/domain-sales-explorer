# Domain Sales Explorer

Interactive viewer for a 3-month domain aftermarket sales analysis (2026-06-21 → 2026-09-19):
1,078 reported sales across 4L .com / 5L .com / 4L .net / .xyz tabs, each enriched with
registry (RDAP) holding history, DNS lander signatures, comp-based fair-value modeling and
per-domain analyst verdicts (why the price, confidence the price is genuine, listing type,
buyer type, ownership history).

Single self-contained `index.html` — no build, no server, no dependencies.

Deployed via GitHub Pages. Cloudflare Pages alternative: `npx wrangler pages deploy . --project-name=domain-sales-explorer`
