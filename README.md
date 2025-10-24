## Real Food Solution – Static Website

This is a fully static site (HTML/CSS/JS). You can serve it from any static host. The recommended workflow is GitHub (+ Vercel) for CI/CD and hosting.

### Local usage
- Open `index.html` directly in a browser, or serve the folder with any static server.

### Deploy via GitHub + Vercel
1. Create a GitHub repository and push the code on branch `main`.
2. In Vercel, click “New Project” → “Import Git Repository” and pick the repo.
3. Framework preset: “Other”. No build command. Output directory: project root (contains `index.html`).
4. Deploy. Vercel will serve the site from its CDN.

### Custom domain (optional)
- Point your domain (e.g. `realfoodsolution.se`) to Vercel by adding it in the project’s Domains settings and following the DNS instructions.

### Notes
- Error pages: `404.html` is included and will be used automatically by Vercel.
- All assets live in `css/`, `images/`, `fonts/`, and `js/`.


