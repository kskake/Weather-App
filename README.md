# Weather App

A simple weather app that fetches data from the OpenWeather API and displays it with a dynamic background that changes based on the weather.

## How to Use

1. **Get an OpenWeather API Key**:
   - Sign up at [OpenWeather](https://openweathermap.org/) and get your API key.

2. **Set Up the API Key**:
   - Copy `config.example.js` to a new file named `config.js`.
   - Open `config.js` and replace `'your-api-key-here'` with your actual API key.

3. **Run the App**:
   - Open `index.html` in a web browser.
   - Enter a city name to see the weather.

## Features
- Clean UI with a semi-transparent container
- Dynamic background that changes with the weather
- Error handling for invalid cities
- Default city (Phoenix) on load

## Notes
- The `config.js` file is not included in this repository for security reasons. You must create it with your own API key.
