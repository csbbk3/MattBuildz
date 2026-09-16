# Matthew Wool — Portfolio

A static portfolio with project photos, technical build notes, an About page, and a downloadable resume. No installation or build step required.

## Upload to GitHub Pages

1. Extract this ZIP on your computer.
2. Open or create your GitHub repository. For GitHub Free, use a public repository.
3. Select **Add file → Upload files** (or **uploading an existing file** for an empty repository).
4. Upload the extracted contents, including the entire `assets` folder. Upload the files themselves, not the ZIP or an enclosing folder. `index.html` must be at the repository root. Include `.nojekyll` if your file browser shows it.
5. Commit the files to `main`.
6. Go to **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**. Click **Save**.
8. When publishing finishes, the Pages settings show your live site URL.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: projects and home page
- `about.html`: portrait, biography, resume preview and download
- `style.css`: shared styling
- `assets/`: all images and PDFs
- `.nojekyll`: serves the static files without Jekyll processing

Navigation uses relative paths, so it works both at a domain root and under a GitHub repository path. Fonts are requested from Google Fonts, with system-font fallbacks.

To update the site, edit or replace files in the publishing branch. The asset files include the resume exactly as provided.
