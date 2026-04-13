# Data Engineering Portfolio Landing Page

This folder contains a static portfolio website built from the **Massively** template by HTML5 UP and customized to showcase data engineering and analytics projects.

## Overview

The site presents featured project work, project summaries, and contact/social links in a clean single-page experience.

Current highlights include:

- Sunshine Resort customer analysis (Power BI)
- Bank fraud detection analysis (SQL)
- Customer behavior analysis
- Airline customer analysis
- Culinary business impact analysis

## Tech Stack

- HTML5
- CSS3 (compiled from Sass)
- JavaScript
- jQuery + Scrollex/Scrolly
- Font Awesome icons


## Run Locally

Because this is a static site, you can run it directly:

1. Open `index.html` in your browser.
2. Or serve it from a local server for best behavior (recommended):

```bash
cd LandingPage
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Customization Guide

### 1. Update text and sections

Edit project titles, descriptions, links, and contact info in:

- `index.html`

### 2. Update social links

Replace LinkedIn and GitHub URLs in the nav/footer sections of:

- `index.html`

### 3. Replace images

Put your image files in:

- `images/`

Then update `<img src="images/...">` references in:

- `index.html`

### 4. Update styling

Quick changes:

- `assets/css/main.css`

Source-level Sass changes:

- `assets/sass/` (then recompile Sass if needed)

## Deployment Options

You can deploy this static site easily on:

- GitHub Pages
- Netlify
- Vercel
- Azure Static Web Apps

For GitHub Pages, publish the `LandingPage` folder content and ensure `index.html` is in the published root.

## Accessibility and Quality Tips

- Add descriptive `alt` text for all project images.
- Replace placeholder links (`#`) with actual project URLs.
- Keep headings in logical order (`h1` -> `h2` -> `h3`).
- Test responsive behavior on mobile and desktop.

## Credits

- Design template: **Massively** by HTML5 UP
- Icons: Font Awesome
- JS libraries: jQuery, Scrollex, Scrolly, Responsive Tools

## License

Template is provided under the **Creative Commons Attribution 3.0** license as noted by HTML5 UP.

Please review and keep the required attribution when redistributing.
