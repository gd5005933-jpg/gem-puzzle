# Gem Puzzle

An original, self-contained HTML5 match-three game. It uses plain HTML, CSS, and JavaScript, with no server, external libraries, or third-party media.

## Run locally

Open `index.html` in a modern desktop or mobile browser. For local static hosting, serve this folder with any static web server.

## Publish

Upload the complete project folder, keeping `index.html`, `style.css`, `game.js`, and `assets/` together, to a static host such as GitHub Pages, Netlify, or Cloudflare Pages. No build step or server-side runtime is required. The game uses relative paths.

## Controls and features

- Select adjacent gems with mouse/touch, or drag between neighboring cells.
- Valid matches of three or more clear automatically; cascades earn combo multipliers.
- Reach the level target to advance and earn extra moves.
- Pause, continue, restart, and toggle synthesized sound from the controls.
- Best score is saved in browser local storage on the current device.

All visual effects and sound are generated locally by CSS and the Web Audio API. `assets/` is reserved for any future original game assets; the current version needs no image or audio files.
