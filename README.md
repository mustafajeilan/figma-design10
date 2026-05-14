# Figma Design 10

A responsive landing-page layout built from a Figma-inspired design using HTML and CSS.

## Design Overview

This project recreates the original design shown in `images/Original-image-reference.png` using a stacked content section and a multi-image grid.

## Key Concepts Used

- HTML structure with semantic containers:
  - `.main-container` for the overall page wrapper
  - `.content-part` for headings, description, and call-to-action
  - `.images-part` for the visual gallery
- CSS reset on all elements with `margin: 0`, `padding: 0`, and `box-sizing: border-box`
- Responsive layout with `display: flex` and `display: grid`
- Flexbox for the main content area and adaptive page flow
- CSS Grid for the image gallery: a 4x4 grid with `grid-template-columns` and `grid-template-rows`
- Responsive media queries:
  - `@media (min-width: 320px)` for mobile-friendly scaling
  - `@media (min-width: 768px)` for tablet/laptop layout
- Typography styling for large headings and supporting text
- Button styling with padding, border-radius, and hover states
- Image handling with `max-width: 100%` and `object-fit: cover`
- Color scheme and background styling to match the design aesthetic
- Root font sizing using `:root { font-size: 16px; }`

## Files

- `index.html` — page markup and image placement
- `styles/styles.css` — layout, typography, responsive behavior, and image gallery styling
- `images/Original-image-reference.png` — original design reference used for reconstruction
- `images/Frame1.png` through `images/Frame16.png` — gallery assets displayed in the design

## How It Works

1. The HTML file builds a simple landing page with a headline, text, and a button.
2. The gallery section uses HTML `img` tags inside a CSS Grid container.
3. Responsive CSS ensures the content stacks vertically on small screens and shifts to a two-column layout on larger devices.
4. Visual polish is applied through spacing, scaled typography, and image sizing.

## Notes

- The project is intentionally lightweight and uses plain HTML/CSS without JavaScript.
- The original Figma design is referenced directly from `images/Original-image-reference.png`.
