# weather-data-collector
**Application 2 :**
Real-Time Data Processing System for Weather Monitoring with Rollups and Aggregates.
**1. Weather Data Collector**
This project collects weather data for multiple cities in India using the OpenWeatherMap API. It tracks temperature, humidity, and wind speed, calculates daily summaries, and provides alerts if temperatures exceed a specified threshold.

**2. Features**
- Collects weather data for cities: Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad.
- Computes daily summaries including average temperature, humidity, and wind speed.
- Sends alerts if the temperature exceeds a predefined threshold for two consecutive updates.
- Visualizes daily weather trends using Matplotlib.
- 
# Build Instructions

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.x
- Docker (optional, for containerization)
- A database of your choice (e.g., SQLite, PostgreSQL) for persistent storage.

### Dependencies

The following Python packages are required:

- `requests`: For making API calls to the OpenWeatherMap service.
- `matplotlib`: For visualizing weather data trends.

To install these dependencies, run:
```bash
pip install requests matplotlib

 
