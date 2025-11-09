# ColorCatcher

A small, browser-based color picking game built with plain HTML, CSS and JavaScript.

Live repository: https://github.com/heyvishusri/colorCatcher

## Overview

ColorCatcher is a lightweight game where the player is shown a target color name and must click the matching colored tile from a grid before the timer runs out. It's designed as a simple, fun demo of DOM manipulation, event handling, and a tiny game loop using vanilla JavaScript.

## Features

- 5x6 grid of colored tiles (configurable in `script.js`)
- Randomized target color each round
- 30-second timer with scoring
- Light / Dark theme toggle
- Minimal, dependency-free code (works in any modern browser)

## Demo / Screenshots

Open `index.html` in your browser to play locally. If you'd like to include screenshots in the repo, add them to a `screenshots/` folder and reference them here.

## How to run

1. Clone the repository (or download the ZIP):

   git clone https://github.com/heyvishusri/colorCatcher.git

2. Open the project folder and open `index.html` with your browser (double-click or right-click -> Open with...).

Optional: serve it with a static server (helpful for some browsers):

- Using Node (http-server):
  1. npm install -g http-server
  2. http-server .
  3. Open the URL shown by http-server in your browser.

## Gameplay

- Click the "Start Game" button to begin. A 30-second timer starts.
- A target color name is shown (e.g., "navy"). Click the tile that matches that color to score a point and refresh the grid.
- When the timer reaches 0, the game ends and your final score is displayed.
- Use the Light / Dark buttons at the top to switch theme.

## Project structure

```
e:/colorCatcher
├─ index.html      # Main page
├─ script.js       # Game logic, grid, timer, theme toggles
└─ style.css       # Styling for layout and themes
```

## Customize

- Add/remove colors: edit the `colors` array in `script.js`.
- Change grid size: adjust the `.color-grid` CSS and how many tiles you create in `createGrid()`.
- Timer and scoring: modify the `time` default and scoring logic in `script.js`.

## Contribution

Contributions are welcome. If you'd like to suggest changes or add features (extra modes, better accessibility, sounds, mobile optimizations), open a GitHub issue or submit a pull request to:

https://github.com/heyvishusri/colorCatcher

When contributing, please:

- Fork the repository
- Create a feature branch
- Make changes and add a short description in your PR

## License

This project is provided under the MIT License — see `LICENSE` if you add one. If you want me to add a `LICENSE` file (MIT or another), tell me which license you prefer and I'll add it.

## Notes

- The project uses plain JavaScript and no build step — it's ready to upload to GitHub Pages or any static host.
- If you want, I can also add a small README badge, a demo link (GitHub Pages), or a `package.json` with a local start script.

---

If you'd like changes to the README (more screenshots, badges, or additional usage examples), tell me what you'd like added and I will update it.
