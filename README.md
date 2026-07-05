# Vinnovates Website — GitHub Pages Setup

This folder contains everything needed to publish the site:

- `index.html` — the website
- `logo.png` — your logo, referenced by the website

## How to publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `vinnovates-website`).
2. Upload **both** `index.html` and `logo.png` to the root of that repository.
   - Keep them in the same folder — do not put `logo.png` inside a subfolder, since `index.html` looks for it right next to itself.
3. Go to the repository's **Settings → Pages**.
4. Under "Source", choose the `main` branch and `/ (root)` folder, then click **Save**.
5. GitHub will give you a live link, usually:
   `https://your-username.github.io/vinnovates-website/`
   It can take a minute or two to go live after the first save.

## If something looks broken

- Logo not showing? Double check `logo.png` was uploaded to the exact same folder as `index.html` and that the filename is lowercase, exactly `logo.png`.
- Blank page? Make sure the file is named exactly `index.html` (lowercase), since that's the name GitHub Pages looks for automatically.
