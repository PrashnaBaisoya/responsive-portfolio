# Semantic HTML5 & Accessible Personal Portfolio

A multi-page personal portfolio website built strictly with modern semantic HTML5 elements and WCAG 2.1 AA accessibility standards, achieving a **100/100 score** on Google Lighthouse for both **Accessibility** and **SEO**.

## Pages Included
* **`index.html`** — Home page featuring an introduction, semantic landmarks, and core technical skills.
* **`projects.html`** — Portfolio showcase structured with `<article>` cards and descriptive ARIA labels.
* **`contact.html`** — Fully keyboard-navigable contact form using `<fieldset>`, `<legend>`, explicit `<label>` associations, and `aria-required` attributes.
* **`style.css`** — High-contrast, responsive stylesheet with visible keyboard `:focus-visible` states and a skip-to-content link.

## Key Accessibility & SEO Features
* **Semantic Landmarks:** Uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` instead of generic `<div>` containers.
* **Keyboard Navigation:** Includes a hidden "Skip to main content" link on focus and clear focus rings across all interactive elements.
* **Screen Reader Support:** Implements `aria-label`, `aria-labelledby`, `aria-current="page"`, and screen-reader-only helper text for external links.
* **SEO Optimization:** Configured with unique `<title>` tags, meta descriptions, proper heading hierarchy (`<h1>` through `<h3>`), and viewport settings.