# Automation APP — legal pages

Static Terms of Service and Privacy Policy pages for the TikTok developer app.

- `index.html` — landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy

## Deploy with GitHub Pages

1. Push this repo to GitHub (it must be public on a free plan).
2. Repo **Settings → Pages** → Source: *Deploy from a branch*, pick the branch, folder `/ (root)`.
3. The pages will be at:
   - `https://<user>.github.io/<repo>/terms.html`
   - `https://<user>.github.io/<repo>/privacy.html`

## TikTok URL verification

TikTok asks you to verify any URL you enter (**URL properties** in the developer portal). Pick *URL prefix*, enter `https://<user>.github.io/<repo>/`, download the `tiktok…txt` signature file, commit it to the repo root, push, then click **Verify**.
