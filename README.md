# Infinity — T-Rex Endless Runner

A complete clone of the Chrome offline dinosaur game. The T-Rex runs
automatically; jump to clear an endless stream of obstacles and survive as long
as possible. A collision triggers the game-over screen and a restart button.

## Features

- Auto-running animated T-Rex sprite
- Gravity + spacebar jump
- Six obstacle types (`obstacle1`–`obstacle6`) spawning continuously
- Drifting clouds
- Game-over screen with a clickable restart button

## Libraries

- [p5.js](https://p5js.org/)
- [p5.play](https://molleindustria.github.io/p5.play/) — sprites, animations, collisions
- p5.dom, p5.sound

All libraries are vendored — no install/CDN required.

## How to run

Open through a web server so the image assets load:

- **Local static server:** from the repo folder run `python3 -m http.server 8000`
  and visit `http://localhost:8000`
- Or use the VS Code "Live Server" extension on `index.html`
- Or enable GitHub Pages and open the published URL
- Or double-click `index.html` if your browser permits local file access

## Controls

- **Spacebar** — jump
- **Restart button** — click after game over to restart
