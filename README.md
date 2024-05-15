# Weather App

This is a simple weather application built using HTML, CSS, and JavaScript. It allows users to search for the current weather conditions of any location around the world.

## Features

- Search for the weather of any location by entering the city name or zip code.
- Displays the current temperature, weather condition (sunny, cloudy, rainy, etc.), location name, and date/time.
- Responsive design that works well on desktop and mobile devices.

## Technologies Used

- HTML
- CSS
- JavaScript
- WeatherAPI (https://www.weatherapi.com/) to fetch weather data

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository or download the source code.
2. Open the `index.html` file in a web browser.
3. Enter a location in the search field and press the "Search" button.

Alternatively, you can use a local development server like Live Server (Visual Studio Code extension) to run the application.

## API Key

This application uses the WeatherAPI to fetch weather data. You will need to obtain an API key from their website (https://www.weatherapi.com/) and replace the existing key in the `index1.js` file with your own key.

In the `fetchData` function, update the following line with your API key:

```js
const url = `https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${target}`;
