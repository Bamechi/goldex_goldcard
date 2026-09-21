# Goldex — landing, app, member page (v0.8)

Static files, no build step.

- `index.html` — landing page
- `app.html` — the Goldex web app (log in: amechi@addcolormedia.com / VANTA)
- `purchase.html` — unlisted member page (noindex); the same guide lives inside the app under Guide
- `goldex-user-guide.pdf` — downloadable Member Guide

## Test today (portable links)
Cards, QR codes, and NFC links carry the card inside the link, so they open on any phone once deployed.
Settings > Sharing shows "Portable" and fills your app address automatically on Vercel.
Intake submissions arrive as a pre-written email or text; paste them into Contacts > Import > Paste Goldex submissions.

## Deploy
GitHub Pages or Vercel (framework "Other", no build command, output directory `.`).
