# Kala Roberts — Portfolio & Professional Site

A responsive, zero-dependency single-page personal portfolio hosted on GitHub Pages.

🔗 **Live site:** https://kalaroberts.github.io  
🔗 **LinkedIn:** [kalaroberts](https://linkedin.com/in/kalaroberts)  
🔗 **Article:** [Lessons Learned Working at Amazon](https://www.linkedin.com/pulse/lessons-learned-working-amazon-14-years-kala-roberts/)

## Overview

A clean, one-page site featuring:

- **Intro** — Professional summary and leadership philosophy, alongside a headshot
- **Career Highlights** — A scannable 2×2 grid of core areas of focus
- **Projects & Ventures** — Launched work and partner case studies, each a banner/modal card: a built-and-deployed web platform, plus telecom, AWS, and seller partnership spotlights linking to announcements and testimonials
- **Experience** — 17 years of product strategy across multiple Amazon teams, with expandable role details
- **Recommendations** — Endorsements from colleagues
- **Perspectives** — A written article and an embedded highlight-reel video (opened in a modal)
- **Hobbies** — Personal interests, including an interactive art gallery

## Technical Architecture & Built With

- **Core:** Pure HTML5, CSS3, and vanilla JavaScript — zero build steps, frameworks, or external dependencies
- **Visuals:** Custom animated particle-network background via HTML canvas
- **Accessibility:** Semantic HTML landmarks, keyboard-focusable cards with visible focus rings, `aria-label`s on icon links and modals, native `<dialog>` modals (video reel, testimonials, and art lightbox) and `<details>`/`<summary>` collapsible cards, `prefers-reduced-motion` compliance, and descriptive `alt` text throughout
- **Performance:** Fully responsive (mobile-first) design, dark theme, lazy-loaded imagery, on-demand video loading, and optimized media assets
- **Analytics:** Google Analytics 4 via the Google tag (gtag.js), plus custom click-event tracking for project cards, art gallery views, Experience expansions, video plays/downloads, nav links, and outbound links
- **SEO & Search:** Semantic HTML landmarks (`<main>`, single `<h1>`, clean heading hierarchy), canonical URL, descriptive meta tags, Open Graph / Twitter social preview tags with a custom 1200×630 share card and `summary_large_image` card type (plus large image-preview hints for rich search thumbnails), JSON-LD `Person` structured data, a `sitemap.xml` + `robots.txt`, `llms.txt` + `llms-full.txt` summaries for AI crawlers, and Google Search Console verification for indexing

## Repository Structure

```text
index.html                       Single-file core architecture (HTML + CSS + JS inline)
kala-headshot.jpg                Hero professional headshot
og-card.jpg                      1200×630 Open Graph / Twitter social share card
kala-highlights.mp4              Amazon project highlights reel (opens in a modal)
kala-highlights-poster.jpg       Poster frame for the reel video player
kala-highlights-thumb.jpg        Banner thumbnail for the highlights reel card
leadership-principles-thumb.jpg  Banner thumbnail for the Writing & Reflections card
aws-testimonial-thumb.jpg        Thumbnail for the AWS partner case-study modal
seller-testimonial-thumb.jpg     Thumbnail for the seller impact testimonial modal
telecom-partner-thumb.jpg        Thumbnail for the telecom partner announcement modal
art-*.jpg                        Interactive gallery artwork assets
favicon.ico / *.png              Site icons
sitemap.xml                      Sitemap for search engine discovery
robots.txt                       Crawler directives (allows all, points to sitemap)
llms.txt                         Structured site summary for AI crawlers / LLMs
llms-full.txt                    Expanded full-content version for AI crawlers / LLMs
```

## Local Preview

Open `index.html` in any web browser — no server or build step needed.

## Deployment

Hosted on **GitHub Pages**, served directly from the repository root on the `main` branch. Any push to `main` automatically redeploys the live site within a minute or two — no build pipeline required.

## License

Site code is free to reference. All written content, images, and artwork © Kala Roberts.
