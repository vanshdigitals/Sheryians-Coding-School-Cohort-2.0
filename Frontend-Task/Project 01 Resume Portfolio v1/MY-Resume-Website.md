# My Resume Website

This is a practice project built during Sheryians Coding School Cohort 2.0. The goal was to build a simple, clean resume-style webpage using HTML and CSS while learning layout, typography, and responsive basics.

## Overview

- Project name: My Resume Website
- Built with: HTML, CSS
- Font: Montserrat (Google Fonts)
- Purpose: Learning practice — create a personal resume/portfolio layout, practice semantic HTML, typography, and basic responsive design.

## What I learned

- HTML structure and semantic elements: `header`, `section`, `footer`.
- Linking external stylesheets and using Google Fonts.
- CSS layout fundamentals: spacing, padding, background colors, and card-style containers.
- Basic responsive design using media queries to adapt for mobile devices.
- A small JavaScript snippet to display the current year dynamically.

## Project structure

- `Index.html` — main page markup.
- `styles.css` — styling for layout, colors, and responsive tweaks.
- `MY-Resume-Website.md` — this project description.

## How to view locally

1. Open `Index.html` directly in a browser (double-click) OR run a simple local server for correct font loading:

   - Using Python 3:

     ```powershell
     python -m http.server 8000
     ```

     <!-- Then open http://localhost:8000 in your browser. -->

   - Using Node (no install needed for `http-server`):

     ```powershell
     npx http-server -p 8000
     ```

     <!-- Then open http://localhost:8000. -->

2. Resize the browser or use DevTools device toolbar to test mobile view.

## Notes & Suggestions

- The project uses Montserrat from Google Fonts. If you prefer not to rely on an external CDN, consider self-hosting the font files.
- For improved responsiveness, replace large fixed paddings with a centered container (`max-width`) and responsive gutters so content adapts smoothly to different screen sizes.
- Contact details are already wrapped in clickable links; you can improve accessibility by adding aria-labels where appropriate.
- Consider adding a responsive grid for the skills and projects sections to make better use of available space on larger screens.

## Possible next steps (ideas)

- Add a navigation bar and smooth scrolling to sections.
- Implement CSS variables and a dark-mode toggle.
- Add a contact form (with client-side validation) and a simple JSON-based storage or Netlify Forms.
- Add more pages: Projects detail pages, a printable resume, or a blog section.

---

Made with ❤️ during Sheryians Coding School Cohort 2.0 by Vansh.
