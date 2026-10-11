# 2048

A small, touch-friendly 2048 game that runs in the browser. Open `index.html` to play, or serve this folder from a static web host to use it as an installable web app.

## Play

- Swipe on the board on iPhone or iPad.
- Use the arrow keys on a keyboard.
- Use **Undo** to roll back the last move, or **New game** to start over.

Scores and the current game are saved in the browser. To add it to an iPhone or iPad Home Screen, open the hosted page in Safari, tap **Share**, then **Add to Home Screen**.

## Host it

This is a static site. The included GitHub Actions workflow publishes it to GitHub Pages whenever you push to `main`. The manifest, icon, and service worker let supported browsers install it and keep the game available offline after its first visit.

### Deploy with GitHub Pages

1. Push this project to a GitHub repository on the `main` branch.
2. In the repository, open **Settings → Pages** and set the build source to **GitHub Actions**.
3. Wait for the **Deploy 2048 to GitHub Pages** workflow to finish. The site will be available at `https://<username>.github.io/<repository>/`.
4. On the iPad, open that HTTPS URL in Safari, tap **Share → Add to Home Screen**, and confirm.
