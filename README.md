# 🌤️ Los Angeles Weather Data Visualization

This project analyzes and visualizes weather data for Los Angeles using Python. It includes scatter plots to explore variable relationships 
and circular (polar) plots to represent wind direction patterns.

## 📊 Features

- **Scatter plots** showing relationships such as:
  - Temperature vs. Feels Like
  - Humidity vs. Dew Point
  - Wind Speed vs. Wind Gust
- **Polar scatter plot** of wind direction and speed
- Clean handling of missing values and directional binning

## 🧪 Technologies Used

- Python 3
- Pandas
- Matplotlib
- NumPy
- Jupyter Notebook

## 📌 Key Insights

- Polar plots clearly show the **distribution of wind directions**, with customizable cardinal labeling.
- Scatter plots allow exploration of **correlations** between temperature, humidity, and solar metrics.

## 📂 Data Description

The CSV file contains the following weather-related columns:
- `datetime`,
- `temp`, `feels_like`, `dew`, `humidity`
- `wind_speed`, `wind_gust`, `wind_dir`
- `precip`, `precip_prob`, `precip_type`
- `solar_radiation`, `solar_energy`, `uv_index`
- `cloud_cover`, `visibility`, `conditions`, etc.

