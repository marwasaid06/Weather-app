# WeatherApp

## Overview
**WeatherApp** is a Java-based desktop application that provides real-time weather information for any specified location using the OpenWeatherMap API. It features both current weather details and an 8-day forecast, with options to switch between Celsius and Fahrenheit units and easy access to your search history.

## Features
- **Current Weather:** Retrieve and display real-time weather data for a specified location.
- **8-Day Forecast:** View an 8-day weather forecast with detailed daily conditions.
- **Unit Conversion:** Switch between Celsius and Fahrenheit temperature units.
- **Search History:** Automatically save and access previously searched locations for quick reference.

## Prerequisites
- Java Development Kit (JDK) 8 or higher.
- An OpenWeatherMap API key.

## Installation
1. **Clone the Repository:**
   
   git clone https://github.com/your-repo/weather-app.git
   cd weather-app
   ```
2. **Set Up the API Key:**
   - Replace `API_KEY` in `WeatherAPIService.java` with your OpenWeatherMap API key.

## Usage
1. **Compile the Java Files:**
   ```bash
   javac WeatherApp.java WeatherAPIService.java
   ```
2. **Run the Application:**
   
   java WeatherApp
   ```

## Class Overview

### WeatherApp
This class is responsible for creating the graphical user interface (GUI) using Swing components. Key elements include:
- `locationField` – Input field for entering the location.
- `weatherInfoArea` – Area to display the current weather details.
- `iconLabel` – Label to display weather icons.
- `forecastLabel` – Label to display the 8-day weather forecast.
- `unitComboBox` – Dropdown for toggling between Celsius and Fahrenheit.
- `searchHistoryList` – List to display and manage search history.

### WeatherAPIService
This class manages the API interactions with OpenWeatherMap, including:
- `getWeather(String location)` – Fetches current weather data for the specified location.
- `getForecast(String location)` – Retrieves weather forecast data for the specified location.

## Example Usage
1. **Search Weather:**
   - Enter a location (e.g., "London") in the text field.
   - Click "Search" to fetch and display the weather data.
   - View current weather details such as temperature, humidity, wind speed, and overall conditions.
   - Review the 8-day forecast displayed below the current conditions.

2. **Additional Features:**
   - Use the combo box to toggle between Celsius and Fahrenheit.
   - Access and revisit previous searches from the search history list by double-clicking an entry.

## Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is licensed under the MIT License.
