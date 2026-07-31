# Arzoo Shamoon — Portfolio Website

A single self-contained `index.html` file — no build step, no dependencies to install.

## How to launch it on GitHub Pages

1. Create a new repository on GitHub. If you name it `your-username.github.io`, your site
   will be live at `https://your-username.github.io`. Any other name works too — it'll just
   live at `https://your-username.github.io/repo-name`.
2. Upload `index.html` to the repository (drag-and-drop on github.com works fine, or use git).
3. Go to the repo's **Settings → Pages**.
4. Under **Source**, choose the `main` branch and `/ (root)` folder, then **Save**.
5. Wait a minute or two — GitHub will give you the live URL at the top of that page.

That's it. Any time you edit `index.html` and push the change, the live site updates automatically.

## Before you publish — things to personalize

I filled this in from what's publicly findable about you (LinkedIn, Google Scholar, ORCID,
your publications), but a few things need your input:

- **Photo** — the "About" section has a placeholder box. Replace it with:
  `<img src="photo.jpg" alt="Arzoo Shamoon">` (upload `photo.jpg` to the repo alongside `index.html`).
- **Email** — currently `your.email@uk-essen.de` as a placeholder (search for `mailto:` in the file).
- **Skills/tools list** — I listed common tools for your research areas (Seurat/Scanpy, Python, R, etc.)
  based on your stated interests, but you should edit these to match your actual day-to-day stack.
- **Publications** — I included the three peer-reviewed papers I could verify online. If you have
  more (or preprints, posters, talks), add them following the same `<div class="pub">` pattern.
- Double check the Google Scholar and LinkedIn links still point to the right profile.

## Structure

Everything — HTML, CSS, and the small year-stamp script — lives in `index.html`. Section IDs
(`#about`, `#research`, `#experience`, `#publications`, `#contact`) match the nav links, so you
can reorder or rename sections without breaking navigation, as long as the `href`/`id` pairs stay in sync.
