

To run the Weather App locally on your machine, follow these steps:

1. Make sure you have Node.js installed on your machine.

2. Clone this repository or download the source code.
   ```
     git clone https://github.com/Mohanrf/weather.git
   ```
3. Open a terminal and navigate to the project directory.
   ```
     cd weather
   ```
4. Run the following command to install the project dependencies:
   ```
     npm install
   ```
   
5. Obtain an API key:
   - Sign up for an account on a weather API provider (e.g., OpenWeatherMap, Weatherbit, AccuWeather) prefarably OpenWeatherMap which is used in this project.
   - Generate an API key.

6. Set up environment variables:
   - Create a ' .env ' file in the root directory of the project.
   - Add the following line to the .env file:
   ```
     REACT_APP_API_KEY= "YOUR_API_KEY"
   ```

7. Start the development server with the following command:
   ```
     npm start
   ```
8. Open the app in your browser:
   - Open http://localhost:3000 in your preferred browser.
   - The Weather App should now be running and accessible in your browser.
  
## API

This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. OpenWeatherMap provides a wide range of weather information, including current weather conditions, forecasts, and historical data. It offers various API endpoints and data formats to suit different needs.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
