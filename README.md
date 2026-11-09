# Surjith Kumar JK — Portfolio

Static portfolio website for an AI/ML engineer (computer vision, image processing, geospatial systems). Plain HTML, CSS and a small vanilla JS file, so there is no build step and no dependencies.

## Structure

```
.
├── index.html           Home
├── profile.html         Profile and technical background
├── projects.html        Independent projects (placeholder for now)
├── case-studies.html    Six sanitized organizational case studies
├── expertise.html       Skills and working principles
├── contact.html         Email, LinkedIn, GitHub
├── 404.html             Not-found page
├── sitemap.xml / robots.txt
├── .nojekyll            Tells GitHub Pages to serve files as-is
└── assets/
    ├── styles.css
    ├── script.js        Mobile menu and footer year
    ├── favicon.svg
    └── images/
        └── SurjithKumar-JK.jpg   <- add your portrait here (4:5 ratio, ~640x800)
```

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository go to **Settings → Pages**.
3. Set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. The site will be live at `https://<username>.github.io/` (for a repo named `<username>.github.io`).

If you use a different repository name or a custom domain, update `BASE_URL`-style references in the `<link rel="canonical">`, `og:url` tags, `sitemap.xml` and `robots.txt` (search for `surjithkumar-jk.github.io`).

## Notes

- If `assets/images/SurjithKumar-JK.jpg` is missing, the pages show an "SK" monogram instead of a broken image.
- Case studies are intentionally high-level; do not add proprietary details without approval.
