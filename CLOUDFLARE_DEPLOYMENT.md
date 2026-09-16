# Deploy to Cloudflare Pages

This project is configured for the free `*.pages.dev` domain.

## Direct deployment

1. Run `npm install`.
2. Run `npm run deploy`.
3. Sign in to Cloudflare when Wrangler asks.
4. The configured project name is `syazwan-razak`. If available, the website will use `https://syazwan-razak.pages.dev`.

## Git-based deployment

Push this project to GitHub or GitLab, then create a Cloudflare Pages project using:

- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `dist`
- Node.js version: `22`

Cloudflare will create a free `*.pages.dev` address and redeploy automatically after every push.

## Commands

- `npm run build` — create the production website
- `npm run pages:preview` — preview the production build locally with Cloudflare
- `npm run deploy` — build and deploy to Cloudflare Pages

The final subdomain depends on availability in your Cloudflare account.
