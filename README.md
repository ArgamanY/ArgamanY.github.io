# Yiftach Argaman — Personal Website

A simple, clean academic website with four pages: Home, Projects, Publications, Contact. Plain HTML and CSS, no build step, no framework.

## Files

- `index.html` — home / about
- `projects.html` — ongoing projects
- `publications.html` — publication list
- `contact.html` — email and affiliation
- `styles.css` — all styling, shared across pages
- `profile.svg` — placeholder profile image (replace with your photo, see below)

## Add your photo

Two options:

**Option A — keep `profile.svg`:** drop a square photo into this folder, name it `profile.jpg`, then in `index.html` change `src="profile.svg"` to `src="profile.jpg"`.

**Option B — replace the SVG:** delete `profile.svg`, save your photo as `profile.svg` (or any name) at roughly square dimensions (e.g., 600×600 px), and update the `<img>` tag in `index.html` to point to it.

If you skip this, the page still works — you'll see a soft gray circle with "YA".

## Put the site online (GitHub Pages, free)

1. Create a free account at [github.com](https://github.com) if you don't have one.
2. Create a new repository named exactly `<your-username>.github.io` — for example `yiftachargaman.github.io`. Make it **Public**.
3. Click **Add file → Upload files**, drag in everything from this folder, and commit.
4. Wait ~1 minute, then visit `https://<your-username>.github.io`. Your site is live.

That's the whole setup. No server, no domain purchase required.

If you want a custom domain later (e.g., `yiftachargaman.com`), you can add it in the repo's Settings → Pages → Custom domain.

## Updating the site every couple of weeks

Each page is a plain HTML file. To update:

- **Add a publication** → open `publications.html`, copy any existing `<li>...</li>` block, paste it at the top of the list, edit the citation and the links.
- **Add or edit a project** → open `projects.html`, copy a `<section class="project">` block, paste it where you want, edit the title and one-line description.
- **Update the home text** → open `index.html` and edit the paragraphs inside `<main>`.
- **Style tweaks** → edit `styles.css`. The accent color is the `--accent` variable at the top.

After editing, push the changed files to GitHub (drag-and-drop on the repo page works fine). GitHub Pages republishes within about a minute.

## Preview locally

Just double-click `index.html` — it opens in your browser. No server needed.
