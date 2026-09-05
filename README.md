# IKARDIO GYM Website

Static one-page bilingual (EN/AR) website for IKARDIO GYM — Obour Branch.

## Files
- `index.html` — the full site (videos are embedded inside this file as base64, so it works standalone)
- `logo.png` (transparent background), `promo-newspace.png`, `promo-competition.png`, `promo-feeltheburn.png` — images used by the page

## Deploy on Vercel (recommended, free)
1. Create a new GitHub repository and upload these files to the repo root (keep the file names exactly as they are).
2. Go to https://vercel.com → **Add New Project** → **Import** your GitHub repo.
3. Framework Preset: choose **Other** (no build step needed).
4. Build Command: leave empty. Output Directory: leave as `.` (root).
5. Click **Deploy**.

## Deploy on GitHub Pages (alternative, also free)
1. Push these files to a GitHub repo.
2. Repo Settings → Pages → Source: `main` branch, root folder.
3. GitHub will publish it at `https://<username>.github.io/<repo-name>/`.
