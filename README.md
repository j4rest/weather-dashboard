# 🌤️ MeteoCompare

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://j4rest.github.io/weather-dashboard/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Languages](https://img.shields.io/badge/languages-EN%20%7C%20RU-blue)](#)

> **A free tool for analyzing weather forecast model accuracy**  
> Compare predictions from ECMWF, GFS, ICON and other models against real observations

🔗 **[Open the dashboard →](https://j4rest.github.io/weather-dashboard/)**

---

## 📖 About the Project

**MeteoCompare** is a web application that overlays weather model forecasts made N days ago onto actual observation data. You literally see each model's accuracy on a timeline!

The app uses the free [Open-Meteo](https://open-meteo.com/) API and runs entirely in the browser — no servers or registration required.

---

## 📸 Screenshots

### 🌡️ Temperature and Wind Analysis
![Main screen with charts](images/screenshot-main.png)

*Comparing ECMWF IFS forecast with actual temperature in Moscow*

### 🏆 Model Ranking
![Model ranking](images/screenshot-ranking.png)

*Automatic accuracy calculation across 4 metrics: temperature, wind, precipitation, sunshine*

### 🗺️ Accuracy Map
![Accuracy map](images/screenshot-map.png)

*The best model for every city in the world — visualized on an interactive map*

### 📅 Period Comparison
![Period comparison](images/screenshot-periods.png)

*Discover how model accuracy changes across different time periods*

### 🌙 Dark Theme
![Dark theme](images/screenshot-dark.png)

*Comfortable work at any time of day*

### 🌐 Multilingual Support
![English version](images/screenshot-english.png)

*Full support for Russian and English languages*

---

## ✨ Features

### 📊 Accuracy Analysis
- Compare forecasts from **7 models** (ECMWF IFS, AIFS, AIGFS, GFS, ICON, UKMO, GEM, MétéoFrance)
- **4 accuracy metrics**: temperature, wind, precipitation, sunshine hours
- Visualization on charts with colored lines for each model
- Automatic **model ranking** with medals 🥇🥈🥉

### 🗺️ Accuracy Map
- Interactive world map (Leaflet + OpenStreetMap)
- Analyze multiple cities simultaneously
- Colored markers show the best model for each region
- 4 map styles to choose from (light, dark, Voyager, OSM)

### 📅 Period Comparison
- Compare model accuracy across different time periods
- Find out which model performs better in winter vs summer
- Table with color-coded improvements/declines

### 🔔 Notifications
- Configurable accuracy thresholds
- Alerts for large temperature errors
- Log of all notifications

### 📱 PWA and Offline Mode
- Install as an app on your phone or computer
- Works offline (Service Worker)
- Responsive design for mobile devices

### 🌐 Multilingual Support
- Full support for **English** and **Russian**
- One-click language switching
- Dynamic update of all texts and charts

### 💾 Data Export
- Export to **CSV** (for Excel/Google Sheets)
- Export to **JSON** (for programmatic processing)

### 🎨 Settings
- Dark/light theme
- Daily/hourly resolution
- Time format 24h / 12h (AM/PM)
- Auto-save all settings in the browser

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5 / CSS3** | Structure and styles |
| **Vanilla JavaScript** | Application logic |
| [Chart.js](https://www.chartjs.org/) | Interactive charts |
| [Leaflet](https://leafletjs.com/) | Interactive map |
| [Open-Meteo API](https://open-meteo.com/) | Weather data (free) |
| [CartoDB](https://carto.com/) | Map tiles |
| **GitHub Pages** | Hosting |

---

## 🚀 Quick Start

### Online (no installation required)
Just open: **[https://j4rest.github.io/weather-dashboard/](https://j4rest.github.io/weather-dashboard/)**

### Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/j4rest/weather-dashboard.git
   cd weather-dashboard
