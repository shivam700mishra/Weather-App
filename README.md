# Weather App

A simple React-based weather application that displays current weather information for any city using the OpenWeatherMap API.

## Features

- Search for weather by city name
- Displays temperature, humidity, wind speed, and weather icon
- Responsive and modern UI
- Default weather shown for London on load

## Screenshots

![alt text](<Screenshot 2025-06-29 133435.png>)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```
   VITE_APP_ID=your_openweathermap_api_key
   ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

5. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

```
.
├── public/
│   └── vite.svg
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── assets/
│   │   ├── clear.png
│   │   ├── cloud.png
│   │   ├── drizzle.png
│   │   ├── humidity.png
│   │   ├── rain.png
│   │   ├── search.png
│   │   ├── snow.png
│   │   └── wind.png
│   └── components/
│       ├── Weather.jsx
│       └── Weather.css
├── .env
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Usage

- Enter a city name in the search bar and click the search icon to view the weather.
- The app will display temperature, humidity, wind speed, and a weather icon.

## Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [OpenWeatherMap API](https://openweathermap.org/api)

