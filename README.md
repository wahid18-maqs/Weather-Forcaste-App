# Weather Forecast App

A simple and interactive weather forecast application built using Python and Tkinter. This app fetches and displays current weather data and a 7-day forecast for any city.

## Screenshot
   1. In vs code
        ![screenshot_1](https://github.com/user-attachments/assets/828c27ff-797c-4fc6-8ed9-ed747d3e5771)

   2. In python IDLE

       ![weather app _screenshot](https://github.com/user-attachments/assets/7ed4415b-7643-4fd1-994a-79fc24a18db6)


## Features

- Displays current temperature, humidity, pressure, wind speed, and weather description.
- Shows 7-day weather forecast with day and night temperatures and weather icons.
- Fetches data using OpenWeatherMap API.
- Uses geolocation to determine latitude and longitude based on city name.
- Displays local time and timezone of the searched city.

## Tech Stack

- **Python**: Programming language
- **Tkinter**: GUI framework for Python
- **Geopy**: Library for geocoding
- **TimezoneFinder**: Library for finding timezone based on coordinates
- **Requests**: HTTP library for API calls
- **Pytz**: Library for timezone calculations
- **PIL (Pillow)**: Image processing library

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/wahid18-maqs/Weather-Forcaste-App-.git

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

3.Get your OpenWeatherMap API key from OpenWeatherMap and replace your_api_key in the getWeather function with your actual API key.

4.Run the application:
 ```bash
   python weather_app.py
 ```
## Usage
   1.Enter the city name in the search box.

   2.Click the search icon.

   3.View the current weather and 7-day forecast for the city.

## Contribution
Follow the standard guidelines for contributions and open issues for feature requests or bug reports.
Feel free to reach out for any questions or suggestions regarding this project.   
