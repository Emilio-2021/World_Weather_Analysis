# World_Weather_Analysis  

On this project we use the Weather API and Google API to find the best cities for vacation.

## Overview

We create a system to look at different weather patterns around the world and offers insights to travelers who want to book a trip, we create three folders with different levels of analysis: weather database, vacation search, and vacation itinerary.

### 1.Weather Database

This folder uses Open Weather Map API to pull weather information on different cities around the world. That information consists of:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)

These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

### 2.Vacation Search

This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location, we select a temperature range between 75 and 88 degrees fahrenheit.

### 3.Vacation Itinerary

This analysis takes the search information from the vacation search and uses Google Maps directions API to create a vacation itinerary.
