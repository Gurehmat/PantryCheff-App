# PantryChef Web Spec (v1)

## Stack
- VS Code
- HTML + CSS + vanilla JS only
- No Tailwind, no frameworks, no build tools
- Files: index.html (Pantry), recipes.html, shopping.html, styles.css, app.js

## Design source
See screenshots in /ui-ref:
- pantry.png
- modal-add.png
- recipes.png
- shopping.png

## Layout rules
- Center container max-width: 980px
- Page padding: 24px
- Spacing scale: 8px grid (8/16/24/32)
- Radius: 16px (default)
- Subtle border + soft shadow (light mode)

## Components (class names must be reused)
- Topbar: .topbar .container .brand .navlinks .navlinks__link .actions .iconbtn
- Page header: .page-header .page-title .btn .btn--primary
- Search: .search .search__icon .search__input
- Chips: .chips .chip .chip--active
- Pantry list rows: .list .row .
