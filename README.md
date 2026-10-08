# R10 Pro Aqua Guide

Animated, bilingual (English / ქართული) how-to for the Dreame R10 Pro Aqua cordless vacuum: what's in the box (11 parts), assembly, which head goes on which floor, the trigger and modes, the spin mop, cleaning routine, troubleshooting, and the manual's safety rules.

- `index.html` is the whole app (inline CSS/JS/SVG). It loads GSAP from cdnjs and fonts from Google Fonts; everything else is self-contained.
- Live site (GitHub Pages): https://app-droze.github.io/r10-pro-aqua-guide/
- Claude artifact copy: https://claude.ai/artifact/1Y7ZZ3f1CXyzMqvncgh3dA
- Georgian is the default language; the EN button switches, and the choice is remembered in the browser.
- Language: the ქართული / EN toggle in the header. Georgian strings live in the `KA_RAW` dictionary inside `index.html`; the English text is the key. In the browser console, `window.__r10missing` lists any string without a Georgian entry.
- Facts: Dreame product pages for the R10 Pro Aqua, plus Dreame's R10 Pro and R10S Slim Aqua manuals (see the Sources footer on the page). Where the paper manual in the box differs, the paper manual wins.

To preview locally, open `index.html` in a browser (it renders without a wrapper), or serve the folder with `python3 -m http.server`.
