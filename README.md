# Weather Tracking Dashboard

A robust Python-based CLI application designed to fetch real-time weather data and maintain historical records for trend analysis.

## Features
- **Real-Time Data:** Fetches live weather (Temperature, Humidity, Wind Speed, Condition) using OpenWeatherMap API.
- **Data Persistence:** Automatically stores search history in both JSON and CSV formats.
- **Advanced Analysis:** View past records with custom filters (by City or Date) and analyze temperature trends.
- **Smart Alerts:** Built-in alerts for rain, thunderstorms, heatwaves, and freezing temperatures.
- **Bonus Features:** - Multi-city tracking.
    - Auto-refresh mode for real-time monitoring.
    - Clean, color-coded CLI interface.

## Prerequisites
- Python 3.x installed.
- `requests` library: `pip install requests`
- A free API key from [OpenWeatherMap](https://openweathermap.org/api).

## Setup & Usage
1. Clone this repository.
2. Create a `config.json` file in the main folder with your API key:
   ```json
   {
     "api_key": "YOUR_API_KEY_HERE"
   }

Run the application:

Bash
python Task 13 Weather dashboard.py

## Demo
A 1-minute demonstration of this dashboard is available. Please visit the :
       Weather dashboard demo video.mp4
