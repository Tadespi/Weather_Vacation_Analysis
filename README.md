# Weather and Vacation Analysis

Introduction:
This project aims to analyze weather data from over 500 cities at varying distances from the equator. By utilizing Python requests, APIs, and JSON traversals, the project visualizes weather patterns and explores the relationship between weather variables and latitude.

# Part 1: WeatherPy
In this section, you will create a Python script to visualize weather data using the citipy library and the OpenWeatherMap API.

Task 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude:

Retrieve weather data from the OpenWeatherMap API.
Generate scatter plots to illustrate the relationships between latitude and temperature, humidity, cloudiness, and wind speed.

Task 2: Compute Linear Regression for Each Relationship:

Calculate linear regression for each relationship and separate the plots into Northern and Southern Hemispheres.
Create scatter plots with the linear regression line, model's formula, and r values for temperature, humidity, cloudiness, and wind speed in both hemispheres.

# Part 2: VacationPy
In this section, you will utilize weather data to plan future vacations and create map visualizations.

Main Tasks:

Create a map displaying a point for every city in the DataFrame, with the size of the point representing the humidity.
Narrow down the DataFrame to find cities with ideal weather conditions based on specified criteria.
Utilize the Geoapify API to find the first hotel within 10,000 meters of each city's coordinates.
Generate a new DataFrame to store city, country, coordinates, humidity, and hotel information.
Add hotel name and country as additional information in the hover message for each city on the map.

# Conclusion:
Summarize key findings and insights from the weather analysis and vacation planning process.
