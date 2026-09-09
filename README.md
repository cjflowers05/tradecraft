# Tradecraft

A personal, 10-week curriculum for getting more out of Claude at work and at
home — four tiers (Recon, Fieldcraft, Standing Orders, Command), each week
pairing a work application with a home one, plus a "Long Game" section on
what keeps it compounding after week ten. Progress checkboxes save to your
browser's local storage, so they'll persist on whichever device you use it
from (checking it off on your phone won't show up on desktop, and vice
versa — it's per-browser, not synced).

It's a single self-contained file: `index.html`. No build step, no
dependencies to install.

## Put it on GitHub Pages (free hosting, works on any phone browser)

1. Go to [github.com/new](https://github.com/new) and create a new
   repository (public works fine — call it `tradecraft` or anything you
   like). Don't initialize it with a README, since you're uploading one.
2. On the new repo's page, click **Add file → Upload files**, then drag in
   both `index.html` and this `README.md`. Commit the upload.
3. Go to **Settings → Pages** (left sidebar). Under "Build and deployment,"
   set **Source** to "Deploy from a branch," pick the `main` branch and
   `/ (root)` folder, then **Save**.
4. Wait about a minute, then refresh that Pages settings screen — it'll show
   a live URL like `https://<your-username>.github.io/tradecraft/`. That
   URL works from any browser, including your phone's.

## Add it to your phone's home screen

Once you have the GitHub Pages URL loading in your phone's browser:

- **iPhone (Safari):** tap the Share icon → **Add to Home Screen**. It opens
  full-screen, no browser bar, like a regular app.
- **Android (Chrome):** tap the ⋮ menu → **Add to Home screen** (or
  **Install app**, depending on your Chrome version).

## Updating it later

Whenever you want to add a Tier V or tweak a week, ask Claude to hand you an
updated `index.html`, then use GitHub's **Add file → Upload files** again on
the same repo (it'll overwrite the old one) — or, if you're comfortable with
git, just replace the file and push. The Pages site updates automatically
within a minute or two of any push to `main`.
