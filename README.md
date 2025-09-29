Immersive Weather Dashboard
A visually stunning, real-time weather dashboard that provides current conditions, hourly forecasts, and a 7-day outlook. The application features fully dynamic, physics-based animated backgrounds that change to match the live weather, creating an immersive and beautiful user experience.

Live Demo: https://your-site-name.netlify.app/ (Replace with your actual Netlify link)

✨ Features
Real-time Weather Data: Fetches live data for any location, including temperature, "feels like," humidity, wind speed, and UV index.

Comprehensive Forecasts: Displays a 24-hour hourly forecast and a detailed 7-day forecast.

Dynamic Animated Backgrounds: The entire background animates to reflect the current weather conditions:

☀️ Clear/Sunny: A bright, clear sky with a tracked sun.

🌙 Clear Night: A dark sky filled with gently twinkling stars and a visible moon.

☁️ Cloudy/Overcast: Soft, volumetric clouds drift smoothly across the sky.

🌧️ Rain: Physics-based raindrops fall, influenced by wind speed, and create a splash effect.

⛈️ Thunderstorm: A dark, stormy scene with heavy rain and dramatic lightning flashes.

❄️ Snow: Graceful snowflakes drift down, influenced by wind, creating a parallax effect for depth.

🌫️ Fog/Mist: Dense, slowly moving fog patches create an atmospheric effect.

Accurate Day/Night Cycle: The animation system tracks the sun and moon based on local sunrise and sunset times, with beautiful gradient transitions for twilight hours.

Automatic Geolocation: Detects the user's location on page load to provide instant local weather.

Manual City Search: Allows users to search for weather information for any city worldwide.

Fully Responsive Design: The interface is optimized for a seamless experience on desktops, tablets, and mobile devices.

Modern UI: A clean and intuitive user interface with glassmorphism-style cards.

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS

API: WeatherAPI.com for real-time weather data.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
You need a modern web browser like Google Chrome, Firefox, or Safari.

Installation & Setup
Clone the repository:

git clone [https://github.com/avirajsalunkhe/immersive-weather-dashboard.git](https://github.com/avirajsalunkhe/immersive-weather-dashboard.git)

Get your free API Key:

Go to WeatherAPI.com and sign up for a free account.

You will get an API key on your dashboard.

Add the API Key to the project:

Open the index.html file in your code editor.

Find the following line in the <script> section (around line 230):

const API_KEY = 'YOUR_API_KEY_HERE'; // <-- PASTE YOUR WeatherAPI.com KEY HERE

Replace 'YOUR_API_KEY_HERE' with the key you obtained from WeatherAPI.

Run the application:

Simply open the index.html file in your web browser.

🌐 Deployment
This project can be easily deployed using services like Netlify, Vercel, or GitHub Pages.

Deploying to Netlify
Prepare your file: Ensure your main HTML file is named index.html.

Drag & Drop: Go to your Netlify dashboard and simply drag the project folder (containing index.html) into the deploy area.

Your site will be live in a few seconds!

©️ Copyright
This project is created and maintained by Aviraj Salunkhe.

© 2025 Aviraj Salunkhe. All Rights Reserved.
