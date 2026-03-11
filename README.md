# Sindhri.pk — Static Site

This repository hosts the **Sindhri.pk — Mirpurkhas Farm Experience** static website for GitHub Pages.

## Files
- `index.html` – the complete single‑page site (no build tools required)

## Quick Publish on GitHub Pages
1. Create a new **public** repository on GitHub, e.g., `sindhri.pk` or `sindhri-site`.
2. Upload (or commit & push) the `index.html` file to the repository **root** on the `main` branch.
3. Go to **Settings → Pages**.
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` and **Folder:** `/ (root)`
   - Click **Save**.
4. Wait ~1–3 minutes. Your site will be available at:
   - `https://<your-username>.github.io/<repo-name>/`

### (Optional) Use a Custom Domain
If you own `sindhri.pk` and want to use it:
1. In **Settings → Pages**, add your domain under **Custom domain** (e.g., `sindhri.pk`). This creates a `CNAME` file, or you can add one manually.
2. In your DNS provider (where `sindhri.pk` is managed), add these records:
   - **A** records pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or use a **CNAME** record for subdomains (e.g., `www.sindhri.pk` → `<your-username>.github.io`).
3. Back in GitHub Pages, enable **Enforce HTTPS** once the certificate is issued (can take up to an hour).

### Update the Site
Just edit and commit `index.html` — GitHub Pages auto‑deploys the latest commit on `main`.
