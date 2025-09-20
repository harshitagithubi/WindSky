# WindSky Weather Dashboard

A comprehensive weather application demonstrating advanced front-end development and API integration capabilities.

**Live Demo:** https://harshitagithubi.github.io/WindSky/

## Technical Skills

### Frontend Development
- **HTML5:** Semantic markup with modern accessibility standards
- **CSS3:** Advanced styling with glassmorphism effects, CSS Grid, Flexbox, and responsive design
- **JavaScript:** Vanilla ES6+ with async/await, DOM manipulation, and real-time data processing

### API Integration & Data Processing
- **Weather Data API:** Open-Meteo forecast and current weather integration
- **Air Quality API:** Open-Meteo air quality with PM2.5 to AQI conversion algorithms
- **Geocoding API:** Nominatim reverse geocoding for location resolution
- **Mapping API:** OpenStreetMap embedding for interactive location visualization

### Data Visualization
- **Chart.js Integration:** Dynamic weather charts (temperature, precipitation, wind speed)
- **Real-time Updates:** Live data rendering with responsive chart animations
- **Custom Data Processing:** Multi-source data aggregation and formatting

## Core Features

**Weather Analytics**
- 10-day forecast with hourly breakdowns
- Real-time weather conditions with comprehensive metrics
- Interactive temperature, precipitation, and wind speed visualizations
- Sun/moon tracking with astronomical calculations

**Air Quality Monitoring**
- PM2.5 measurement with EPA AQI conversion
- Visual health category indicators

**Intelligent Health Recommendations**
- Dynamic suggestion engine based on environmental factors

**Interactive Mapping**
- Embedded OpenStreetMap integration

## Technical Architecture

**Frontend Stack:**
- Pure HTML5, CSS3, Vanilla JavaScript
- Chart.js for data visualization
- Responsive design with mobile-first approach

**API Integrations:**
- Open-Meteo Weather API (forecast and current conditions)
- Open-Meteo Air Quality API (PM2.5, pollutant data)
- Nominatim Geocoding API (location services)
- OpenStreetMap Embed API (mapping)

## Current Implementation Notes

**Input Method:** Currently requires latitude/longitude coordinates due to API design constraints. This provides precise global location accuracy and eliminates dependency on paid location search APIs.

**Browser Geolocation:** Integrated for automatic coordinate detection when user permissions are granted.
