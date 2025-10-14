# E‑Portfolio (GitHub Pages)

A simple personal e‑portfolio hosted on GitHub Pages.

## Structure
- `index.html` — Welcome
- `about.html` — About
- `experience.html` — Experience
- `projects.html` — Projects (includes link to "Company Website" repo)
- `contact.html` — Contact (optionally link to résumé)
- `assets/css/style.css`, `assets/js/main.js`

## Local preview
Open any HTML file in your browser or use a simple server:
```bash
python -m http.server 8000
```

## Publish to GitHub Pages
1. Create a repository named `USERNAME.github.io`.
2. Push these files to the `main` branch.
3. In **Settings → Pages**, select the `main` branch as the source.
4. Wait ~1–2 minutes, then visit `https://USERNAME.github.io`.
