# Weather App

A simple weather application built with HTML, CSS, and JavaScript using the OpenWeatherMap API.

## Features

- Search weather by city name
- Displays temperature, humidity, wind speed, and weather icon
- Responsive design

## Setup

1. **Clone this repository:**
   ```
   git clone https://github.com/lilabshaar/weather-app.git
   ```

2. **Add your OpenWeatherMap API key:**
   - Create a file named `config.js` in the project folder.
   - Add this code:
     ```javascript
     const apiKey = "YOUR_API_KEY";
     ```
   - Make sure `config.js` is listed in `.gitignore`.

3. **Add weather icons:**
   - Place weather icon images in the `images` folder.
   - The folder is ignored by git, so you need to add your own icons.

4. **Open `index.html` in your browser.**

## Notes

- Do **not** share your API key publicly.
- The `images` folder and `config.js` are excluded from version control for
