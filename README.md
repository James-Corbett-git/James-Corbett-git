# Publishing this site with GitHub Pages

1. **Create a repo.** On GitHub, click **New repository**. Name it whatever you like —
   if you name it exactly `yourusername.github.io`, your site will be live at the root
   domain (`https://yourusername.github.io`). Any other name works too, just at
   `https://yourusername.github.io/repo-name`.

2. **Upload `index.html`.** In the new repo, click **Add file → Upload files**, drag in
   `index.html`, and commit it to the `main` branch.

3. **Turn on Pages.** Go to **Settings → Pages**. Under "Build and deployment," set
   **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.

4. **Wait ~1 minute**, then refresh that Pages settings page — it'll show your live URL.

## Before you publish

Two placeholders in `index.html` need your real info:

- **Contact section** (near the bottom): swap `your.email@example.com`,
  `github.com/yourusername`, and `linkedin.com/in/yourusername` for your actual links.
- **CV download button**: it currently links to `resume.pdf`, which doesn't exist yet.
  Either add a `resume.pdf` file to the repo (same folder as `index.html`), or remove/edit
  that button if you'd rather not offer a download.

## Making changes later

Edit `index.html` directly on GitHub (pencil icon) or clone the repo locally — any push
to `main` updates the live site within a minute or two, no rebuild step needed.
