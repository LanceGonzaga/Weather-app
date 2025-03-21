# Weather App

## Description

This weather app allows users to view the current weather information for any location worldwide. It provides key details such as temperature, weather condition, humidity, and wind speed, all fetched from the OpenWeatherMap API. The app is built with React, leveraging its state and lifecycle management features to provide a dynamic user experience.

## Features

- **Current Weather Data**: Displays the temperature, humidity, wind speed, and weather condition (e.g., sunny, rainy, etc.).
- **Search by Location**: Allows users to search for the weather in any city globally.
- **Temperature Units**: Shows the temperature in Celsius
- **Responsive Design**: The app is designed to be mobile-friendly and adapts to different screen sizes.

## Usage of useState and useEffect

- **useState**: Manages state in a functional component. In your case, it holds the weather data, loading state, and error messages.
- **useEffect**: Runs side effects, such as fetching data. In your case, it triggers the search function on the initial render to fetch weather data for "Cainta."

## Hosted Vercel Page Link

- https://my-weather-app-v1.vercel.app/

## Set up if you download the folder

1. download the files or clone it then open the folder using VScode
2. run ``npm install`` in the terminal
3. run ``npx vite`` to start and get the webpage link


## API Source

The weather data is fetched using the [OpenWeatherMap API](https://openweathermap.org/api). You will need to sign up for an API key to use this service. The API provides detailed weather data for a wide range of locations.
