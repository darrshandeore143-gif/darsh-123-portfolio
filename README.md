# Darshan Deore — Cloud & DevOps Portfolio

A responsive portfolio built with plain HTML, CSS, and JavaScript. No build tools or package installation required.

## Included files

- `index.html` — all portfolio sections and project details
- `style.css` — responsive design, animations, and mobile layouts
- `script.js` — mobile navigation, scroll reveal, active section state, current year
- `assets/darshan-profile.png` — profile photo supplied with the request
- `assets/Darshan-Deore-Resume.pdf` — resume PDF used by the Download Resume button

## Run locally

1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. For a local server, run `python -m http.server 8000` from this folder, then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Sign in to GitHub and create a new repository (for example, `darshan-portfolio`).
2. Upload the contents of this folder to the repository root. Make sure `index.html` is at the root, not inside an extra nested folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Wait for GitHub Pages to finish publishing. The site URL will appear in the Pages settings, usually `https://YOUR-USERNAME.github.io/darshan-portfolio/`.

## Before publishing

- The portfolio uses the LinkedIn URL and email address listed in the supplied resume.
- No GitHub profile URL was present in the resume, so this site does not invent one or show a fabricated GitHub link. Add a real GitHub profile or repository link once you provide it.
- Project descriptions and percentage outcomes are reproduced from the resume. Make sure the metrics accurately reflect your work before using them in job applications.
- Google Fonts load from the internet; system fallback fonts are provided if offline.
- The email buttons open the visitor's email app using `mailto:`. They do not send email automatically.
- The resume PDF is included locally so the Download Resume button works without an external link.
