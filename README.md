# Immersive Weather Dashboard

A visually stunning, real-time weather dashboard that provides current conditions, hourly forecasts, and a 7-day outlook. The application features fully dynamic, physics-based animated backgrounds that change to match the live weather, creating an immersive and beautiful user experience.

## 🌐 Live Demo
[Live Demo](https://live-wether-app.netlify.app/) 

---

## ✨ Features
- **Real-time Weather Data**: Fetches live data for any location, including temperature, "feels like," humidity, wind speed, and UV index.  
- **Comprehensive Forecasts**: Displays a 24-hour hourly forecast and a detailed 7-day forecast.  
- **Dynamic Animated Backgrounds**: Fully immersive backgrounds that adapt to live weather conditions:  
  - ☀️ Clear/Sunny: A bright, clear sky with a tracked sun.  
  - 🌙 Clear Night: A dark sky with twinkling stars and a visible moon.  
  - ☁️ Cloudy/Overcast: Smoothly drifting volumetric clouds.  
  - 🌧️ Rain: Physics-based raindrops with splash effects.  
  - ⛈️ Thunderstorm: Heavy rain with dramatic lightning flashes.  
  - ❄️ Snow: Graceful, parallax snowflakes.  
  - 🌫️ Fog/Mist: Dense, moving fog patches.  
- **Accurate Day/Night Cycle**: Tracks sun and moon based on sunrise and sunset times with twilight transitions.  
- **Automatic Geolocation**: Instantly detects user’s location.  
- **Manual City Search**: Search weather for any city worldwide.  
- **Fully Responsive Design**: Optimized for desktop, tablet, and mobile.  
- **Modern UI**: Clean, glassmorphism-style cards.  

--- 
 
## 🛠️ Technologies Used:
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)  
- **Styling**: Tailwind CSS  
- **API**: [WeatherAPI.com](https://www.weatherapi.com/) for real-time data  

---

## 🚀 Getting Started

### Prerequisites
A modern web browser (Chrome, Firefox, Safari, etc.).

### Installation & Setup
1. **Clone the repository**  
   ```bash
   git clone https://github.com/avirajsalunkhe/immersive-weather-dashboard.git
   ```
2. **Get your free API Key**  
   - Sign up at [WeatherAPI.com](https://www.weatherapi.com/signup.aspx).  
   - Copy your API key from the dashboard.  
3. **Add the API Key**  
   - Open `index.html`.  
   - Find this line:  
     ```javascript
     const API_KEY = 'YOUR_API_KEY_HERE'; // <-- PASTE YOUR WeatherAPI.com KEY HERE
     ```  
   - Replace `'YOUR_API_KEY_HERE'` with your actual API key.  
4. **Run the application**  
   - Open `index.html` in your browser.  

---

## 🌐 Deployment

### Deploying to Netlify
1. Ensure your main file is named `index.html`.  
2. Go to [Netlify](https://www.netlify.com/).  
3. Drag and drop your project folder into the deploy area.  
4. Your site will be live within seconds!  

You can also deploy via **Vercel** or **GitHub Pages**.

---

## ©️ Copyright 
This project is created and maintained by **Aviraj Salunkhe**.  

© 2025 [Aviraj Salunkhe](https://www.github.com/avirajsalunkhe/). All Rights Reserved.  
