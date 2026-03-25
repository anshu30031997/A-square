# Publish the gym site on GitHub Pages

This repo includes [`index.html`](../index.html) at the project root so GitHub Pages can serve the A Square Fitness Club landing page.

## Steps

1. **Create a GitHub repository** (e.g. `a-square-gym` or use this repo) and push your branch:

   ```bash
   git add index.html docs/GITHUB_PAGES.md
   git commit -m "Add GitHub Pages landing page"
   git remote add origin https://github.com/<YOUR_USER>/<YOUR_REPO>.git
   git push -u origin main
   ```

2. **Enable Pages**: On GitHub open **Settings → Pages**.

3. Under **Build and deployment → Source**, choose **Deploy from a branch**.

4. Select branch **`main`** (or your default branch) and folder **`/ (root)`**, then **Save**.

5. After a minute or two, the site is live at:

   **`https://<YOUR_USER>.github.io/<YOUR_REPO>/`**

   Use that exact **HTTPS** URL everywhere (including QR codes).

6. **QR code**: In any QR generator, paste only that URL, export PNG/SVG, and test the scan on a phone.

## Notes

- The page is a single self-contained HTML file (large because images are embedded). Stay within GitHub’s repository size limits.
- For a **custom domain**, add it under **Settings → Pages** and configure DNS at your registrar.
- If you use a **project site** (`username.github.io/repo-name`), the path is `/repo-name/`; for a **user site** (`username.github.io`), the repo must be named `username.github.io`.
