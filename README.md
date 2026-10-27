# Tianhao Qian — minimalist academic website

A **simple static academic homepage** for GitHub Pages, based on the academic CV dated October 19, 2026. No build step, JavaScript framework, hosting subscription, analytics, trackers, remote fonts, or third-party dependencies.

## Files

- `index.html` — entire website, including embedded CSS
- `assets/Tianhao_Qian_CV.pdf` — CV linked in the header
- `.nojekyll` — tell GitHub Pages not to process the folder with Jekyll

## Publish using GitHub Pages (no terminal needed)

1. Sign in to https://github.com/new .
2. Create a **Public** repository. For a personal-root URL, name the repository **`YOUR-GITHUB-USERNAME.github.io`**, replacing the placeholder with your exact account name. Alternatively, use any repository name, e.g. `academic-homepage`.
3. Open the new repository, choose **Add file → Upload files**, and upload `index.html`, `.nojekyll`, `assets/Tianhao_Qian_CV.pdf` and this `README.md`, keeping `index.html` in the repository root. If the browser does not retain the `assets/` folder structure, add that directory separately, or upload via Git.
4. Commit the upload to the `main` branch.
5. Navigate to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, `main`, `/(root)`, then **Save**.
6. Click **Visit site** in the same Pages settings page after publication.

Site address:
- `https://YOUR-GITHUB-USERNAME.github.io/` if your repository is named `YOUR-GITHUB-USERNAME.github.io`.
- `https://YOUR-GITHUB-USERNAME.github.io/academic-homepage/` if your repository is named `academic-homepage`.

## Local preview

Open `index.html` in your browser. The `CV (PDF)` link opens the PDF stored locally in `assets`.

## Editing

Edit the text inside `index.html` with any text editor. The site uses a single CSS block inside `<head>` for colors and typography. Re-upload the edited file to the repository to update your Pages site.

## Publication links and status

Links to the three current first-author manuscripts have been checked against their arXiv titles (October 27, 2026):

- PAC-CF — https://arxiv.org/abs/2604.14345
- Relative Kinetic Utility — https://arxiv.org/abs/2605.09008
- Storage Is Not Strategy — https://arxiv.org/abs/2609.37858

**Under review** does not mean accepted. The website differentiates manuscripts, preprints, and the accepted 2024 conference paper.
