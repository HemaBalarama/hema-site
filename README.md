# hema-site
Public personal site (GitHub Pages via GitHub Actions).

## Public/Private split

- Public repo: publishable site content only.
- Private workspace: keep drafts, notes, and unpublished data in `private/` (ignored by git in this repo).

## Deploy

- Workflow file: `.github/workflows/quarto-pages.yml`
- Trigger: push to `main`
- GitHub setting required: `Settings -> Pages -> Source -> GitHub Actions`
