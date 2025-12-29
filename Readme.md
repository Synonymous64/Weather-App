# Weather App 🌤️

A responsive and aesthetic weather web application built with **Node.js**, **Express.js**, **EJS**, and **OpenWeather API**. Users can search for any city to get the current weather, temperature in Celsius, and dynamic background images based on the weather conditions.

---

## Features

- Search for any city to get live weather data.
- Displays:
  - Temperature (°C)
  - Weather description
  - City and country
- Dynamic background images depending on weather:
  - Clear, Rain, Clouds, Snow, Mist, Fog
  - Default city-based fallback (e.g., Paris)
- Responsive and visually appealing UI.
- Error handling for invalid city names or API failures.



## Technologies Used

- **Backend:** Node.js, Express.js, Axios
- **Frontend:** HTML, CSS, EJS
- **API:** OpenWeatherMap API (Geocoding & One Call API)



## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app

weather-app/
│
├─ public/
│   ├─ styles.css
│   └─ images/
│       ├─ rain.jpg
│       ├─ sunny.jpg
│       ├─ cloudy.jpg
│       ├─ snow.jpg
│       ├─ mist.jpg
│       ├─ fog.jpg
│       └─ paris.jpg
│
├─ views/
│   ├─ index.ejs
│
├─ index.js
├─ package.json
└─ README.md
