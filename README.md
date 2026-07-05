# The Cinder Vault

A Slay the Spire–style deckbuilding roguelike, built as a single self-contained HTML file — no build step, no dependencies. Open `index.html` in a browser and it runs.

**▶ Play:** https://trevorlolsen.github.io/cinder-vault/

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
