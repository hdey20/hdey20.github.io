# Haimabati Dey — Research Portfolio (GitHub Pages)

A responsive, white-background academic research website inspired by the information hierarchy of [Dakshita Khurana's homepage](https://dakshitakhurana.com/). This is an original implementation: it does not copy her text, source code, branding, or images. The visual language uses restrained blue/cyan accents and original locally authored SVG scientific illustrations.

## Included pages

- `index.html` — academic homepage, profile, selected research, contact links
- `research.html` — six research themes
- `projects.html` — filterable research and engineering project summaries
- `publications.html` — selected conference proceedings and poster presentations from the supplied CV
- `experience.html` — research, industry, and education timeline
- `teaching.html` — teaching, mentoring, technical skills, and awards
- `contact.html` — email and professional links
- `assets/css/style.css`, `assets/js/main.js`, `assets/images/` — styles, navigation/filter behavior, and original SVG illustrations
- `assets/downloads/Haimabati-Dey-CV-uploaded.pdf` — the PDF supplied in this conversation

## Deploy to GitHub Pages

1. Download and unzip this archive.
2. Create a repository named **`haimabati-dey.github.io`** under the GitHub account that should own the website. If you use a different account, the repository name must match that account's username.
3. Upload the *contents* of this folder to the repository root (so `index.html` is at the root, not inside another nested folder).
4. Commit to the `main` branch.
5. In GitHub, open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for the Pages deployment, then visit `https://haimabati-dey.github.io/`.

No Node.js, Jekyll, build command, or paid hosting is required. You can preview locally by opening `index.html` in a browser.

## Customize before publishing

Search the HTML files for the profile links and update them if needed. Current profile links use:

- Email: `deyh2023@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/haimabati2022/`
- GitHub: `https://github.com/haimabati-dey`

Replace `assets/downloads/Haimabati-Dey-CV-uploaded.pdf` with an up-to-date public CV if you have a revised PDF. If you change its filename, update the CV link in `index.html`.

## Important CV consistency note

The supplied LaTeX CV contains an additional UT Dallas Graduate Research Assistant appointment (August 2024–May 2025) and expanded medical-AI/bio-signal project details that do not appear in the supplied four-page PDF. The website uses the expanded LaTeX CV for its experience and project content, while the download button currently serves the supplied PDF unchanged. Please compile/update the PDF before making the site public if you want the downloadable CV to match the website.

## Content integrity

- The selected conference proceedings and poster presentations are reproduced from the supplied CV; this is not represented as a complete journal-publication list.
- Project summaries combine the supplied CV and prior project discussions. Research directions are labelled as such where the source material does not establish a completed prototype or measured result.
- No GitHub repository URLs are invented for individual projects. Add verified repository links when ready.
- The site does not include a phone number to reduce unwanted public exposure; add it only if you deliberately want it public.

## Editing guide

Edit the page content directly in the `.html` files. Change colors, typography, and layout in `assets/css/style.css`. The project filter buttons use each card's `data-category` attribute and are powered by `assets/js/main.js`. Replace or edit the SVGs in `assets/images/` to evolve the original scientific illustrations.
