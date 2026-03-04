# Form & Signal — Landing Page

A tiny, zero-build, static landing page you can deploy to Vercel (recommended) or anywhere that serves static files.

## What's in here

- `index.html` — the landing page
- `public/fs.svg` — your logo mark
- `favicon.svg` — favicon (same mark)
- `vercel.json` — optional Vercel settings

## Quick start (local)

Just open `index.html` in your browser.

## Deploy to Vercel (recommended)

1. Push this repo to GitHub.
2. In Vercel: **Add New → Project**, import the repo.
3. Deploy (no framework detected is fine).
4. In Vercel project settings → **Domains**, add:
   - `form-signal.com`
   - `www.form-signal.com` (optional)

Vercel will tell you the exact DNS records to add at your registrar.

## Update links

Edit `index.html` and change:

- The app URL (default is `https://erg.form-signal.com`)
- The GitHub link

## Notes

Keeping the app on a subdomain like `erg.form-signal.com` avoids base-path routing issues and always points users at your latest Vercel production deployment.
