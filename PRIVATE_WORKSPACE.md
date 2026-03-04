# Private Workspace

Use `private/` for incomplete writing, notes, and unpublished data.

This folder is ignored by the public site repo (`.gitignore`), so files there will not be committed here.

## Create a separate private repo (one-time)

From the project root:

```bash
cd private
git init
git add .
git commit -m "Initialize private workspace"
git branch -M main
git remote add origin <your-private-repo-url>
git push -u origin main
```

## Current moved files

- `private/notes/ideas.qmd`
- `private/writing/posts/2025-08-21-first-post.qmd`
- `private/archive/docs-before-public-split/`
