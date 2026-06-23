# Edward Dong — personal website

A minimal static research website for Edward Dong (immunology researcher at Memorial
Sloan Kettering, incoming PhD student at Princeton, Schwarzman Scholar).

Plain HTML, CSS, and a little vanilla JavaScript. No build step.

## Files

- `index.html` — the page, including the interactive cell and DNA-transcription canvases
- `stylesheet.css` — styling
- `profile.JPG`, `sailing.jpg` — images

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Pushes to `main` are deployed to GitHub Pages by the workflow in
`.github/workflows/deploy.yml`. Enable it once under
**Settings → Pages → Build and deployment → Source: GitHub Actions**.
