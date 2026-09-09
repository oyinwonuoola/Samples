# Mubarak Ibrahim — Portfolio Website

Modern editorial portfolio for **Mubarak Ibrahim, Digital Marketer** — pure static
site (HTML + CSS + JS, no build step), ready for **GitHub Pages**.

**Live URL (after deploy):** `https://oyinwonuoola.github.io/Samples/`
**Repo:** `https://github.com/oyinwonuoola/Samples`

## What's inside

- `index.html` — hero, skills ticker, about, content writing, digital marketing
  projects, TikTok ads feature, evidence gallery, contact
- `articles/` — 3 full-text writing samples
  - `yzy-memecoin.html` (crypto news)
  - `b2b-lead-generation.html` (B2B strategy playbook)
  - `volkswagen-esg.html` (ESG corporate report)
- `assets/img/` — 15 optimized evidence images (3.4 MB total)
- `assets/css/style.css`, `assets/js/main.js` — styling + lightbox/menu/animations
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Preview locally

```bash
cd portfolio
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages

### Option A — Terminal / git (exact commands for this repo)

```bash
cd portfolio
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/oyinwonuoola/Samples.git
git push -u origin main
```

Then enable Pages: open `https://github.com/oyinwonuoola/Samples` →
**Settings → Pages** → Source: **Deploy from a branch** → Branch: **main**,
folder **/(root)** → **Save**. Your site goes live at
`https://oyinwonuoola.github.io/Samples/` within ~1 minute.

> If the `Samples` repo already has files and the push is rejected, either
> `git pull origin main --rebase` first, or use Option B below.

### Option B — GitHub website (no terminal)

1. Go to `https://github.com/oyinwonuoola/Samples`.
2. Click **Add file → Upload files**.
3. Drag in everything from this `portfolio/` folder
   (`index.html`, `articles/`, `assets/`, `.nojekyll`, `README.md`).
4. Click **Commit changes**.
5. Go to **Settings → Pages**: Source **Deploy from a branch**, Branch **main**,
   folder **/(root)** → **Save**.
6. Live at `https://oyinwonuoola.github.io/Samples/`.

## Notes

- The TikTok video is embedded from Google Drive (47 MB — too heavy to bundle).
  Keep that Drive file's sharing on **"Anyone with the link can view"**.
- All article pages link back to their original Google Docs for verification.
- Contact: Oyinwonuoola@gmail.com ·
  [LinkedIn](https://www.linkedin.com/in/ibrahim-mubarak-333363290)
