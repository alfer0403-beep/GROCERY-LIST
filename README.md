# Grocery List

A phone-friendly grocery list app: saved items, check-off, aisles, favorites, multiple lists, voice input, learned prices with a running total, and pink/purple or blue themes (light and dark). Works offline and installs to the home screen. Data is stored on each phone.

## Put it online (GitHub Pages)
1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Repo **Settings → Pages → Source: GitHub Actions**.
3. Push to `main`. The workflow in `.github/workflows/deploy.yml` publishes the `public/` folder.
4. Open `https://<your-username>.github.io/<repo-name>/` on her phone.

## Install on the phone
- iPhone (Safari): Share → Add to Home Screen.
- Android (Chrome): menu → Install app.

## Updating
Edit `public/index.html`, then change `VERSION` in `public/sw.js` (e.g. `grocery-v2`) so phones refresh their offline copy.

## Local preview
`cd public && python3 -m http.server 8000`
