# Tattoo Artist Reset — Home Screen App

## What it does
- Separate warm-up, strength, and hourly micro-break sections
- Interactive checkboxes and completion progress
- Saves checkbox progress in the browser on this device
- Print / Save PDF button
- Designed for a phone screen

## Important: make it installable
The included `index.html` works as a local webpage, but iPhone's **Add to Home Screen** feature is most reliable when the page is hosted at an HTTPS address. The files in this folder are a small static website; no app store or server code is needed.

### Easy hosting option
1. Upload `index.html` and `manifest.json` to a static website host such as GitHub Pages, Netlify, or Cloudflare Pages.
2. Open the resulting HTTPS URL in Safari on your iPhone.
3. Tap **Share** → **Add to Home Screen** → **Add**.

The Home Screen icon opens the workout in a standalone-style view. For a true offline installable web app, a service worker would also be needed; this starter bundle does not claim full offline caching.

### Try it on a computer
Open `index.html` in a modern browser. Checkboxes should work, and progress is saved by that browser.

### Safety
Use comfortable, controlled movements. Stop if you develop lightheadedness, chest pain, unusual shortness of breath, or a racing heart, and seek medical advice before increasing exercise intensity.
