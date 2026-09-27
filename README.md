# Sandeep B — Portfolio Site

Static HTML/CSS rebuild of your Google Site, ready for GitHub Pages.

## What's inside
- `index.html` (this is now the About me page — the standalone Home page was removed, so the site opens directly on About me), `research.html`, `resume.html`, `gallery.html`, `technical-hobbies.html`, `connect.html` — the main pages
- `gallery/iit-kanpur-lab.html`, `gallery/iit-bombay-lab.html`, `gallery/sport-activities.html` — gallery sub-pages
- `style.css` — shared stylesheet
- `images/`, `images/gallery/`, `images/hobbies/`, `images/research/` — empty folders where your photos go
- `files/` — put `Sandeep_Resume_Master.pdf` here

## Before you publish
1. **Add your images.** The original site's photos live on Google's private CDN and can't be reliably copied over, so the pages reference placeholder filenames (e.g. `images/gallery/kanpur-1.jpg`). Save your photos from the live Google Site (right-click → Save image as) into the matching folders using those filenames, or edit the `src=` paths in the HTML to match whatever you save.
2. **Add your resume PDF** to the `files/` folder, named `Sandeep_Resume_Master.pdf` (or update the link in `resume.html`).

## Publish to GitHub Pages
1. Create a repo on GitHub (e.g. `sandeepportfolio` or `<username>.github.io`).
2. Upload all these files/folders, keeping the same structure.
3. Go to Settings → Pages, select your branch and `/root`, save.
4. Your site will be live at `https://<username>.github.io/<repo-name>/` (or `https://<username>.github.io/` if you named the repo that way).
