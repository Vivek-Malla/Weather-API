
Weather Application

This Weather Application allows users to check the current weather for any city and also provides functionality to convert city names into geographical coordinates using the OpenWeather API's Geocoding feature.

eatures

- **Weather Widget**: Displays current weather information for a specified city.
- **Geocoding API**: Converts city names into geographical coordinates (latitude and longitude).
- **User-Friendly Interface**: Simple and intuitive design for easy navigation.

Technologies Used

- React.js
- Axios (for making API calls)
- OpenWeather API
- CSS for styling

Installation

To get started with the Weather Application, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd weather-app
   ```

3. **Install the dependencies**:
   ```bash
   npm install
   ```

4. **Replace API Key**:
   - Create an account on [OpenWeather](https://openweathermap.org/) and get your API key.
   - Replace the placeholder `YOUR_API_KEY` in `WeatherWidget.js` and `GeocodingPage.js` with your actual API key.

## Usage

1. Start the development server:
   ```bash
   npm start
   ```

2. Open your web browser and go to `http://localhost:3000`.

3. Use the **Weather Widget** to enter a city name and view the current weather conditions.

4. Navigate to the **Geocoding API** page to convert city names into geographical coordinates.

## API Information

### Weather Widget API

- **API Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Parameters**:
  - `q`: City name.
  - `appid`: Your unique API key.
  - `units`: Metric or imperial (e.g., `metric` for Celsius).

### Geocoding API

- **API Endpoint**: `http://api.openweathermap.org/geo/1.0/direct`
- **Parameters**:
  - `q`: City name, state code, country code (comma-separated).
  - `appid`: Your unique API key.
  - `limit`: Optional limit on the number of results (default is 5).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeather](https://openweathermap.org/) for providing the weather and geocoding APIs.
- [React](https://reactjs.org/) for the powerful front-end library.

---

Feel free to customize this README file further based on your project specifics. Good luck with your GitHub repository! If you need any more modifications or additions, let me know!
