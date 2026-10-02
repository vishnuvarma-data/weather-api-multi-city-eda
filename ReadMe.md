Project Overview

This project demonstrates an end-to-end data workflow using Python.
It extracts real-time weather data for multiple cities using an API, performs data cleaning and transformation, and visualizes insights using pandas and matplotlib.

Key Features
Fetches live weather data using OpenWeather API
Processes data for multiple cities from a dataset
Handles missing and inconsistent API responses
Converts temperature from Kelvin to Celsius
Identifies top 10 hottest and coldest cities
Visualizes results using bar charts

Tech Stack
Python
Pandas
Matplotlib
Requests (API calls)
tqdm (progress tracking)

Project Structure
weather-api-multi-city-eda.ipynb   # Main notebook
README.md                          # Project documentation

Workflow
Load cities dataset
Fetch weather data using API
Convert JSON to structured DataFrame
Clean and handle missing data
Perform analysis (sorting, filtering)
Visualize insights

Sample Analysis
Top 10 cities with highest temperature
Top 10 cities with lowest temperature

Notes
API key is required from OpenWeather
Some cities may not return valid data due to API limitations

Future Improvements
Use latitude & longitude for accurate API calls
Store data in SQL Server
Build Power BI dashboard
Automate data collection