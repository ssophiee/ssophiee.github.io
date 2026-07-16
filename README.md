# ssophiee.github.io

Personal academic website — a single static `index.html` with inline CSS and no JS/build step.

## Editing

- All content lives in `index.html`. Search for `[BRACKETED PLACEHOLDERS]` and replace them.
- Replace `assets/img/profile.jpg` with a real photo (square crop works best).
- Replace `assets/img/paper1.jpg` … `paper3.jpg` with paper thumbnails (~640×480).
- Add your CV as `assets/cv.pdf`.
- Preview locally by opening `index.html` in a browser, or run
  `python3 -m http.server` and visit http://localhost:8000.

## Publishing on GitHub Pages

1. Create a repo named exactly `ssophiee.github.io` on GitHub (must match your username).
2. Push this folder to its `main` branch.
3. On GitHub: **Settings → Pages → Build and deployment**, set Source to
   **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. The site goes live at https://ssophiee.github.io within a minute or two.
