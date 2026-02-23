# SunDose ☀️

A Vitamin D sun tracker that tells you when to go outside — and roasts you when you don't.

Built as a single-file web app. No install, no sign-up, no excuses.

## What it does

- Fetches real-time UV index data for any city in the world
- Shows the optimal window for Vitamin D absorption (UV 3–7)
- Animated sky canvas that changes based on time of day — sunrise, noon, golden hour, full night
- Hover the UV chart and watch the sky transition in real time
- Sarcastic commentary that gets progressively more aggressive as UV goes up
- Advice section with skin-tone specific exposure times

## How to use

Open it in a browser. Type a city. Hover the chart. Go outside.

## Tech

- Vanilla HTML, CSS, JavaScript — single file, no framework, no build step
- [Chart.js](https://www.chartjs.org/) for the UV curve
- [Open-Meteo](https://open-meteo.com/) for UV data (free, no API key)
- [Nominatim](https://nominatim.org/) for geocoding
- Canvas 2D API for the animated sky


---

Built by [vrgoks](https://github.com/vrgoks)
