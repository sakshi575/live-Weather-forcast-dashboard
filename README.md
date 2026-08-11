# Weathervane

An interactive weather dashboard built with React + Vite. Search any city to see
current conditions and a 5-day forecast, set against a live animated sky that
shifts with the actual weather — drifting clouds, falling rain or snow, and a
day/night sun and moon.

## Features

- 🔍 City search with recent-search chips (saved to localStorage)
- 📍 Auto-detects your location on load (with permission)
- 🌡️ Toggle between °C and °F
- 🌦️ Animated sky background that reacts to real conditions (clear, cloudy, rain, snow, storm, night)
- 📅 5-day forecast strip
- ⏳ Loading and error states

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).
3. Copy `.env.example` to `.env` and add your key:
   ```bash
   cp .env.example .env
   ```
4. Run the dev server:
   ```bash
   npm run dev
   ```

## Tech stack

- React 18 + Vite
- Axios for API calls
- OpenWeatherMap Current Weather + 5-Day Forecast endpoints
- Plain CSS (no framework) — Fraunces + Space Grotesk from Google Fonts

## Deploy

Push to GitHub, then deploy free on [Vercel](https://vercel.com) or
[Netlify](https://netlify.com) — remember to add `VITE_WEATHER_API_KEY` as an
environment variable in your hosting dashboard.
