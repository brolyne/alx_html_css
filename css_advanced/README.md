HTML/CSS — Advanced Exercises (css_advanced)
============================================

Description
-----------
This folder contains the "advanced" step of the ALX-style HTML/CSS exercises. It is intended for practicing and demonstrating more advanced CSS techniques (beyond the basic layout), such as responsive design patterns, Flexbox/Grid refinements, accessibility improvements, and subtle visual polish.

Purpose
-------
- Provide a workspace for experimenting with advanced CSS rules while keeping the core Flexbox layout strategy intact.
- House a simple demo page (`index.html`) and a stylesheet (`styles.css`) that showcase responsive behavior and styling techniques.

What’s in this folder
---------------------
- `index.html` — the demo page you can open in a browser to preview the result.
- `styles.css` — advanced styling rules for the demo. Non-positioning visual rules (colors, typography, table striping, logo styles, etc.) should live here.
- `README.md` — this file.

How to preview
--------------
Open `index.html` in your default Windows browser from the command line:

```cmd
start "" "c:\Users\brolyne\Desktop\programs\git\html2\alx_html_css\css_advanced\index.html"
```

Or open the file directly from your editor (VS Code: right-click → Open with Live Server if you have that extension).

Responsive / Mobile notes
-------------------------
- The page includes a viewport meta tag to ensure proper scaling on smartphones.
- The layout strategy uses CSS Flexbox: `body` is a column flex container; `main` is a row flex container containing `article` and `aside`. Please do not change this overall layout strategy.
- If you want to tweak the mobile behavior, add non-positioning rules (colors, font sizes, margins) or media queries in `styles.css`. To change layout on small screens, prefer adding small responsive rules rather than replacing Flexbox with a different positioning system.

Recommended next edits / challenges
----------------------------------
- Add a visually distinct logo (unicode character is fine) and style it in `styles.css`.
- Improve the article content: semantic headings, accessible image `alt` text, and meaningful links.
- Add a responsive breakpoint to collapse the aside below the article on narrow screens (e.g. `@media (max-width:640px)`).
- Experiment with subtle animations (transitions for hover states) and accessible color contrast.

Resources
---------
- Mozilla Developer Network (MDN) — Flexbox guide: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout
- A Complete Guide to Flexbox — CSS-Tricks: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Responsive meta tag reference: https://developer.mozilla.org/en-US/docs/Mobile/Viewport_meta_tag

Notes
-----
Keep layout-only (positioning) rules in the shared layout file and use this `styles.css` for enhancements that don't replace the Flexbox strategy. If you want, I can add example responsive snippets or accessibility improvements — tell me what you prefer.

