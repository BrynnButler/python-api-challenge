# python-api-challenge
module 6 challenge

## Overview
This challenge explores the relationship between weather and location. Using Python, OpenWeatherMap and Geoapify APIs, we gathered and visualized weather data for hundreds of cities worldwide, and created a heat map and hotel locator based on weather conditions.

## Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question:  
**"What is the weather like as we approach the equator?"**

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But if pressed for more information, how would you prove that?

## WeatherPy Summary
- Generated random cities using the `citipy` module.
- Retrieved current weather data (temperature, humidity, cloudiness, wind speed) using the OpenWeatherMap API.
- Created scatter plots to visualize weather patterns based on latitude.
- Performed linear regression to explore trends in Northern vs. Southern hemispheres.

## VacationPy Summary
- Used Geoapify API to locate hotels near ideal vacation locations.
- Created an interactive map to visualize cities that meet certain weather conditions (e.g., warm, humid, low wind).
- Displayed hover text with hotel and city details.

## Tools & Libraries Used
- Python (Pandas, Matplotlib, NumPy, Requests)
- Jupyter Notebook
- hvPlot / HoloViews
- OpenWeatherMap API
- Geoapify API
- Git & GitHub

## Results
The WeatherPy analysis confirmed a clear relationship between latitude and temperature, and weaker or no clear correlation for other weather variables. VacationPy allowed us to find ideal travel destinations and nearby hotels based on chosen weather parameters.
