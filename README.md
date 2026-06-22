# Yue Dai Personal GitHub Pages Site

This folder contains a static personal research webpage for GitHub Pages.

## 1. Files to Upload

Upload the following files and folders to the root of your GitHub Pages repository:

- `index.html`
- `styles.css`
- `.nojekyll`
- `assets/`
- `publications/`

## 2. Create the GitHub Pages Repository

1. Log in to GitHub.
2. Click `+` in the top-right corner and choose `New repository`.
3. Name the repository exactly:

   `your-github-id.github.io`

4. Set it to `Public`.
5. Create the repository.

After publication, the homepage URL will be:

`https://your-github-id.github.io`

## 3. Upload the Webpage Files

1. Open the new repository.
2. Click `Add file -> Upload files`.
3. Drag in:

   - `index.html`
   - `styles.css`
   - `.nojekyll`
   - the `assets/` folder
   - the `publications/` folder

4. Click `Commit changes`.

## 4. Enable GitHub Pages

1. Open the repository.
2. Go to `Settings -> Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select:

   - Branch: `main`
   - Folder: `/root`

5. Save.
6. Wait for GitHub to finish deployment.

## 5. Update Repository Links

The webpage currently uses placeholder links such as:

- `https://github.com/your-github-id/central-bank-fintech-briefings`
- `https://github.com/your-github-id/economic-nowcasting`
- `https://github.com/your-github-id/finllm-research-toolkit`
- `https://github.com/your-github-id/hft-strategy-market-impact`

After creating these repositories, replace every `your-github-id` in `index.html` with your real GitHub username.

## 6. Publication Links

PDFs are stored in `publications/`. The webpage links to them with relative paths such as:

`./publications/book-fintech-and-financial-risk-in-china.pdf`

The links will work locally and on GitHub Pages if the `publications/` folder is uploaded.

Only upload PDFs that you are allowed to share publicly.
