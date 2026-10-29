# HYPER INU ($HI)

Static website for HYPER INU on Ethereum. No build step required.

## Local preview

Open `index.html`, or from this folder run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Launch config

Edit `assets/js/script.js` and fill in `CONFIG`:

- `CA` — token contract (`0x` + 40 hex). Leave empty for **Coming soon..**
- `X` / `TG` — social URLs. Leave empty for **Coming soon..**

## Deploy

Pushes to `main` deploy automatically via GitHub Pages (Actions workflow).
