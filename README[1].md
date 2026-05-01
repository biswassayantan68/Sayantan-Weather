# 🌦 WeatherDrift — Live Weather Tracker

A sleek, production-grade weather tracker built with **vanilla JavaScript**, **HTML5**, and **CSS3**. Fetches real-time weather and 5-day forecasts using the **OpenWeatherMap API**.

![WeatherDrift Preview](https://i.imgur.com/placeholder.png)

## ✨ Features

- 🔍 **City Search** — Look up current weather anywhere in the world
- 📍 **Geolocation** — Detect and use your current location
- 🌡 **°C / °F Toggle** — Switch temperature units on the fly
- 📅 **5-Day Forecast** — Daily outlook with weather icons
- 🕓 **Search History** — Recently searched cities saved via `localStorage`
- 🎨 **Stunning UI** — Brutalist dark aesthetic with animated loading states

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/weather-tracker.git
cd weather-tracker
```

### 2. Get a Free API Key

1. Sign up at [openweathermap.org](https://openweathermap.org/api)
2. Go to **API keys** in your account dashboard
3. Copy your free API key (it activates within ~10 minutes)

### 3. Add Your API Key

Open `app.js` and replace line 9:

```js
const API_KEY = 'YOUR_API_KEY_HERE'; // ← Replace this
```

with your actual key:

```js
const API_KEY = 'abc123yourrealkeyhere';
```

### 4. Open in Browser

No build tools needed! Just open `index.html` in any modern browser:

```bash
open index.html
# or double-click the file in your file explorer
```

## 📁 Project Structure

```
weather-tracker/
├── index.html   # App markup
├── style.css    # All styles (CSS variables, dark theme, responsive)
├── app.js       # All logic (API calls, rendering, localStorage)
└── README.md    # This file
```

## 🌐 Deploy to GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your app will be live at `https://YOUR_USERNAME.github.io/weather-tracker`

## 🛠 Tech Stack

| Layer     | Tech                          |
|-----------|-------------------------------|
| Markup    | HTML5                         |
| Styles    | CSS3 (Custom Properties, Grid)|
| Logic     | Vanilla JavaScript (ES2020+)  |
| Data      | OpenWeatherMap API (Free)     |
| Storage   | `localStorage` (search history)|
| Fonts     | Google Fonts (Bebas Neue, DM Sans, JetBrains Mono) |

## 📡 API Endpoints Used

| Endpoint                  | Purpose              |
|---------------------------|----------------------|
| `/data/2.5/weather`       | Current weather      |
| `/data/2.5/forecast`      | 5-day / 3-hour forecast |

Both endpoints are available on the **free tier** (60 calls/minute).

## 📄 License

MIT — free to use, modify, and distribute.
