# Explore Japan — Tourism & Travel Guide

This project is a university-assignment-level travel and tourism website built entirely from scratch using **pure HTML5** and **CSS3**. It was developed for the "Introduction to Web Authoring (COM4014)" module.

## 1. Quick Deployment Instructions
Because this site uses strictly static HTML and CSS without any build tools, frameworks, or backend requirements, it is exceptionally easy to deploy:
- **Local Viewing:** Simply double-click on `index.html` to open the website in your default web browser. You do not need a local server.
- **Online Hosting (e.g., GitHub Pages, Netlify, Vercel):**
  1. Upload/Push the entire `COM4014` directory to a GitHub repository.
  2. Go to your repository settings -> Pages, and select the `main` branch as the source. 
  3. Alternatively, drag and drop the folder into Netlify's "Deploy without Git" portal.

## 2. Browser Compatibility Notes
The website is fully compatible with all modern web browsers:
- Google Chrome (latest versions)
- Mozilla Firefox
- Apple Safari
- Microsoft Edge
- Opera

*Note:* The responsive navigation relies on the "Checkbox Hack" using the `:checked` pseudo-class and the `~` sibling combinator. These CSS features have widespread support across all modern browsers, ensuring smooth navigation behavior without relying on JavaScript. CSS Grid and Flexbox are used heavily, both of which are fully supported in modern browsers.

## 3. Accessibility Notes
The project was designed with web accessibility standards in mind:
- **Semantic HTML:** Correct and meaningful use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` tags for document structuring.
- **Alt Text:** Every image tag `<img />` includes descriptive `alt` attributes to ensure screen readers can convey the visual content to visually impaired users.
- **Form Accessibility:** All form fields in `contact.html` utilize proper `<label>` tags linked to their respective `<input>` and `<select>` elements via the `for`/`id` attributes.
- **Aria Attributes:** `aria-label` attributes are used on interactive elements like social links and the mobile navigation toggle where visual text isn't present.
- **Color Contrast:** The primary colors (crimson red, dark charcoal, white background) pass standard WCAG contrast ratios to ensure maximum readability.

## 4. Validation Readiness Notes
The code is written to strictly adhere to the W3C standards.
- **HTML5 Validation:** All `.html` files conform to standard HTML5 structure. Elements are correctly nested, void elements properly utilized, and there are no deprecated tags.
- **CSS3 Validation:** The `style.css` uses modern CSS variables (`:root`), Flexbox, CSS Grid, media queries, and transition animations securely. No non-standard or proprietary prefixes are heavily relied upon.
- **Readability:** Code is cleanly indented and organized. The single `style.css` is separated into logical sections (Reset, Typography, Navigation, Hero, Cards, Forms, Footer, Media Queries) with large comment blocks for easy grading.

Live site : [Arden](https://ardens-prototype.vercel.app/)