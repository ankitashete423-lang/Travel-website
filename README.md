# Wanderly — Travel Discovery Website

Wanderly is a premium, editorial-style travel discovery website built as a frontend portfolio project. It uses **only HTML5 and CSS3**, with no JavaScript and no frameworks.

> All prices, statistics and ratings are demonstration data. The newsletter form is a visual demo and does not send or store anything.

## Features

- Sticky navigation with a custom SVG logo and a CSS-only mobile menu (checkbox pattern)
- Hero with large serif headline and an arched photograph
- Statistics band with clearly labelled demo figures
- Six featured destination cards (location, category, sample pricing)
- Travel categories: beach escapes, mountain adventures, city breaks
- Editorial travel story section
- Journal with three article cards
- Newsletter section (visual demo only)
- Footer with logo, links, social links and copyright
- Responsive layouts for desktop, tablet and mobile with no horizontal overflow
- Keyboard focus styles, skip link, alt text, and `prefers-reduced-motion` support

## Technologies

- HTML5 (semantic structure)
- CSS3 (custom properties, Grid, Flexbox, media queries, keyframes)
- Google Fonts: Fraunces (serif) and Instrument Sans (sans-serif)
- Photography hosted on Unsplash

## Project structure

```
wanderly/
├── index.html
├── style.css
└── README.md
```

## Run locally

1. Download or clone the repository.
2. Open `index.html` in any modern browser. An internet connection is needed for fonts and photographs.

Optional local server: `python3 -m http.server 8000`, then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (for example `wanderly`).
2. Upload `index.html`, `style.css` and `README.md` to the repository root, or push them with git:
   ```
   git init
   git add .
   git commit -m "Add Wanderly travel website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/wanderly.git
   git push -u origin main
   ```
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
6. After a minute, the site is live at `https://YOUR-USERNAME.github.io/wanderly/`.

## Credits

Photographs are from [Unsplash](https://unsplash.com). The design and code are original.
