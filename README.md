# Garv Joshi: Personal Resume Website

A single-page personal resume website built with HTML, CSS and JavaScript.

## Project structure

```
garv-resume-website/
├── index.html   page structure, content and JavaScript
├── style.css    all styling, linked from index.html
└── README.md
```

## How the CSS is organised

All styles live in `style.css` and are loaded from the `<head>` of `index.html`:

```html
<link rel="stylesheet" href="style.css">
```

`index.html` has no `<style>` block. The only JavaScript (the growth-curve marker placement and the "Copy" buttons in the contact section) stays in `index.html`.

## Running it

Open `index.html` in a browser. Keep `index.html` and `style.css` in the same folder so the relative link works.

The page loads its fonts (Bricolage Grotesque, Source Serif 4, Caveat, Space Grotesk and IBM Plex Mono) from Google Fonts, so it needs an internet connection to show them. Without one, it falls back to system fonts.

## Publishing on GitHub Pages

Upload the three files to the repository root, then go to **Settings → Pages**, choose the branch and the `/ (root)` folder, and save.
