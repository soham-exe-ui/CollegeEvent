# IEM Events — CSE (AIML)

A responsive, single-page college events website built with plain HTML, CSS, and JavaScript. No npm install, bundler, or build step is required.

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload the **contents of this folder** (not the enclosing ZIP folder) so `index.html` is at the repository root.
3. Confirm the paths remain exactly `css/style.css`, `js/script.js`, and `images/...`.
4. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for the Pages deployment to finish and open the URL shown in Settings → Pages.

## Project structure
```
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── logo.png
│   └── event photos/assets
├── README.md
└── REPORT.md
```

## Why CSS/JavaScript may fail on GitHub
- Keep filenames and capitalization exact (`style.css` is different from `Style.css` on GitHub's Linux servers).
- Keep `css/` and `js/` beside `index.html`; do not upload only `index.html`.
- Use relative paths such as `./css/style.css` and `./js/script.js`.
- If deploying from a repository subfolder, configure Pages for that folder or move the site files to the selected publishing root.
- Check DevTools → Network/Console for 404 errors.

## Features
- Responsive layout for desktop, tablet, and mobile
- Event list generated from a JavaScript data array, category filters, and registration dropdown
- Event countdown and Kolkata clock
- Light/dark theme toggle
- Client-side validation for registration and feedback forms
- Mobile navigation

## Important note
Forms currently demonstrate client-side validation only. They do not save submissions or send emails without a backend or a form service. Update sample event details and replace illustrative event photos with approved official photos before publishing.
