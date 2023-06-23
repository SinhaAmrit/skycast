# Sky Cast Application

Sky Cast is a weather application that provides users with real-time weather information for a specific location. It allows users to input the country and city of their choice and retrieve weather data such as temperature, weather description, and additional information.

## Features

- Input Location: Users can enter the country and city of their choice to retrieve weather information for that location.
- Weather Information: The application displays the current weather information, including temperature, weather description, and additional details such as feels like temperature, humidity, longitude, and latitude.
- Visual Representation: The application uses an icon to represent the weather conditions visually, enhancing the user experience.
- Responsive Design: The application is designed to be responsive, ensuring a consistent user experience across different devices and screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API

## Usage

1. Open the `index.html` file in a web browser.
2. In the location input section, enter the desired country and city.
3. Click the "Check" button to retrieve the weather information for the specified location.
4. The application will display the current temperature, weather description, and additional details.

## Customization

To customize the Sky Cast application, you can make changes to the following files:

- `index.html`: Modify the HTML structure and content to add or remove elements as needed.
- `css/style.css`: Adjust the CSS styles to change the visual presentation of the application.
- `js/main.js`: Modify the JavaScript code to add new functionality or modify the existing behavior.

## API Integration

The Sky Cast application integrates with the OpenWeather API to fetch real-time weather data. To use the OpenWeather API with your own API key, modify the `main.js` file and replace the placeholder API key with your valid API key.

```javascript
const apiKey = 'YOUR_API_KEY_HERE';

## License

This project is licensed under the MIT license.