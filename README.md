# Project Arbor

Minimal public landing page for Project Arbor, the working name for the company building Workforce OS.

## Publish

This repository is designed to publish directly from the root of the `main` branch with GitHub Pages. It has no build step and no external dependencies.

## Connect `projectarbor.ai`

The site should remain on its GitHub Pages URL until the domain is registered and DNS is ready.

After registration:

1. Add the custom domain `projectarbor.ai` in the repository's **Settings → Pages** screen.
2. At the registrar, add `A` records for the apex (`@`) pointing to:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Add a `CNAME` record for `www` pointing to `sebastianrehaag.github.io`.
4. Wait for GitHub's DNS check to pass, then enable **Enforce HTTPS**.

GitHub will create the repository `CNAME` file when the custom domain is saved in Pages settings.
