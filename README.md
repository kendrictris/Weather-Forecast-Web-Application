# Weather Forecast Web App

A responsive weather forecast web app that shows current conditions and a 5-day forecast for any city, or the user's current location.

## Features
- Live weather data via WeatherAPI.com (fetch, async/await)
- Search by city name or auto-detect location via IP
- 5-day forecast with min/max temps, wind, humidity, chance of rain
- Dark mode toggle
- Dynamic background based on weather condition (sunny, cloudy, rainy, snowy)

## Tech Stack
- HTML, CSS, JavaScript (all in a single self-contained file)
- Deployed on a Raspberry Pi running Linux, using Apache as the web server
- PHP was installed and tested as part of setting up the server environment (see `/server-setup` folder), though the app itself runs entirely client-side in JavaScript

## Server Setup
This project was deployed on a Raspberry Pi. Screenshots/recordings of the setup process (installing Apache, PHP, and configuring the server) are included in `/server-setup`.

## Notes
This project was built for a university assignment with an open brief, allowing free choice of topic and implementation.
