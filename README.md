# 2048

**Join the tiles.** This is a touch-friendly 2048 number puzzle that runs in your browser. Play the live game at [arnavgmallan.github.io/2048](https://arnavgmallan.github.io/2048/).

## How to play

- Slide tiles with the **arrow keys** on a keyboard or **swipe** on a touch screen.
- Matching tiles merge into one; reach the **2048** tile to win. You can keep playing after winning.
- **Undo** rolls back your last valid move. **New game** starts a fresh board.
- Your current game and best score are saved in your browser on that device.

## Install and offline play

The site is a progressive web app. On a supported browser, use its install option to add it to your device. On iPhone or iPad, open the live game in Safari, tap **Share → Add to Home Screen**. After the first visit, the service worker caches the game files for offline use.

## Run locally

No build step or dependencies are required. Clone the repository and open `index.html` in a browser, or serve the project directory with any static web server. The service worker is registered on HTTPS sites and on `localhost`.

## Deploy

GitHub Actions deploys the repository to GitHub Pages when changes are pushed to `main` (or when the workflow is run manually). To enable deployment, select **Settings → Pages → GitHub Actions** in the repository. The live site is [https://arnavgmallan.github.io/2048/](https://arnavgmallan.github.io/2048/).

## License

This project is available under the [MIT License](LICENSE).
