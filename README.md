# Neon Snake

Neon Snake is a polished, dependency-free arcade game built with a single `index.html` file. Guide a glowing snake around a dark grid, collect energy orbs, grow longer, and survive as the game accelerates.

## Features

- Neon snake and food on a dark, subtle-grid canvas
- Score, best score, level, and live speed tracking
- Speed increases as the score and level increase
- Adjustable base speed from relaxed to turbo
- Three gameplay scenarios:
  - **Classic** — walls end the game
  - **Wrap around** — exiting one edge enters from the opposite edge
  - **Neon maze** — avoid glowing obstacles
- Pause and resume with the button or the `P` key
- Restart with the game-over button, `Space`, or `Enter`
- Keyboard, on-screen, swipe, and touch controls
- Best score saved locally in the browser
- Share button with Web Share API and clipboard fallback
- LinkedIn sharing button for published HTTPS URLs
- Responsive layout for desktop and Android browsers

## Controls

| Action | Control |
| --- | --- |
| Move | Arrow keys or `WASD` |
| Move on mobile | Swipe the board or use the directional pad |
| Pause/resume | Pause button or `P` |
| Restart after game over | Play again, `Space`, or `Enter` |

## Run locally

No server, package manager, or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` directly in a browser.
3. Choose a scenario and base speed, then start playing.

For the best sharing and install experience, publish the game over HTTPS using GitHub Pages.

## Publish with GitHub Pages

1. Create a new **Public** repository on GitHub, such as `neon-snake`.
2. Upload `index.html` and `README.md` to the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then choose **Save**.
6. Wait for deployment to finish. GitHub will provide a URL similar to:

   `https://your-username.github.io/neon-snake/`

Open that URL to play the public version and copy it when sharing the game.

## Android and sharing

Open the GitHub Pages URL in Chrome on Android and choose **Add to Home screen** from the browser menu. The game is responsive and supports touch gestures and on-screen controls.

Use **Share game** to share the public URL through Android's share sheet. Use **Share on LinkedIn** to open LinkedIn's sharing flow. A local `file://` address cannot be shared publicly, so publish the game first.

## Technology

- HTML5 Canvas
- Vanilla JavaScript
- CSS with responsive design and `prefers-color-scheme`
- Browser `localStorage` for the best score
- No external libraries or build step

## License

This project is available for personal and educational use. Add a license file if you plan to distribute or modify it publicly.
