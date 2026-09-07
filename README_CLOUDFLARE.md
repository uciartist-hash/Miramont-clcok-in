# Miramont Time

Miramont Cabinetry workforce time system.

## Routes

- `/` — employee kiosk
- `/admin.html` — admin panel

## Cloudflare Workers

This repository is configured for Cloudflare Workers Static Assets.

Deploy command:

```bash
npm install
npm run deploy
```

For production, connect this repository to Cloudflare Workers Builds so pushes to `main`
deploy automatically.
