# RELIANCE website

Static single-page website for the RELIANCE COST Open Call 2026 proposal.

## Files

- `index.html` — page content
- `style.css` — visual design and responsive layout
- `script.js` — mobile navigation and subtle scroll reveal
- `assets/` — portraits, favicon and concept-note PDF
- `.nojekyll` — tells GitHub Pages to serve the files directly

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, e.g. `reliance`.
2. Upload all files and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. GitHub will publish the project site at:
   `https://YOUR-USERNAME.github.io/reliance/`

If you instead create a repository named exactly `YOUR-USERNAME.github.io`, it becomes your account-level Pages site and the URL is:
`https://YOUR-USERNAME.github.io/`

## Update the Google Form link

The current Google Form URL is embedded in `index.html`. Search for:
`docs.google.com/forms`
and replace it if the form URL changes.

## Optional custom domain

A custom domain can later be configured under **Settings → Pages → Custom domain**.
