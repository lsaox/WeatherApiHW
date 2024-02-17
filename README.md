 ## Weather Dashboard

This weather dashboard application allows users to search for cities and view current and future weather conditions. The application uses the OpenWeather API to retrieve weather data and `localStorage` to store persistent data.

### Getting Started

To get started, clone the repository and install the dependencies:

```
git clone https://github.com/your-username/weather-dashboard
cd weather-dashboard
npm install
```

### Running the Application

To run the application, start the development server:

```
npm start
```

The application will be available at `http://localhost:3000`.

### Usage

To use the application, enter a city name in the search box and click the "Search" button. The current and future weather conditions for the city will be displayed.

The current weather conditions are displayed in the "Current Weather" section. This section includes the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the wind speed.

The future weather conditions are displayed in the "5-Day Forecast" section. This section includes the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity for the next five days.

### Storing Persistent Data

The application uses `localStorage` to store persistent data. This data includes the search history and the current weather conditions for the last searched city.

The search history is stored in the `localStorage` item `searchHistory`. This item is an array of city names.

The current weather conditions for the last searched city are stored in the `localStorage` item `currentWeather`. This item is an object with the following properties:

* `city` (string): The name of the city.
* `date` (string): The date of the weather conditions.
* `icon` (string): The icon representation of the weather conditions.
* `temperature` (number): The temperature in Fahrenheit.
* `humidity` (number): The humidity in percentage.
* `windSpeed` (number): The wind speed in miles per hour.

* Screenshot of Deployed Application:
* ![Screenshot (16)](https://github.com/lsaox/WeatherApiHW/assets/138525227/c8503144-fe15-49eb-8f94-21bea3da888b)

Link to Deployed Application : 
https://lsaox.github.io/WeatherApiHW/
