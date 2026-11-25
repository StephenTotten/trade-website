# The Trade

A responsive static landing page for **The Trade**, an AleHouse Studios psychological thriller series directed by Alexander Griffith.

## Local preview

Open `index.html` in a browser. The site uses plain HTML and CSS and has no build step or runtime dependencies.

## Deploy with GitHub Pages

The images used by the site are stored in `assets/images/`. The workflow in `.github/workflows/deploy.yml` deploys the site whenever changes are pushed to `main`, or when manually started from the Actions tab.

1. In the repository settings, open **Pages**.
2. Set the build and deployment source to **GitHub Actions**.
3. Push to `main` or run **Deploy static site to GitHub Pages** from the Actions tab.

The workflow publishes the repository root, including the supplied visual-reference images. Add an approved trailer and public contact details when they are available; the page currently marks both as coming soon rather than using unverified information.
