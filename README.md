# markgray-site

This repository contains the static website for Mark Gray.

Development

- Branches: work in the `dev` branch and open pull requests to `main` for deployment.
- Run locally: open `index.html` in a browser or serve the directory with a static server (e.g., `python -m http.server 8000`).

Deployment

This repo includes a GitHub Actions workflow to deploy the site to GitHub Pages. The workflow is configured to deploy from `main` on push. To publish:

1. Merge changes from `dev` into `main` (create PR from `dev` → `main`).
2. Ensure the repository visibility and Pages settings meet your needs (Pages from the repo root).
3. (Optional) Add a `CNAME` file at the repo root for a custom domain and configure DNS.

Notes

- The site is currently a static HTML site (no build step). If you add a build tool (npm, eleventy, Hugo, etc.), update the workflow to run the build and change the artifact path.
- There is an existing `netlify.toml` so Netlify deployment is also supported — you can connect this repo to Netlify for continuous deploys.

Author: Markgray217

License: (add a LICENSE file if you want to make this public)
