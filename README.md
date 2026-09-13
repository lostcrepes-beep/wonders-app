# Wonders — Desktop App

This folder is a ready-to-run Electron project that wraps your `index.html`
menu screen in a real desktop window.

## 1. Install Node.js
Download from https://nodejs.org if you don't already have it (LTS version is fine).

## 2. Install dependencies
Open a terminal in this folder and run:

```bash
npm install
```

## 3. Run it
```bash
npm start
```

This opens your menu screen in its own desktop window (not a browser tab).

## 4. Package it into an installer (optional)
Once you're happy with it, turn it into a real `.exe` / `.dmg` / `.AppImage`:

```bash
npm run dist
```

The finished installer will land in a new `dist/` folder.

## File overview
- `index.html` — your menu screen, unchanged
- `main.js` — the Electron entry point that creates the window and loads `index.html`
- `package.json` — project config, scripts, and packaging settings
