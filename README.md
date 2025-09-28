# weather-checker
API based project on weather Weather Checker

A simple web app to fetch and display the current weather for a given city using a weather API. Built with HTML, CSS, and JavaScript.

⚠️ Important: The API key used in this project expires in 15 days. You will need to replace it with a new valid key when it expire

Features

Search weather by city name

Display current temperature, weather condition, humidity, wind speed, etc.

Simple, responsive UI

Error handling (invalid city, network errors)

Technologies Used

HTML

CSS

Vanilla JavaScript (Fetch API)

A weather data provider API (e.g. OpenWeatherMap, WeatherAPI, etc.)

Getting Started
Prerequisites

A modern web browser

A (free or paid) weather API key

Installation

Clone the repository

git clone https://github.com/yourusername/weather-checker.git
cd weather-

Open the project in your code editor

In your JavaScript file (for example app.js), find where the API key is used and replace with your key if needed.

Usage

Open index.html in your browser (double-click or via local server)

Enter a city name in the input field

Click “Search” (or press Enter)

The weather data will be fetched from the API and displaye

API Details

Base URL: e.g. https://api.openweathermap.org/data/2.5/weather

Query parameters typically include:

q for city name

appid for your API key

units (metric or imperial)

Response includes JSON with weather data (temperature, humidity, description, etc.)

You should consult the API’s documentation for exact endpoints and parameters.

Limitations & Expiry:

The API key will expire in 15 days. After expiration, requests will fail (e.g. unauthorized or invalid key errors).

You need to obtain a new key or renew the key before that time.

The project currently supports only basic weather lookup (no forecast, no multiple cities, etc.).

There may be rate limits depending on the API provider.

Project Structure
weather-checker/
├── index.html
└── README.md
