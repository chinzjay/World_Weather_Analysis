# World_Weather_Analysis

## Overview
The purpose of this project is to identify potential travel destinations and nearby hotels and to create a travel itinerary based on traveller weather preference. A travel route is created between four cities of choice using Google Maps Directions API and marker layer maps.

## Results
A set of 2,000 random latitudes and longitudes were generated and their nearest city was retrieved. In addition to the city weather data, the current weather description was retrieved for each city from OpenWeatherMap wih API calls. The data was added to a DataFrame and exported as a CSV file (https://github.com/chinzjay/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv).

A customer travel destination map was created based on user input for weather preference and potential travel destinations and nearby hotels were identified. The hotel data was loaded to a new DataFrame and exported as a CSV file (https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv).
![WeatherPy_vacation_map](https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)
|:--:|
|Fig 1. Marker layer map with pop-up markers for possible destinations.|

A marker layer map with pop-up markers for the cities in the vacation DataFrame was created *(Fig 1)* (https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG). 

The Google Directions API was used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. A directions layer map between the cities and the travel map was created (https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG). 
![WeatherPy_travel_map_markers](https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
|:--:|
|Fig 2. Marker layer map with pop-up markers for cities in the itinerary.|

A marker layer map *(Fig 2)* (https://github.com/chinzjay/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG) was created with a pop-up marker for each city on the itinerary.

## Summary
The following are the major features of PlanMyTrip app.
 -  Based on latitudes and longitudes, current weather description of the random cities are retrieved.
 -  Based on customer weather preference, a travel destination map is created with potential destinations and nearby hotels.
 -  Based on traveler choice of cities, a route map is created with pop-up markers for each city in the itinerary.
