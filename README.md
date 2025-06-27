# 🌦️ Weather Data Dashboard (Python + R)

This project pulls real-time weather data using Python and visualizes trends using R to create a simple weather analysis dashboard. It demonstrates an end-to-end pipeline from API to report.

## Tools
- Python: `requests`, `pandas`
- R: `tidyverse`, `lubridate`, `ggplot2`, `rmarkdown`, `flexdashboard`

## How It Works
1. Run `python/fetch_weather.py` to fetch weather data from OpenWeatherMap API
2. Save data as `data/weather_data.csv`
3. Load in R (`r-analysis/weather_dashboard.Rmd`) and knit to HTML
