# Hinsawdd

<div align="center">
  <p float="left">
    <img src="screenshot1.jpg" width="24%" />
    <img src="screenshot2.jpg" width="24%" />
    <img src="screenshot3.jpg" width="24%" />
    <img src="screenshot4.jpg" width="24%" />
  </p>
</div>

A Welsh weather application built with Flutter that provides location-based forecasts through the OpenWeatherMap API.

## Features

- **Automatic Location Detection**: Uses device location to show relevant weather data
- **Real-time Weather Updates**: Fetches current conditions from OpenWeatherMap
- **Multiple Location Search**: Look up weather information for any location
- **Asynchronous Data Loading**: Smooth user experience with loading indicators
- **Bilingual Support**: Available in Welsh and English

## Technology Stack

- **Framework**: Flutter
- **Language**: Dart
- **API**: OpenWeatherMap
- **Device Integration**: Location Services
- **State Management**: Provider

## Installation

1. Clone this repository
   ```
   git clone https://github.com/yourusername/hinsawdd.git
   ```

2. Navigate to the project directory
   ```
   cd hinsawdd
   ```

3. Install dependencies
   ```
   flutter pub get
   ```

4. Add your OpenWeatherMap API key
   - Create a file called `secrets.dart` in the `lib` folder
   - Add the following code:
     ```dart
     const String apiKey = 'YOUR_API_KEY_HERE';
     ```

5. Run the application
   ```
   flutter run
   ```

## Development Journey

This project was developed as part of my Flutter learning journey. Key learning points included:

- Working with RESTful APIs and JSON parsing
- Implementing asynchronous operations in mobile apps
- Managing navigation stacks for multi-screen applications
- Handling device location services
- Creating a responsive UI for different screen sizes

## Future Enhancements

- Weather forecasts for multiple days
- Weather alerts and notifications
- More detailed weather information
- Custom location saving
- Dark mode support

## API Reference

This application uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You'll need to create an account and obtain an API key to use this application.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*"Hinsawdd" means "Weather" in Welsh.*
