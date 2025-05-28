# Weather App

A sleek, modern weather application built with React Native that provides real-time weather information for any city around the world.

![Weather App Screenshot](./assets/screenshot.png)

## Features

- **Real-time Weather Data**: Get current weather conditions using the Weatherstack API
- **City Search**: Look up weather information for any city globally
- **Detailed Weather Information**: View comprehensive weather details including:
  - Temperature and "feels like" temperature
  - Weather conditions with icons
  - Humidity and wind speed
  - UV index, visibility, and pressure
  - Precipitation and cloud cover
  - Wind direction
- **Location Details**: Access additional location information such as region, timezone, and coordinates
- **Responsive Design**: Clean, intuitive interface that works across different device sizes
- **Error Handling**: Graceful error management with retry functionality

## Technologies Used

- React Native
- Expo
- Axios for API requests
- Weatherstack API
- JavaScript ES6+
- React Hooks (useState, useEffect)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Weatherstack API key:
```
REACT_APP_WEATHERSTACK_API_KEY=your_weatherstack_api_key_here
```

4. Start the development server:
```bash
npm start
```

5. Run on your preferred platform:
```bash
# For iOS
npm run ios

# For Android
npm run android

# For web
npm run web
```

## Project Structure

```
weather-app/
├── assets/              # Images and app icons
├── App.jsx              # Main application component
├── app.json             # Expo configuration
├── babel.config.js      # Babel configuration
├── index.js             # Entry point
├── package.json         # Dependencies and scripts
└── README.md            # Project documentation
```

## API Reference

This app uses the [Weatherstack API](https://weatherstack.com/) to fetch weather data. You'll need to sign up for a free API key to use this application.

## Future Enhancements

- Weather forecasts for upcoming days
- Geolocation to automatically detect user's city
- Unit conversion (Celsius/Fahrenheit)
- Dark/Light theme toggle
- Weather alerts and notifications
- Favorite locations saving

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Weatherstack API](https://weatherstack.com/) for providing weather data
- [Expo](https://expo.dev/) for the development framework
- [React Native](https://reactnative.dev/) for the mobile application framework
