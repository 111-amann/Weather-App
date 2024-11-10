# Weather App

This is a simple weather application that allows users to check the current weather conditions for any city. The app fetches real-time weather data using the OpenWeather API and displays details like temperature, wind speed, humidity, and visibility. The UI is designed to be clean and user-friendly.

## Demo

![Weather App Screenshot](screenshot.png) <!-- Add a screenshot of your app here -->

## Features

- **City-based Search**: Users can enter a city name to view the current weather.
- **Weather Information**: Displays temperature, weather condition, wind speed, humidity, and visibility.
- **Dynamic Icons**: Weather conditions are represented with icons, making it easy to understand at a glance.
- **Responsive Design**: The app is designed to be responsive on various screen sizes.

## Tech Stack

- **HTML, CSS**: For structure and styling.
- **JavaScript**: For dynamic functionality and API integration.
- **OpenWeather API**: For fetching real-time weather data.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   
2.**Navigate into the project directory**:
  cd weather-app
  
3.**Get an API key from OpenWeather**:
  Sign up at OpenWeather and obtain an API key.
  
4.**Add your API key**:
  Open script.js and replace the apiKey variable value with your own API key:
  const apiKey = 'YOUR_API_KEY_HERE';
  
5.**Open index.html in your browser**:
  Simply double-click index.html or use a live server in your editor.

Usage
Open the app and enter the name of a city in the search bar.
Click the search button or press "Enter" to display the weather details for the specified city.
The app will show:
Current temperature
Weather condition (with icon)
Wind speed
Humidity level
Visibility
Code Overview
index.html: Contains the HTML structure, including input fields for city name and placeholders for weather information.
style.css: Provides styling for the app layout, making it visually appealing and responsive.
script.js: Handles the fetching of weather data from the OpenWeather API and updating the DOM with the retrieved data.
Example
If you enter "Delhi" as the city name, the app will display the current weather in Delhi, showing temperature, condition, and other details.

License
This project is open-source and available under the MIT License. Feel free to use and modify it as you like.

Note: Replace "YOUR_API_KEY_HERE" in script.js with your actual OpenWeather API key for the app to function correctly.
