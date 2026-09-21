# Closeout Buy Panel

Live buy-decision panel for Dynadot expired-domain closeouts (sheet 2026-09-22: 205 x 5L .com, 5 x 4L .net).
Each of the 210 candidates carries: closeout cost + Amman deadline + Dynadot link, JEV-mode probability
verdict (P(sell 1yr/3yr), EV net of fees, ROI vs cost, STRONG BUY/BUY/SPECULATIVE/PASS), a buy-side analyst
call with why/special/risks/exit-plan, and the empirical comp band from a 3-month aftermarket baseline.
98 analyst BUYs, $1,555 total to take them all.

Single self-contained `index.html`. Deployed via GitHub Pages.
Cloudflare alternative: `npx wrangler pages deploy . --project-name=closeout-buy-panel`
