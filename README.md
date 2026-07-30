# The Cinder Vault

A Slay the Spire–style deckbuilding roguelike, built as a single self-contained HTML file — no build step, no dependencies. Open `index.html` in a browser and it runs.

**▶ Play:** https://trevorlolsen.github.io/cinder-vault/

## Requirements

A desktop browser with a window of at least **1000 × 660**, plus a mouse and keyboard. Below that size the game shows a resize prompt instead: a ten-card hand needs about 972px of width before cards start overlapping, and hiding a card you are holding hides a decision.

There is no touch support — the game uses hover tooltips and keyboard shortcuts throughout.

## Running locally

Serve the folder over HTTP (assets load via relative paths, so `file://` won't work reliably):

```sh
python -m http.server 8000
# then open http://localhost:8000/
```

## Structure

- `index.html` — the entire game (HTML/CSS/JS inline).
- `assets/art/` — relic/potion icons and combat FX animation frames.
- `assets/audio/` — music loops and sound effects.
