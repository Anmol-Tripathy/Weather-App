# 🌦️ Weather App

A modern and responsive weather forecasting web application built using **HTML**, **CSS**, and **JavaScript**. It uses the **OpenWeatherMap API** to fetch real-time weather data and display it in an attractive, user-friendly interface.

---

## 🔍 Features

- 🌍 Search for any city to get live weather updates
- 🌡️ Displays:
  - Temperature
  - City name
  - Humidity
  - Wind speed
  - Matching weather icons (Clear, Clouds, Rain, Drizzle, Mist)
- ⚠️ Error message for invalid or unknown city names
- ⌨️ Supports both **button click** and **Enter key** to trigger search
- 🎨 Gradient-based card UI with mobile responsiveness

---

## ⚙️ Tech Stack

- **HTML5** – Structure of the webpage
- **CSS3** – Styling with modern gradients and flexbox
- **JavaScript (ES6)** – Logic, API calls, and DOM manipulation
- **OpenWeatherMap API** – Real-time weather data

---

## 🛠️ How It Works

1. User enters a city name.
2. The app sends an API request to OpenWeatherMap using `fetch()`.
3. If the city is found:
   - Updates weather info dynamically (temp, humidity, wind).
   - Weather icon changes based on condition.
4. If the city is not found (404):
   - Displays an error message and hides the weather data.
5. App loads with a **default city (Delhi)** on first load.

---

## 📁 Project Structure
---

## 🚀 Future Improvements

- 🌐 Add geolocation-based auto weather detection
- 💾 Save search history using `localStorage`
- 🌙 Add light/dark mode toggle
- 🎞️ Loading spinner or transition while fetching data

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## ✨ Author

Developed with ❤️ by **Anmol Tripathy**
