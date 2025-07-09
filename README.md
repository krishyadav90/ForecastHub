# 🌦️ Weather Forecast Web App

Welcome to **ForecastHub** – a modern, interactive, and responsive web application that delivers **real-time weather updates** for any city across the globe! Powered by the **OpenWeatherMap API**, this app combines sleek design with powerful features for a personalized weather experience.

---

## 🚀 Deploy to Vercel

This project is optimized for Vercel deployment with secure environment variable handling.

### Quick Deploy
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/forecast-hub)

### Manual Deployment Steps:

1. **Fork this repository** to your GitHub account

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Sign in with your GitHub account
   - Click "New Project" and import your forked repository

3. **Set Environment Variable**:
   - In your Vercel project dashboard, go to Settings → Environment Variables
   - Add a new variable:
     - **Name**: `OPENWEATHER_API_KEY`
     - **Value**: Your OpenWeatherMap API key
     - **Environment**: Production (and Preview if needed)

4. **Deploy**: Click "Deploy" and your app will be live!

### Local Development:
```bash
# Clone the repository
git clone https://github.com/yourusername/forecast-hub.git
cd forecast-hub

# Install Vercel CLI (if not already installed)
npm i -g vercel

# Set up environment variables
cp .env.local.example .env.local
# Edit .env.local and add your API key

# Start development server
vercel dev
```

---

## ✨ Key Features

* 🔴 **Real-Time Weather**
  Get live updates on temperature, humidity, wind speed, pressure, and more.

* 🕒 **Hourly + 3-Day Forecast**
  View detailed hourly trends and summarized 3-day forecasts.

* 📍 **Geolocation Support**
  Auto-detects your current location to show hyper-local weather.

* 🛠️ **Customizable Widgets**
  Select which metrics (AQI, sunrise, sunset, etc.) you want to display.

* 🌐 **Multilingual**
  Supports English, Hindi, Russian, and Japanese with live translations.

* 🎨 **Theme Options**
  Choose from Blue, Green, Purple themes, and toggle Light/Dark mode.

* ⛅ **Dynamic Backgrounds**
  Background animations react to weather conditions – sunny, rainy, cloudy, etc.

* 📱 **Responsive Design**
  Fully optimized for all devices – phones, tablets, and desktops.

* 🌬️ **Air Quality Index**
  View AQI with clear color-coded levels (Good, Moderate, Poor).

* 🔄 **Auto Refresh**
  Weather updates automatically every 15 minutes.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3** – Structured using Tailwind CSS for sleek, modular styles
* **JavaScript** – Handles API communication and UI interactivity
* **OpenWeatherMap API** – Main source for weather, forecast, and AQI data
* **Particles.js** – Adds animated, weather-based background visuals
* **Weather Icons** – Custom icons for each weather state
* **Google Fonts** – Uses “Inter” font for clean, modern typography

---

## 🚀 Getting Started

### 🔑 Prerequisites

* A modern browser (Chrome, Edge, Firefox, Safari)
* An internet connection
* A **free API key** from [OpenWeatherMap](https://openweathermap.org/api)

### 📥 Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/weather-forecast-app.git

# 2. Navigate to the folder
cd weather-forecast-app
```

### 🔧 Setup API Key

* Open `index.html`
* Locate this line inside the `<script>` tag:

  ```js
  const apiKey = 'YOUR_API_KEY_HERE';
  ```
* Replace it with your actual API key from OpenWeatherMap.

### 🌐 Launch the App

* Simply open `index.html` in a browser
* Or run with **Live Server** in VS Code for a local server experience

---

## 📋 How to Use

| Action                | Description                                           |
| --------------------- | ----------------------------------------------------  |
| 🏙️ Enter City        | Type a city and press Enter or click **Get Weather**  |
| 📍 Use Location       | Auto-fetch weather for your current position         |
| 🌡️ Toggle Units      | Switch between Celsius °C and Fahrenheit °F           |
| 🎨 Change Theme       | Choose from color themes and Dark/Light modes        |
| 🛠️ Customize Widgets | Enable or disable metrics to display                  |
| 🌐 Switch Language    | Pick from English, Hindi, Russian, Japanese          |
| 📅 View Forecasts     | Scroll through hourly and 3-day summaries            |

---

## 📂 File Structure

```
weather-forecast-app/
├── index.html       # Main HTML + JS + Tailwind styles
├── README.md        # Project documentation
```

---

## 🎨 Customization

* **Add Themes:**
  Modify `:root` CSS variables and update the `setTheme()` function.

* **New Languages:**
  Extend the `labels` object with translations.

* **More Widgets:**
  Add entries to `selectedWidgets[]` and enhance the `displayWeather()` logic.

* **Weather Icons:**
  Expand `customIcons` with more SVGs or icon classes.

---

## ⚠️ Limitations

| Constraint         | Description                                           |
| ------------------ | ----------------------------------------------------- |
| 🌐 API Dependency  | Needs internet + valid OpenWeatherMap API key         |
| ⏳ Rate Limits      | Free API tier has request limits                      |
| 📍 Geolocation     | Requires user permission, may not work on all devices |
| 📅 Forecast Window | Hourly forecast limited to 3 days by API constraints  |

---

## 🧰 Troubleshooting

* ❌ **City Not Found**
  Check for typos or try a nearby major city.

* 🔑 **Invalid API Key**
  Double-check your key and quota usage.

* 🌐 **No Weather Data**
  Ensure your device is online and refresh the page.

* 📍 **Geolocation Fails**
  Enable location services in your browser settings.

---

## 🤝 Contributing

We welcome contributions! 💪
To contribute:

```bash
# Fork the repo
# Create a feature branch
git checkout -b feature/your-feature

# Make changes & commit
git commit -m "Add your feature"

# Push & open a Pull Request
git push origin feature/your-feature
```

---

## 📜 License

Licensed under the **MIT License** – see the `LICENSE` file for more info.

---

## 🙌 Credits

* **Created by:** Krish Yadav
* **APIs:** OpenWeatherMap
* **Libraries:** Tailwind CSS, Particles.js, Weather Icons
* **Fonts:** Google Fonts – Inter

---

> 🌦️ Happy Forecasting from **ForecastHub**
> Made with ❤️ in 2025
