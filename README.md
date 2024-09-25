# React Weather App

A simple and intuitive Weather Application built using React.js. This application fetches real-time weather data and displays it in a user-friendly interface.

## Features

- Fetches current weather data using a weather API
- Displays temperature, weather conditions, and location
- Responsive design for mobile and desktop views

## Installation

### /public

* index.html: The main HTML file that is served when the app is run. This file includes the root <div> where the React application is mounted.

### /src

* /api
* weatherApi.js: Contains functions to fetch weather data from the API. This file abstracts the API calls and returns the necessary data to the components.

## /components

* WeatherCard.js: A React component that displays the weather information. It includes temperature, weather conditions, and the location name. This component receives props from the main App.js file.
* App.css: The main CSS file for styling the App.js component.
* App.js: The root component of the application. It manages the state, handles user input, and renders the WeatherCard component.
* index.css: The main CSS file for global styles.
* index.js: The entry point of the React application. It renders the App.js component into the root <div> in index.html.

## Root Files
* .gitignore: Specifies which files and directories should be ignored by Git.
* package.json: Lists the project dependencies and scripts.
* README.md: The file you are currently reading. It provides an overview of the project.
## Usage
1. Open the application in your browser.
2. Enter a city name in the search bar.
3. View the current weather data for the specified city.

# License
This project is licensed under the MIT License.