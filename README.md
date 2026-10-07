# zekiduman.github.io

Live at https://zekiduman.github.io

Personal website of Zeki Duman: a single static page (no build step), hosted on GitHub Pages.

## Files
- `index.html` — the whole site (HTML + CSS inline)
- `assets/Zeki_Duman_CV.pdf` — the CV linked from the "CV" buttons
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish on GitHub Pages
1. Create a new **public** repository named exactly `<your-github-username>.github.io`.
2. Upload everything in this folder (including `.nojekyll` and the `assets` folder):
   *Add file → Upload files*, drag the contents in, then *Commit changes*.
3. Go to **Settings → Pages**, set *Source* to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-github-username>.github.io`.

## Common edits
- **Swap the CV** (e.g. the data-science version): replace `assets/Zeki_Duman_CV.pdf` with a file of the same name.
- **Add a photo**: put `assets/photo.jpg` in the folder and add `<img src="assets/photo.jpg" alt="Zeki Duman">` where you want it.
- **Add a paper link**: in the Publications section, add `<a href="URL" target="_blank" rel="noopener">Paper ↗</a>` inside that paper's `tags` div.
- **Add GitHub**: copy one of the links in the `social` div near the top and point it to your GitHub profile.
