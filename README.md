# DateCraft Landing Page

Production-ready landing page for DateCraft Chocolate Dipped Dates.

## View

Open `DateCraft_landing.html` in a browser. All assets are local — no server or internet required.

## Files

```
datecraft/
├── DateCraft_landing.html        Main page
├── datecraft-product.jpg         Hero product shot (pouch + ingredients)
├── datecraft-intro.mp4           10s intro video (720p, stereo)
├── datecraft-cross-section.jpg   Cut-open date showing layers (also used as faded bg)
├── flavor-dark.jpg               Dark chocolate with sea salt
├── flavor-milk.jpg               Milk chocolate with nuts
├── flavor-white.jpg              White chocolate with drizzle
├── README.md                     This file
└── .gitignore
```

## Sections

- Hero (with background video + audio toggle)
- Why DateCraft (5 benefits)
- Flavors (3 cards with real product photos)
- Our Story
- How It's Made (farm-to-factory narrative + cross-section image)
- Enquiry Form
- CTA

## Features

- Dark/light theme toggle (saved to localStorage)
- Floating gold particle background
- Scroll-triggered animations (Intersection Observer)
- Mouse-reactive video overlay
- Audio control for intro video
- Fully responsive (mobile, tablet, desktop)
- Content Security Policy meta tags
- X-Frame-Options: DENY
- X-Content-Type-Options: nosniff

## To deploy

Upload the entire `datecraft/` folder to any static host (GitHub Pages, Netlify, Vercel). The HTML references files by relative path.
