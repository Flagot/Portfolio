# Developer Portfolio

A single-page developer portfolio with a separate blog page. Built as a static site using plain HTML, CSS, and a small amount of JavaScript, with a focus on clean UI and smooth UX.

## Structure

- **`index.html`** – main one-page portfolio with:
  - Hero section
  - Experience timeline
  - Projects grid
  - Skills overview
  - Contact section with a demo form
- **`blog.html`** – simple blog listing page with featured posts and a short sidebar.
- **`styles.css`** – global design system (colors, typography, layout, components) and responsive breakpoints.
- **`script.js`** – mobile navigation, smooth scrolling, contact form validation, and dynamic year.
- **`package.json`** – optional helper to serve the site locally.

## Running locally

You can open `index.html` directly in your browser, or use a simple static server:

```bash
cd path/to/portfolio
npm install serve --global   # if you don't already have it
serve .
```

Then open the printed local URL (for example `http://localhost:3000`) in your browser.

## Customization

- Update the placeholder text in `index.html` (`Your Name`, experience entries, projects, skills, and contact details).
- Edit the blog post summaries in `blog.html`.
- Adjust the color palette, spacing, and typography tokens in `styles.css` as needed.

