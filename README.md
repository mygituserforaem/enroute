# US Weather App

A single-file weather webapp for US zip codes. No build step, no API keys required.

## Features

- Enter any US 5-digit zip code to get current weather conditions
- Displays temperature, feels like, humidity, wind speed & direction, visibility, UV index, precipitation, and dew point
- 12-hour hourly forecast strip
- Interactive map with a pulsing marker showing the searched location
- Weather card and map displayed side by side
- Responsive layout — stacks vertically on mobile

## APIs Used

| API | Purpose | Cost |
|-----|---------|------|
| [Zippopotam.us](https://www.zippopotam.us/) | Zip code → city name + coordinates | Free |
| [Open-Meteo](https://open-meteo.com/) | Weather data | Free |
| [CARTO Voyager](https://carto.com/basemaps/) | Map tiles | Free |
| [Leaflet.js](https://leafletjs.com/) | Interactive map | Free / Open Source |

## Usage

Just open `index.html` in any modern browser — no server or installation needed.

```bash
open index.html
```

Or host it on GitHub Pages:
1. Go to your repo → **Settings** → **Pages**
2. Set source to the `main` branch
3. Your app will be live at `https://<username>.github.io/<repo>/`

## Tech Stack

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies to install
