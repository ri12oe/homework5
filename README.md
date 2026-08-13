# Trail & Timber

A responsive marketing site for a fictional outdoor adventure guiding company, built as a homework project (HTML + Sass/CSS).

**Live site:** https://in-info-web4.luddy.indianapolis.iu.edu/~maespin/homework5/

## Overview

Trail & Timber is a single-page site for an outdoor guiding company offering mountain trekking, forest camping, and river expedition trips. The page is built around a full-width hero, a set of content sections, and a footer, and is styled with a component-based Sass architecture.

## Sections

- **Hero** – Full-bleed background image, headline, CTA buttons, and stat highlights (trips led, guests served, years of experience, safety record).
- **Featured Adventures** – Card grid showcasing the three core trip types (Mountain Trekking, Forest Camping, River Expeditions), each with duration, difficulty, and a "Learn More" link.
- **Services** – Icon-based grid covering Guided Tours, Equipment Rentals, Survival Training, and Group Events.
- **Why Us / About** – Company story plus a checklist of trust signals (certified guides, small group sizes, safety protocols, gear brands, Leave No Trace certification, 24/7 support).
- **Testimonials** – Star-rated guest reviews with photos, names, trip type, and date.
- **Call to Action** – Secondary booking banner.
- **Footer** – Contact info, sitemap-style link columns (Company, Adventures, Resources), and an email signup form.

## Tech Stack

- **HTML5** – Semantic structure (`nav`, `section`, `footer`, etc.)
- **Sass (SCSS)** – Flat `scss/` folder architecture using `@import`, with:
  - `_mixins.scss` for shared mixins
  - `_media.scss` for centralized responsive breakpoints
- **Responsive design** – Mobile-first layout adjustments via media queries, tested against provided design mockups

## Project Structure

```
homework5/
├── index.html
├── images/
│   ├── hero.jpg
│   ├── pine-tree-fullbg.png
│   ├── moutain-trekking.avif
│   ├── forrest-camping.avif
│   ├── river-expeditions.avif
│   ├── why-us.avif
│   ├── maya-chen.avif
│   ├── jordan-okafor.avif
│   ├── rafael-torres.avif
│   ├── compass.png
│   ├── clipboard.png
│   ├── shield.png
│   └── people.png
├── scss/
│   ├── _mixins.scss
│   ├── _media.scss
│   └── style.scss (compiled to style.css)
└── css/
    └── style.css
```

## Features

- Responsive navigation with brand logo
- Card-based layout for adventures and services
- Testimonial cards with star ratings and guest photos
- Stat counters in the hero section
- Newsletter signup form in the footer
- Mobile-responsive layout matched to design mockups via media queries

## Notes

This project was built for a web development course assignment focused on Sass architecture and responsive CSS, using a simple `@import`-based structure rather than modern `@use`/`@forward` module syntax, to keep the codebase approachable at a beginner/intermediate level.
