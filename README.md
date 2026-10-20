# Personal GitHub Pages

A responsive, bilingual personal homepage built with plain HTML, CSS, and JavaScript. There is no build step or package installation.

## Personalize

Edit `index.html` to replace the name, introduction, project descriptions, notes, and email address. The sample text is placeholder content. Update the GitHub profile link if your account URL differs. Adjust the palette and layout in `styles.css` as needed.

## Preview

Open `index.html` in a browser, or serve this directory with any static file server.

## Publish

1. Push the repository to GitHub's `main` branch.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` deploys the site on each push to `main`. You can also start it from the **Actions** tab with **Run workflow**.

For a user site, the repository name should be `<your-github-username>.github.io`. Once the workflow completes, GitHub Pages will show the published URL in the deployment environment and Pages settings.