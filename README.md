# Awais Khan — Academic Site

A static personal/academic site (About · Publications · Projects · Repositories · CV), no build step required.

## Deploy on GitHub Pages

1. Create a new repo named `AwaisKhan5647.github.io` (this exact name makes it your profile's root site — `https://AwaisKhan5647.github.io`). If you'd rather keep it as a project page, any repo name works and it'll live at `https://AwaisKhan5647.github.io/<repo-name>/`.
2. Push all files in this folder (`index.html`, `publications.html`, `projects.html`, `repositories.html`, `cv.html`, and the `assets/` folder) to the repo root.
3. In the repo: **Settings → Pages → Source → Deploy from branch → `main` / `(root)`** → Save.
4. Your site goes live at the URL GitHub shows there within a minute or two.
5. Add that URL to your GitHub profile, Google Scholar, and LinkedIn "Contact info" / featured link.

## Editing

- All text lives directly in the `.html` files — no templating, just edit and re-push.
- Colors/fonts/spacing are all in `assets/css/style.css` (see the token comment at the top).
- Swap the photo at `assets/img/profile.jpg` and the CV at `assets/pdf/Awais_Khan_CV.pdf` any time — same filenames, so no link updates needed.

## Known placeholders to double-check

- **INTERSPEECH paper title** — listed as "Dual-Branch Architecture for Audio Deepfake Detection" based on what you described; swap in the exact accepted title in `publications.html` and `index.html` once you have it.
- **BMVC** — mentioned as a venue to highlight but not yet confirmed with a title/status, so it's left off. Add it to the `venue-grid` in `index.html` and as a new `.pub` entry in `publications.html` when ready.
