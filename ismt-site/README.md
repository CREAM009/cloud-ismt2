# ISMT College, Kathmandu – Static Website

A simple, responsive, accessible static site for ISMT College, Kathmandu. Built with HTML5, CSS, and vanilla JS only.

## Quick Start
1. Download or clone this repository.
2. Open `index.html` directly in your web browser (no server required).

## Adding Images
- Place your images in the `/assets/img/` folder.
- Update `<img>` tags in the HTML to use your image filenames and add descriptive `alt` text.

## Reusing Header & Footer
- Copy the `<header>...</header>` and `<footer>...</footer>` sections from `index.html` to other pages (e.g., `about.html`, `programs.html`).
- Update the `.active` class and `aria-current="page"` on the relevant nav link for each page.

## Deployment Notes (AWS S3 + CloudFront)
- Upload all files to an S3 bucket configured for static website hosting.
- Set `index.html` as the default root object.
- Use CloudFront for CDN and HTTPS.
- Ensure all asset paths are relative or root-relative for compatibility.

---

© ISMT College, Kathmandu. All rights reserved.
