
# JJR Quarto Academic Site (Starter)

## Quick Start
1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in your editor.
3. Replace placeholders (YOUR_GITHUB_USERNAME, YOUR_REPO_NAME, YOUR_ORCID, YOURHANDLE, YOUR_PLAYLIST_ID).
4. Put your BibTeX into `refs.bib` (export from Zotero/Scholar).
5. Preview locally:
   ```bash
   quarto preview
   ```
6. Publish to GitHub Pages:
   - Create a new repo and push these files.
   - In GitHub, enable Pages (Settings → Pages).
   - Or use `quarto publish gh-pages` (recommended).

## Structure
- `_quarto.yml` — site settings & navigation
- `index.qmd` — home
- `publications.qmd` + `refs.bib` — publications page
- `teaching.qmd`, `talks.qmd`, `projects.qmd`, `service.qmd`
- `media.qmd` — YouTube embeds
- `cv.qmd` — CV page (links to `files/jjr_cv.pdf`)
- `contact.qmd` — contact details
- `files/` — PDFs (CV, syllabi, slides)

## Tips
- Use Markdown; keep entries concise with links/DOIs.
- For images or PDFs, place them in `files/` and link relatively (e.g., `files/filename.pdf`).
- Customize theme via `_quarto.yml` (`format.html.theme`).
