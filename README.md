# Project Arbor

Minimal public landing page for Project Arbor, the working name for the company building Workforce OS.

## Publish

This repository is designed to publish directly from the root of the `main` branch with GitHub Pages. It has no build step and no external dependencies.

## Custom domain

The site is published at `https://projectarbor.ca` through GitHub Pages.

DNS configuration:

1. The custom domain is set to `projectarbor.ca` in the repository's **Settings → Pages** screen.
2. The apex (`@`) points to GitHub Pages using these `A` records:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. `www` is a `CNAME` pointing to `sebastianrehaag.github.io`.
4. GitHub Pages redirects `www.projectarbor.ca` to the apex domain and serves the site over HTTPS.
