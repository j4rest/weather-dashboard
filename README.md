`index.html` is a complete single-page weather forecast comparison dashboard named **«МетеоСравнение» / MeteoCompare**.

### Main functionality

- Lets users select:
  - A city
  - Number of days in the past to examine
  - Forecast period length
  - Daily or hourly resolution
  - 12-hour or 24-hour time format
  - Weather forecast models such as ECMWF, GFS, ICON, UKMO, GEM, and Météo-France
- Fetches location, historical weather, and model forecast data from the **Open-Meteo APIs**.
- Compares forecasts against observed weather data for:
  - Temperature
  - Wind speed
  - Precipitation
  - Sunshine duration
- Displays results using **Chart.js** line and bar charts.
- Calculates accuracy scores for each model and presents:
  - Overall rankings
  - Per-metric scores
  - A highlighted best-performing model

### Additional tabs

1. **Analysis**
   - Charts, rankings, model scores, and export buttons.
   - Supports CSV and JSON export.

2. **Compare periods**
   - Compares model accuracy across two user-defined historical periods.

3. **Accuracy map**
   - Allows multiple cities to be added.
   - Uses **Leaflet** to display each city and its best-performing model.
   - Supports several map tile providers:
     - Carto light
     - Carto dark
     - Carto Voyager
     - OpenStreetMap
   - Includes fallback handling if map tiles fail to load.

4. **Notifications**
   - Configurable accuracy and temperature-error thresholds.
   - Supports browser notifications.
   - Maintains a local notification log.

### UI and persistence

- Russian and English localization.
- Light and dark themes.
- Responsive layout for mobile screens.
- Stores user settings, selected cities, map style, notification preferences, and alert history in `localStorage`.
- Includes a basic dynamically generated PWA manifest and service worker.

### External dependencies

- Chart.js
- Chart.js date-fns adapter
- Leaflet
- Open-Meteo geocoding, archive, and forecast APIs
- Carto and OpenStreetMap map tiles

Overall, the file is both the application’s HTML structure and its entire frontend implementation: styling, interface markup, API calls, data processing, charts, map behavior, notifications, localization, persistence, and exports are all contained in one file.
