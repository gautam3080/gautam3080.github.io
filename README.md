# Gautam's portfolio site

Static site for GitHub Pages: `index.html`, `404.html`, and an `assets/` folder. No build step.
Copy comes from `../case-studies.md`; keep the two in sync.

## Adding Pongz screenshots or video

1. Put files in `assets/` (e.g. `pongz-hero.mp4`, `pongz-practice.png`, `pongz-tutorial.png`).
   Keep videos short (10–20 s), muted, under ~8 MB.
2. In `index.html`, find `var MEDIA = {};` and list them:
   ```js
   var MEDIA = {
     "pongz-hero": "assets/pongz-hero.mp4",
     "pongz-practice": "assets/pongz-practice.png",
     "pongz-tutorial": "assets/pongz-tutorial.png"
   };
   ```
   Any slot left out keeps its placeholder.

## Hosting

Repo `gautam3080/gautam3080.github.io`, branch `main`, root folder → served at https://gautam3080.github.io
