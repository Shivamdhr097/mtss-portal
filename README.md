# MTSS Portal GitHub Pages Setup

This folder is ready for GitHub Pages.

## Files

- `index.html` - the portal page
- `data/portal-data.json` - sample data file

## Publish With GitHub Website

1. Go to GitHub and create a new repository, for example `mtss-portal`.
2. Upload everything inside this folder to the repository root.
3. Open repository `Settings`.
4. Go to `Pages`.
5. Set source to `Deploy from a branch`.
6. Choose branch `main` and folder `/root`.
7. Save.

Your portal will be live at:

`https://YOUR-GITHUB-USERNAME.github.io/mtss-portal/`

## Important Security Note

Do not put GitHub tokens, real passwords, or private bank data directly in `index.html` or `data/portal-data.json` if the repository is public.

For real login and private data storage, use a backend service or GitHub OAuth app.
