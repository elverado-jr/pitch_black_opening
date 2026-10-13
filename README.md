# Homework Simulater.org 🎮

A small browser-game hub, starting with **Pitch Black Pack Pull** — a fan-made card-pack opening simulation.

> **Important:** This is a game simulation. It does not give you real Pokémon cards, items, or money. The card art, emojis, and card details in the game are illustrative/fan-made approximations and are not official Pokémon assets.

## 🕹️ Play the games

- **Game library homepage:** [Open `index.html`](./index.html)
- **Pitch Black Pack Pull (standalone):** [Open `pitch-black-pack-pull.html`](./pitch-black-pack-pull.html)

When GitHub Pages is enabled, the published site should be available at:

`https://elverado-jr.github.io/pitch_black_opening/`

The standalone game should be available at:

`https://elverado-jr.github.io/pitch_black_opening/pitch-black-pack-pull.html`

These links work after GitHub Pages has been configured and the deployment has finished.

## ✨ Features

### Homepage — `index.html`
- A colourful game-library layout branded **Homework Simulater.org**.
- Search field for filtering game cards.
- A playable Pitch Black Pack Pull game built into a pop-up.
- Example cards for future game ideas.
- An “Add a game” preview feature. It adds a placeholder card in the current browser session; it does **not** upload a new game file or save the card permanently.

### Standalone game — `pitch-black-pack-pull.html`
- Open packs and reveal a card.
- Tracks packs opened, special hits, and best streak during the current session.
- Includes a rare special-hit roll with a displayed target chance of 1 in 100 (1%).
- Uses original, simplified visual approximations and emoji rather than official card scans.

## 📁 Project files

| File | Purpose |
| --- | --- |
| `index.html` | Main game-library homepage and embedded pack-opening game |
| `pitch-black-pack-pull.html` | Standalone version of Pitch Black Pack Pull |
| `README.md` | Project information and setup instructions |

## 🚀 Run it on your computer

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Click **Play now** on Pitch Black Pack Pull and press **OPEN PACK**.

You can also open `pitch-black-pack-pull.html` directly to play the standalone game.

No build step or package installation is required; the game is made with HTML, CSS, and JavaScript.

## 🌐 Publish with GitHub Pages

1. Open this repository on GitHub.
2. Select **Settings**.
3. In the left sidebar, choose **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder.
6. Click **Save**.
7. Wait for GitHub Pages to finish deploying, then open the site URL shown on the Pages settings screen.

If the Pages option is missing or deployment does not start, check the repository's visibility and your GitHub plan/settings. Do not share passwords, access tokens, or other secrets in this repository.

## ➕ Add another real game later

The homepage's **Add a game** button currently adds only a temporary placeholder card. To add a playable game to the published site:

1. Add your new game's HTML file to the repository, for example `my-game.html`.
2. Edit `index.html` and add a game card in the game grid.
3. Link that card to your file, or create a game-launch button that opens it.
4. Commit the changes to `main`.
5. Wait for GitHub Pages to deploy the update.

If the game uses separate CSS, JavaScript, or image files, upload those files too and keep their relative paths correct.

## 🛠️ Built with

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages (optional hosting)

## ⚖️ Credits and notes

This is a fan-made hobby project. Pokémon and related names are trademarks of their respective owners. This project is not affiliated with or endorsed by Nintendo, Game Freak, Creatures, or The Pokémon Company. No real-world purchases or trading take place inside the simulation.
