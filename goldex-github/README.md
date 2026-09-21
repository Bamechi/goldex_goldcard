# Goldex — landing page + web app (v0.4)

Two files, no build step.

- `index.html` — the landing page (sells the product; "Log in" and "Open the web app" link to `app.html`)
- `app.html` — the Goldex web app

## Deploy
- **GitHub Pages:** push this folder to a repo, Settings > Pages > Deploy from branch (root).
- **Vercel:** import the repo, framework "Other", no build command, output directory `.`.

## Notes
- App data is stored in the visitor's browser (localStorage + IndexedDB). Supabase replaces this in Phase 1 production.
- External loads: Google Fonts (Instrument Serif, Geist) and cdnjs (qrcodejs, jsPDF). Everything else is inline.
- Test account: amechi@addcolormedia.com / VANTA

## v0.7 additions
- `purchase.html` — unlisted member page (not linked from the nav; `noindex`). Links the Member Guide PDF.
- `goldex-user-guide.pdf` — downloadable guide served by purchase.html.
