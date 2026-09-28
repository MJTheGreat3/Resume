# Resume

Source for a personal portfolio / resume website — a static site rendering an online resume, plus a downloadable CV.

## Structure

```
index.html          # main page (title: "Resume - Matthew Joseph")
css/styles.css
js/scripts.js
assets/
  CV.pdf             # downloadable resume/CV
  img/               # icons (language/tool logos, profile photo, favicon, etc.)
```

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript
- Bootstrap
- Font Awesome icons

## Page sections

The page is organized into the following sections (per its nav bar): About, Projects, Education, Skills, Coursework, and Awards & Certifications.

## Running locally

Static site, no build step:

```bash
open index.html
```

(or serve with any static file server, e.g. `python3 -m http.server`)

## Status

Content (project list, education, skills, etc.) lives in `index.html`/`assets/CV.pdf` and may lag behind the author's actual current resume — check `assets/CV.pdf` for the most up-to-date version.
