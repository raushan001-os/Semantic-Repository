# Semantic HTML5 & Accessible Component Architecture

An accessible enterprise dashboard foundation built with semantic HTML5 and WCAG 2.1-oriented patterns.

## Features
- Semantic `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`
- Skip link and visible keyboard focus
- Multi-page dashboard: Overview, Users, Reports
- Accessible tables with captions and scoped headers
- Forms with explicit labels, fieldsets, legends, validation attributes, and descriptive help
- Native `<dialog>` modal with labelled controls
- Responsive layout

## Run locally

No build step is required.

```bash
# from this folder
python -m http.server 8000
```

Open `http://localhost:8000/` in a browser.

## Validation

Validate `index.html` and the other HTML pages with the W3C Nu HTML Checker/HTML Validator. The source is written to avoid duplicate IDs, invalid nesting, missing `lang`, and other common syntax errors.

## Accessibility checks
1. Navigate using Tab/Shift+Tab only.
2. Confirm the skip link appears when focused.
3. Confirm all controls have visible focus.
4. Confirm table headers are associated with data using `scope`.
5. Confirm every form input has an explicit label.
6. Open and close the native modal with keyboard controls.
