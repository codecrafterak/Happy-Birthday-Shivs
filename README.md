# HBD_Shivs

A small, static birthday microsite made for Shivani's 18th birthday.

## 🎯 Overview
- A single-page site (`index.html`) with a countdown, a heartfelt message, and an interactive canvas game "Pop the Cakes." Score 18 to unlock the celebration `surprise.html` page.
- A surprise/celebration page (`surprise.html`) with confetti, sparkles, and a photo gallery featuring 10 images.

## Features
- Countdown to: **January 15, 2026**
- Pop the Cakes game using an HTML5 canvas (click/tap cake emojis to score; avoid bombs)
- Game redirects to `surprise.html` when score >= 18
- Responsive layout and animated visual effects (hearts, confetti, sparkles)
- Lightbox gallery for viewing images

## File structure
- `index.html` — main page (countdown, message, game)
- `surprise.html` — celebration page (gallery, confetti)
- `Shivani*.jpg`, `.png`, `.jpeg` — gallery images
- `Dance.gif` — animated gallery image
- `.gitattributes`

## How to run
1. Open `index.html` in any modern browser (Chrome/Edge/Firefox).
2. Play the game: click/tap the cakes to increase score. Reach 18 points to open the surprise page.

No server, build steps, or dependencies are required — this is pure HTML/CSS/JS.

## Notes & suggestions
- Accessibility: add alt text where missing and consider keyboard support for the game.
- Performance: optimize images (resize/compress) for faster load on mobile.
- Enhancements: add high-score persistence (localStorage), adjust difficulty or add sound effects.

## License & Credits
- Personal project for Shivani's birthday — use or modify with attribution.

---
