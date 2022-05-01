# World Weather Analysis

## Overview 

In this project I generate a random set of 2000 latitudes and longitudes to then perform an API call on OpenWeatherApp to retrieve the weather information for the nearest city for each point in the dataset. Then, using input statements from customers, I can retrieve their weather prefereces and identify possible travel destinations and nearby hotels. The travel destinations, along with their nearby hotels, are mapped with a marker layer map using Google Cloud Platform's Places API, pop up markers are visible for each city. Once the customer has chosen a travel destination, another marker layer map is genereated using Google Cloud Platform's Directions API that displays a travel itinerary that shows the route between four cities chosen from the customer's possible travel destination. 

## Results 

Marker layer map with travel destinations and nearest hotel. 

![hotel_map](https://github.com/AmairaniR/world-weather-analysis/blob/main/vacation_search/WeatherPy_vacation_map.png)

Marker layer map with directions travel itinerary. 

![travel_map](https://github.com/AmairaniR/world-weather-analysis/blob/main/vacation_itinerary/WeatherPy_travel_map.png)
