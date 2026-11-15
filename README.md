# AstroCare Pro

Autonomous astronaut health monitoring for deep-space crews — a single self-contained HTML file.
Offline-first vitals logging, NASA HRP hazard scoring, explainable bone-loss prediction, PDF/CSV/JSON
reports, and full English / हिंदी / मराठी localisation.

## Run locally

Open `index.html`, or serve the folder:

```bash
python -m http.server 8080
```

## Deploy

No build step. Vercel serves `index.html` directly:

```bash
npx vercel --prod
```

Educational tool — not medical advice.
