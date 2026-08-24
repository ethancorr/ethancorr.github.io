# Ethan Corr — Site

## What's here
- `index.html` — Home
- `research.html` — Research
- `cv.html` — CV (with a "View / Download PDF" button)
- `speaking.html` — Speaking & Outreach
- `css/styles.css` — all styling (one shared stylesheet)
- `js/main.js` — mobile nav toggle
- `images/headshot.jpg` — your photo (already wired into the Home page)
- `files/ethan-corr-cv.pdf` — your CV (already wired into the CV page and its footer)

## Folder structure matters
Keep everything in one top-level folder exactly as it is in this zip — `index.html`, `research.html`, `cv.html`, and `speaking.html` all need to sit *next to* the `css/`, `js/`, `images/`, and `files/` folders, not inside any of them. If you extract this zip and don't move anything around, it'll work as-is.

## If you swap the CV or photo later
- To replace the photo: overwrite `images/headshot.jpg` with a new file of the same name, or update the `src="images/headshot.jpg"` path in `index.html` if you rename it.
- To replace the CV: overwrite `files/ethan-corr-cv.pdf` with a new file of the same name, or update the two `href="files/ethan-corr-cv.pdf"` links in `cv.html` if you rename it.

## Content notes
- I kept research-page language high-level on purpose (no unpublished technical detail), but did include your dissertation title and both NMDSI grants since those are already on your CV.
- The site avoids any "looking for a faculty job" framing, per your note — CTAs talk about collaboration, consulting, and speaking rather than academic positions.
- The CV page mirrors your PDF closely (education, all three Clarios roles, teaching, honors, mentorship, presentations, patents, skills) — check it over for anything you'd rather trim for a public web page vs. what you'd send directly to a search committee.
- The Speaking page topics and "recent talks" now reflect your actual presentations (Battery Bot, STEM outreach, supply chain, etc.) rather than generic placeholders.

## Deploying to GitHub Pages
1. Replace your old `index.html` and add all these files/folders to your repo, keeping the structure above.
2. Commit and push.
3. In your repo Settings → Pages, confirm the source branch/folder (usually `main`, root).
4. Your site will be live at `https://<yourusername>.github.io/<repo-name>/`.
