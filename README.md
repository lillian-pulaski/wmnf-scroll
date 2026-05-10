# White Mountains National Forest — Travel Guide

An interactive, scroll-driven travel guide for White Mountains National Forest built with HTML, CSS, and GSAP (GreenSock Animation Platform).

---

## Project Overview

This project is a single-page scrolling travel guide designed to present information about White Mountains National Forest in an engaging, visually dynamic way. Each section uses a distinct layout and animation to guide the viewer through key facts, highlights, and travel tips.

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Hero | Title slide with animated text and SVG map sliding in on load |
| 2 | Acres | Stat slide — circle expands to fill screen on scroll |
| 3 | Peaks Counter | Two half-circle domes rise up from the bottom |
| 4 | Highest Peaks | Three triangles representing the top peaks slide in from alternating sides |
| 5 | Activities | Table rows slide in from the left on scroll |
| 6 | Popular Attractions | Project cards scroll in horizontally from the right |
| 7 | Travel Tips | Project cards scroll in horizontally from the left |
| 8 | End / CTA | Mountain triangles rise from below; links to USFS site and back to top |

---

## Technologies Used

- **HTML5**
- **CSS3** — Flexbox, clamp(), custom properties
- **JavaScript (vanilla)**
- **GSAP 3** — GreenSock Animation Platform
  - ScrollTrigger plugin
  - ScrollToPlugin plugin
- **Google Fonts** — Afacad
- **Google Material Symbols** — icons

---

## Animation References

| Section | Technique | Reference |
|---------|-----------|-----------|
| SEC 1 | `gsap.from()` slide in on load | https://gsap.com/docs/v3/GSAP/gsap.from() |
| SEC 2 | Scale + ScrollTrigger pin/scrub | https://www.youtube.com/watch?v=SCfZBtedicw |
| SEC 3 | GSAP timeline with staggered ScrollTrigger | https://www.youtube.com/watch?v=-qQhTxTtpeQ&t=284s |
| SEC 4 | SVG elements animated with ScrollTrigger scrub | https://gsap.com/docs/v3/Plugins/ScrollTrigger/ |
| SEC 5 | Staggered row animation with ScrollTrigger | https://gsap.com/docs/v3/GSAP/gsap.from() |
| SEC 6 & 7 | Horizontal scroll track with pinned ScrollTrigger | https://gsap.com/docs/v3/Plugins/ScrollTrigger/ |
| SEC 8 | `gsap.fromTo()` with ScrollTrigger | https://gsap.com/docs/v3/GSAP/gsap.fromTo() |

---

## File Structure

```
/
├── index.html        # Main HTML file
├── style.css         # All styles
├── README.md         # Project documentation
└── photos/
    ├── WM.svg        # White Mountains SVG map (hero image)
    ├── mtwash.jpg    # Mt. Washington photo
    ├── kanhigh.jpg   # Kancamagus Highway photo
    └── flumegorge.jpg # Flume Gorge photo
```

---

## How to Run

No build tools or dependencies required. Just open `index.html` in a browser.

```bash
# Clone the repo
git clone https://github.com/your-username/wmnf-travel-guide.git

# Open in browser
open index.html
```

Or use a local dev server like VS Code Live Server for best results.

---

## Credits

- **Design & Development** — Lillian Pulaski
- **Animation** — GSAP by GreenSock (https://gsap.com)
- **Icons** — Google Material Symbols (https://fonts.google.com/icons)
- **Font** — Afacad via Google Fonts (https://fonts.google.com)
- **Data** — White Mountain National Forest, USDA Forest Service (https://www.fs.usda.gov/whitemountain)

