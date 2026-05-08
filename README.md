# opacommunity.com — marketing site

Single-page landing site for OPA Community. Pure HTML, no build step.

## Local preview

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deploy

Push to `main`. Netlify auto-deploys.

## What needs configuring before launch

- [ ] Replace `REPLACE_WITH_CF_ANALYTICS_TOKEN` in `index.html` with your Cloudflare Web Analytics site token
- [ ] After first Netlify deploy: enable form notifications in Netlify dashboard (Forms → newsletter → Settings)
- [ ] Verify `https://app.opacommunity.com` is reachable (it should be — deployed already)

## Forms

The newsletter form uses **Netlify Forms** — submissions show up in the Netlify dashboard at Forms → newsletter. Set up an email notification there to get pinged when someone signs up.

## Future iteration

Design lives in Claude Design. To make changes: open the project there, iterate, re-export, re-bake into static HTML, push.
