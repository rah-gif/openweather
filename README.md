# 🌤️ OpenWeather App

A simple, beautiful weather application built with HTML, CSS, and Vanilla JavaScript.

## 🚀 Features

- **Current Weather**: Get real-time weather updates by city name.
- **Geolocation**: Use your current location to fetch weather data.
- **5-Day Forecast**: View detailed forecast for the week.
- **Responsive Design**: Looks great on desktop and mobile.

## 🛠️ Setup Instructions

To run this project locally, you need an API key from OpenWeatherMap.

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/rah-gif/openweather.git
    cd openweather
    ```

2.  **Configure API Key**:
    - Rename `config.example.js` to `config.js`:
      ```bash
      mv config.example.js config.js
      # On Windows: ren config.example.js config.js
      ```
    - Open `config.js` and paste your API Key:
      ```javascript
      const CONFIG = {
        API_KEY: "your_actual_api_key_here",
      };
      ```
    - Get a free key at [OpenWeatherMap](https://openweathermap.org/api).

3.  **Open `index.html`** in your browser.

## 🔒 Security Note (Important)

This is a **frontend-only** application. This means the API key is technically visible to anyone who inspects the website code.

To secure your key:

1.  Go to your [OpenWeatherMap Dashboard](https://home.openweathermap.org/api_keys).
2.  If you suspect your key is being misused, **Generate** a new key and delete the old one.

**Note**: The free plan may not support strict referrer restrictions. Keeping your key out of public GitHub repositories (using `.gitignore`) is the best defense.

## 📄 License

This project is open-source and available under the MIT License.
