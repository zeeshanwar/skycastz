🌦️ SkyCastz -  Live Weather App

A React.js-based Live Weather Application that fetches real-time weather data using the Open-Meteo API. The app provides current, hourly, and daily weather forecasts with dynamically updated weather icons, time zone-based updates, and theme customization.

🚀 Features

✅ Real-time Weather Updates – Fetches live weather conditions based on user input.

✅ Hourly & Daily Forecasts – Displays weather forecasts for the next 48 hours and 15 days.

✅ Dynamic Weather Icons – Icons adjust based on day/night detection using API-provided timestamps.

✅ Time Zone Synchronization – Ensures weather updates align with the selected location’s time zone.

✅ Theme Mode Support – Supports dark/light mode, stored in local storage.

✅ Loading Screen with Quotes – Displays random weather-related quotes while fetching data.

✅ Optimized API Calls – Caches searched locations to prevent redundant API requests.

📦 Installation

1️⃣ Clone the repository:

 git clone https://github.com/yourusername/weather-app.git
 cd weather-app

2️⃣ Install dependencies:

 npm install

3️⃣ Run the app:

 npm run dev

⚙️ Technologies Used

React.js – Frontend framework

Axios – API calls

Tailwind CSS – UI Styling

Open-Meteo API – Weather Data

LocalStorage – Theme & user preferences storage

🔧 How It Works

1️⃣ Fetching Weather Data

Uses Open-Meteo’s Geocoding API to get latitude/longitude based on the entered location.

Fetches weather data using the forecast API with time zone auto-detection.

2️⃣ Dynamic Weather Icons

Weather icons update dynamically based on weather code & time of the day.

Uses hourly timestamps to determine day/night instead of system time.

3️⃣ Theme Mode

Detects system theme preference initially.

Allows users to toggle between dark/light modes.

Stores preference in LocalStorage.

🛠️ Future Enhancements

🚀 Add Current Location Detection using browser geolocation API.
🚀 Improve UI Animations for a smoother experience.
🚀 Expand Weather Insights – Air quality, UV index warnings, and more.

🌟 Show Some Love
If you find this project helpful, please ⭐ star the repository and contribute! 😃
