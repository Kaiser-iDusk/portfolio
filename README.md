# Portfolio — Deploy Instructions

This is a simple, single-file portfolio (`index.html`) styled with a frosted-glass aesthetic. The page is ready to deploy on GitHub Pages.

Quick deploy (recommended):

1. Create a new GitHub repository (for example `portfolio`).
2. From your project folder run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. Enable GitHub Pages in the repository settings:
- Go to Settings → Pages → Source → choose `main` branch and `/ (root)` folder → Save.

Alternative (publish via `gh-pages` branch):

```bash
# create a gh-pages branch and push
git checkout -b gh-pages
git push -u origin gh-pages
```
Then set Pages source to `gh-pages` branch in repository settings.

Notes & next steps:
- Replace the placeholder company names, roles, dates, and the email address in `index.html` with your real details.
- To use real company logos, replace the SVG placeholders inside each `.logo` element with your logo images (PNG/SVG) and update alt text.
- If you want automatic deploys, consider enabling GitHub Actions to build and push to `gh-pages`.

Enjoy — open `https://<your-username>.github.io/<your-repo>/` after Pages is active.
