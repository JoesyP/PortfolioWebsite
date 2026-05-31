# Jose — Portfolio

A personal portfolio website. Built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Before you publish

Open the files and replace these placeholders:

- **`YOUR-USERNAME`** → your GitHub username (in `index.html`, appears twice)
- **`YOUR-PROFILE`** → your LinkedIn profile handle (in `index.html`)

Your email (`calpules1@icloud.com`) is already set.

## Run locally

Just open `index.html` in a browser. That's it.

Or serve it with Python:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy free with GitHub Pages

1. Create a new GitHub repository named **`YOUR-USERNAME.github.io`**
   (use your real username — this exact name makes it your main site).
2. Upload `index.html`, `styles.css`, `script.js`, and this `README.md`.
3. Go to **Settings → Pages**, set the source to the `main` branch, root folder.
4. Wait ~1 minute. Your site is live at **`https://YOUR-USERNAME.github.io`**.

## Files

```
index.html    — page structure and content
styles.css    — all styling (responsive, dark theme)
script.js     — scroll animations + mobile menu
```

## Edit your content

All text lives in `index.html`. To add a project, copy one `<div class="project">…</div>`
block in the Work section and update the title, description, and tech stack tags.
