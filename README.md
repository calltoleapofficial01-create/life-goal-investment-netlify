# Life Goal Investment

A fresh, Netlify-ready React/Vite frontend for Life Goal Investment.

## Local development
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```

## Deploy to Netlify
Import this repository in Netlify. Build command: `npm run build`. Publish directory: `dist`. The included `netlify.toml` also provides SPA route fallback.

## Important integration note
This repository starts as a clean frontend. Authentication, account balances, admin permissions, admin-managed instrument prices, order persistence, and the existing deposit/withdrawal workflows must be connected to the existing Life Goal backend before replacing the current production site. Do not copy private keys into frontend environment variables. This UI does not claim to execute orders on an exchange.
