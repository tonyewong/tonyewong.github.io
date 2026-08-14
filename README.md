# Tony Wong — personal academic website

This repository publishes directly to [tonyewong.github.io](https://tonyewong.github.io/) with GitHub Pages. It is intentionally a plain static site: no build step, package manager, or site generator is required.

## Editing the site

- `index.html` — homepage, research overview, projects, and contact information
- `publications.html` — publication list
- `students.html` — current group, student-authored work, and alumni
- `teaching.html` — courses and teaching history
- `consulting.html` — consulting overview and contact prompt
- `examart.html` — student exam-art gallery
- `data.html` — links to open data and code
- `style.css` — the complete visual system and responsive layout
- `pictures/` and `assets/` — images, the CV, and research files

Internal links are relative, so the same files work locally and on GitHub Pages. To preview locally, run a simple web server in this directory and open `index.html` through it.

## Adding a student publication

Add the complete citation to `publications.html`, keeping student or alumni authors in `<b>` tags. For a highlighted item on the Students page, duplicate one of the `publication-card` articles in the `student-work` section and change its year, venue, title, authors, and link.

## Design notes

The site uses only local CSS and system fonts. The palette, spacing, typography, cards, and responsive breakpoints are defined near the top of `style.css`. Avoid adding additional CSS frameworks unless the site is deliberately migrated to a build system.
