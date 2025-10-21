# Project 02 — Hero Section Image

This project is a simple landing page that uses a fullscreen astronomy background image. The page includes a main heading, a short paragraph, and a call-to-action button labeled "Explore More".

## What I changed

- Added mobile-responsive rules to `styles.css`:
  - For small screens (≤ 480px) the `.background` container uses flexbox to center the content vertically and horizontally.
  - Increased left/right padding for `h1` and `p` so text doesn't touch the screen edges on small devices.
  - Styled `.btn` to behave nicely on mobile (full-width with a max-width and centered).
  - Kept the existing tablet breakpoint (~768px) which scales fonts down.

# Hero Section Image — Project 02

This is a practice project built during Sheryians Coding School Cohort 2.0. The goal was to build a simple, responsive hero/landing section using a fullscreen astronomy background image, learn responsive layout techniques, and make a clean call-to-action.

## Overview

- Project name: Hero Section Image (Project 02)
- Built with: HTML, CSS
- Purpose: Practice responsive hero layout, background image overlay, and basic accessibility for a landing section.

## What I changed / key points

- Implemented a fullscreen background image with an overlay and centered content.
- Added responsive rules in `styles.css` to improve mobile layout (≤ 480px):
  - `.background` uses flexbox to center content vertically and horizontally on small screens.
  - Increased padding on `h1` and `p` to avoid touching screen edges on mobile.
  - `.btn` styled to be easier to tap on mobile (full-width with a max-width and centered alignment).
- Kept a tablet breakpoint (~768px) to scale typography appropriately.

## What I learned

- Centering and stacking content over a responsive background using flexbox.
- Balancing overlay, z-index, and readability when using background images.
- Practical responsive adjustments: padding, max-widths, and touch-friendly buttons.

## Project structure

- `Index.html` — main HTML file with hero section markup.
- `styles.css` — styling and responsive breakpoints.
- `README_Project-02.md` — this document (styled like Project 01 README).

## How to view locally

1. Open `Index.html` directly in a browser (double-click) OR run a simple local server for correct font loading and relative asset serving.

   - Using Python 3 (PowerShell):

     ```powershell
     python -m http.server 8000
     ```

     Then open [http://localhost:8000](http://localhost:8000) in your browser.

   - Using Node (http-server via npx):

     ```powershell
     npx http-server -p 8000
     ```

2. Use DevTools → Responsive device toolbar to test mobile, tablet, and desktop breakpoints.

## Notes & suggestions

- If the content appears behind the background image, increase the content z-index, for example:

  ```css
  .background h1,
  .background p,
  .background .btn {
    z-index: 2;
  }
  ```

- Add ARIA labels and keyboard focus styles to improve accessibility for users who rely on keyboards or screen readers.
- Consider optimizing the background image (WebP or compressed JPEG) to improve load performance.

## Possible next steps (ideas)

- Publish the project to GitHub Pages for a live demo.
- Add a subtle entrance animation for the hero content (fade/slide) with reduced-motion support.
- Provide multiple background image sizes (srcset) for faster loads on mobile.
- Add a small contact CTA or newsletter form below the hero section.

---

Made with ❤️ during Sheryians Coding School Cohort 2.0 by Vansh.
