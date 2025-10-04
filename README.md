# ☀️ Weather App

A simple **Weather App** built with **HTML, CSS, and Vanilla JavaScript**.  
It fetches real-time weather data from **OpenWeatherMap API** and displays the current temperature, weather description, and icon for any city.

---

## 🚀 Features
- 🌍 **Search by City** – Enter any city name to get current weather.
- 🌡️ **Display Temperature** – Shows temperature in Celsius.
- 🌤️ **Weather Description** – Describes current weather conditions.
- 🖼️ **Weather Icons** – Shows corresponding weather icon.
- ⚡ **Error Handling** – Handles invalid city names and network errors.
- ⌨️ **Keyboard Support** – Press Enter to search.

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6+)**
- **OpenWeatherMap API**

---


---

## 🖥️ Setup & Usage
### 1. Clone or Download the Project
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
<div class="weatherApp">
  <input type="text" class="searchBox" placeholder="Enter city name">
  <button class="submit">Search</button>
  <p id="error" class="hidden text-red-500"></p>

  <div class="weatherContainer hidden">
    <h2 id="city"></h2>
    <img class="weatherIcon" src="" alt="">
    <p id="temp"></p>
    <p id="description"></p>
  </div>
</div>

<script src="script.js"></script>

