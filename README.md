# Weather Notifier

This Python script fetches current weather data for a specified location, displays it as a desktop notification every hour, and includes information such as temperature, pressure, and sunrise/sunset times.

## Features

- Hourly weather updates with notifications
- Detailed weather information (temperature, pressure, humidity, etc.)
- Easy configuration with environment variables

## Requirements

- `requests`
- `plyer`
- `dotenv` (optional, for environment variables)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Damianzoub/weather_notifier.git
    cd weather_notifier
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up your API key:
   - Create a `.env` file in the project root and add your OpenWeather API key:
     ```
     OPENWEATHER_API_KEY=your_api_key_here
     ```

## Usage

Run the script:
```bash
python Weather_API.py
