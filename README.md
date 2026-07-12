# Speech Pact — Website

Marketing and support site for the **Speech Pact** app — your pocket speech coach for practicing impromptu speaking with instant feedback.

## Pages
- `index.html` — marketing landing page
- `support.html` — support page (FAQ + contact: support@speechpact.com)

## Stack
Plain static HTML + CSS — no build step. Styling lives in `styles.css`; brand assets (icon, mascot, illustrations) are in `assets/`. The palette mirrors the app's design system.

## Local preview
Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy
Any static host works (Vercel, Netlify, GitHub Pages). No environment variables or backend required.
