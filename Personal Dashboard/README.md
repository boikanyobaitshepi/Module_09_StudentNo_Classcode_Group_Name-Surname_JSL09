## Features
1. **Background Image and Author**: Fetches a random landscape nature image from Unsplash API and sets it as the background image of the webpage. It also displays the author's name.
2. **Cryptocurrency Data**: Retrieves data about Dogecoin from the CoinGecko API and displays its name, current price, 24-hour high, and 24-hour low.
3. **Current Time**: Updates the displayed time every second.
4. **Weather Information**: Fetches weather data based on the user's geolocation from the OpenWeatherMap API and displays the weather icon, temperature, and city name.

## Manifest File
The `manifest.json` file contains metadata about the extension, including its name, version, description, and other important details required for its functionality.

### Key Components
1. **Manifest Version**: Specifies the version of the Chrome extension manifest format. In this case, it's version 3.
2. **Name**: The name of the extension, which is "Personal Dashboard".
3. **Version**: The version number of the extension, set to "1.0.0".
4. **Description**: Provides a brief description of the extension, indicating that it's created for practicing asynchronous JavaScript.
5. **Action**: Specifies the default icon for the extension.
6. **Chrome URL Overrides**: Overrides the default new tab page with the specified HTML file (`index.html` in this case).

