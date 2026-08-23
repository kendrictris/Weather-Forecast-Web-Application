# Weather Forecast Web App

A weather forecast web app that shows the current weather and a 4 day forecast for any city, or for the user's current location.

## Features

Shows live weather data from WeatherAPI.com using fetch and async/await
Lets the user search by city name, or find their location automatically using their IP address
Shows a 4 day forecast with min and max temperature, wind, humidity, and chance of rain
Has a dark mode toggle
Changes the background depending on the weather (sunny, cloudy, rainy, snowy)

## Tech Stack

HTML, CSS, and JavaScript, all inside one file
Put on a Raspberry Pi running Linux, using Apache as the web server
PHP was installed and tested while setting up the server, but the app itself runs fully in the browser using JavaScript

## Setup

This project needs a WeatherAPI.com API key to run.

1. Copy `config.example.js` and rename the copy to `config.js`
2. Open `config.js` and replace the placeholder with your own API key
3. `config.js` is not included in this repository, since it holds a private key

## Note on API key security

The API key is kept out of this GitHub repository using a `.gitignore` file. However, since this project runs fully in the browser with no backend, the key is still visible to anyone who inspects the live site's network requests. A more complete fix would move the API call behind a small server side script, so the key is never exposed to the browser at all.

## Server Setup

This project was set up and run on a Raspberry Pi. Recordings of the setup process are linked below:

- Checkpoint 1: [Weather App - Checkpoint 1](https://youtu.be/w9y-0J6hUnc)
- Checkpoint 2: [Weather App - Checkpoint 2](https://youtu.be/tBeBGsEvRxA)
- Final: [Weather App - Final](https://youtu.be/c3Lz6zidLtw)

## Notes

This project was made for a university assignment. The assignment let me choose any idea, so I chose to build this.


