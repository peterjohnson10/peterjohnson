# Peter Johnson Research Platform

A static, multi-page academic website requiring no build tools.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder, preserving the directories.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/root`.
5. Save.

## Deploy on Vercel

Import the GitHub repository into Vercel. No framework preset or build command is required.

## Important URL note

The pages currently use root-relative links such as `/research/index.html`. These work with a custom domain or a Vercel deployment. For GitHub Pages on a project subdirectory such as `username.github.io/repository`, either configure a custom domain or replace root-relative paths with relative paths.

## Editing

- Main page: `index.html`
- Shared design: `styles.css`
- Mobile menu and year: `script.js`
- Research pages: `research/`
- Publication pages: `publications/`
- Downloads: `downloads/`

The structure is intentionally static and transparent. It can later be migrated to Astro without changing the information architecture.
