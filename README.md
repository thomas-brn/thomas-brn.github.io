# Open source contributions portfolio — Thomas Broine

This folder contains the portfolio code (static HTML/CSS). It is ignored by the FerrisKey repository (see root `.gitignore`).

## Hosting on GitHub Pages

1. **Create a dedicated GitHub repository** for the portfolio (e.g. `thomasbroine/portfolio` or `username.github.io`).

2. **Copy this folder’s contents** into that repo (`index.html`, `css/`, etc.). You can either clone FerrisKey, copy `portfolio/` elsewhere, then `git init` and push; or create the repo and copy only the portfolio files into it.

3. **Enable GitHub Pages**: in the repo → Settings → Pages → Source: **Deploy from a branch** → select branch `main` (or `master`) and folder **/ (root)**.

4. The site will be available at: `https://<username>.github.io/<repo-name>/`  
   If the repo is named `username.github.io`, the URL will be: `https://<username>.github.io/`

## Structure

- `index.html` — main page (edit to add new contributions).
- `css/styles.css` — styles (minimal, responsive).

To add a contribution: duplicate the `<article class="contribution-card">` block in `index.html` and fill in the fields (badge, title, project, description, impact).
# thomas-brn.github.io
