# Deploy to Cloudflare Pages (one-time, ~60 seconds)

wrangler is installed on this machine but not logged in. Run from this folder (`site/`):

```bash
npx wrangler login          # opens browser, click "Allow"
npx wrangler pages deploy . --project-name=domain-sales-explorer --branch=main
```

That prints the live URL: `https://domain-sales-explorer.pages.dev`

Optional custom domain: Cloudflare dashboard → Pages → domain-sales-explorer → Custom domains.

Re-deploys after updates: re-run the same `wrangler pages deploy` command,
or connect the GitHub repo (ahmad1980manaseer-star/domain-sales-explorer) in the
Cloudflare Pages dashboard for automatic deploys on every push.
