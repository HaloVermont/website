# Halo Vermont — Static Website

A simple, elegant single-page site for Halo Vermont. No monthly fees — host on GitHub Pages, Netlify, or Vercel.

## Files
- `index.html` — the website
- `Halo-LogoV1.gif` — your logo (place it next to index.html)
- `assets/favicon.svg` — site icon
- `404.html` — not-found page (Netlify/GitHub Pages compatible)
- `robots.txt` — allow indexing

## Quick Publish Options

### GitHub Pages
1. Create a new repo named `halo-vermont-site`.
2. Upload all files/folders from this zip (or push via Git).
3. In **Settings → Pages**, set:
   - Source: `Deploy from a branch`
   - Branch: `main` / root (`/`)
4. Your site appears at `https://<username>.github.io/halo-vermont-site/`.
5. To use your domain, add it under **Pages → Custom domain** and follow the DNS steps.

### Netlify (drag‑and‑drop)
1. Go to https://app.netlify.com and click **Add new site → Deploy manually**.
2. Drag the folder into the drop area.
3. In **Site settings → Domain management**, add your custom domain and follow the DNS instructions.

### Vercel
1. Go to https://vercel.com and **Add New Project → Import** this folder or a Git repo.
2. Accept defaults and deploy.
3. Add your custom domain in the project **Settings → Domains**.

## Connect Your Domain
At your domain registrar, create a **CNAME** record pointing to your host (for example, `username.github.io` for GitHub Pages, or the value provided by Netlify/Vercel). Propagation can take a little while.

---

If you want more sections (gallery, reviews, hours), just edit `index.html`. The site is plain HTML/CSS for maximum simplicity.
