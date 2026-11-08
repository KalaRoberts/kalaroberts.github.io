# Kala Roberts — Portfolio & Professional Site

A responsive, zero-dependency single-page personal portfolio hosted on GitHub Pages.

🔗 **Live site:** https://kalaroberts.github.io  
🔗 **LinkedIn:** [My LinkedIn Profile](https://linkedin.com/in/kalaroberts)  
🔗 **Article:** [Lessons Learned Working at Amazon](https://www.linkedin.com/pulse/lessons-learned-working-amazon-14-years-kala-roberts/)

## Overview

A clean, one-page site featuring:

- **Intro** — Professional summary and leadership philosophy, alongside a headshot
- **Career Highlights** — A scannable 2x2 grid of core areas of focus
- **Experience** — 17 years of product strategy across multiple Amazon teams
- **Projects** — Highlight reel of publicly released projects I’ve worked on
- **Recommendations** — Endorsements from colleagues
- **Hobbies** — List of hobbies including an interactive personal art gallery

## Technical Architecture & Built With

- **Core:** Pure HTML5, CSS3, and vanilla JavaScript (zero build steps, frameworks, or external dependencies)
- **Visuals:** Custom animated particle-network background via HTML canvas
- **Performance:** Fully responsive design, dark theme support, reduced-motion compliance, and optimized media assets
- **Analytics:** Integrated via Google Tag Manager (`GTM-N496CKG9`)
- **SEO & Search:** Semantic HTML landmarks (`<main>`, single `<h1>`, clean heading hierarchy), canonical URL, descriptive meta tags, Open Graph / social preview tags (with large image-preview hints for rich search thumbnails), JSON-LD `Person` structured data, a `sitemap.xml` + `robots.txt`, and Google Search Console verification for indexing

## Repository Structure

```text
index.html                  Single-file core architecture (HTML + CSS + JS inline)
kala-headshot.jpg           Hero professional headshot
kala-highlights.mp4         Projects and product highlight reel video
kala-highlights-poster.jpg  Optimized video poster frame
art-*.jpg                   Interactive gallery artwork assets
favicon.ico / *.png         Site icons
sitemap.xml                 Sitemap for search engine discovery
robots.txt                  Crawler directives (allows all, points to sitemap)
```

## Local preview

Open `index.html` in any web browser — no server needed.

---

© Kala Roberts
