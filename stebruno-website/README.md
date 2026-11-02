# Stefano Bruno — Personal Research Website

A minimalist, responsive, single-page research website for GitHub Pages.

## Publish

1. Log in to GitHub as `stebruno`.
2. Create a **public** repository named **`stebruno.github.io`** (exact spelling).
3. Upload `index.html`, `assets/`, `.nojekyll`, and this README to the repository **root** on the `main` branch. **Do not upload the enclosing `stebruno-website` folder.**
4. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Wait a few minutes, then visit https://stebruno.github.io/ .

No Jekyll, Ruby, Node.js, build process, or external dependencies are required. The `.nojekyll` file tells GitHub Pages to serve the files directly.

## Edit

- `index.html`: all text, publication links, navigation, contact details.
- `assets/style.css`: fonts, spacing, colors, layout.
- `assets/main.js`: mobile navigation and footer year.
- Portrait: currently uses `https://github.com/stebruno.png?size=460` because the original Google Sites image could not be downloaded. To use a local photo, add `assets/profile.jpg` and change the `src` in `index.html` to `assets/profile.jpg`.
- CV: when ready, upload a PDF as `assets/Stefano_Bruno_CV.pdf` and add a link in the hero quicklinks.

## Review before publishing

- Confirm current affiliations and position titles.
- Confirm descriptions of submitted / in-preparation manuscripts, which may change.
- Verify that all paper and institutional links point to the intended destinations.
- Replace generic ResearchGate and institutional links with exact profile/event pages if desired.
- The GitHub avatar may not be the same as the original Google Sites portrait.
- No CV PDF is included because one was not available from the source page.

## Source

Migrated and edited from https://sites.google.com/view/drstefanobruno/home (accessed November 2026), and cross-checked against public GitHub profile and ICML proceedings. The prose is edited for an AI-focused research presentation.
