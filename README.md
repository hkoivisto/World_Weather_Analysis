# World_Weather_Analysis

## Overview
This tools allows users to view a map of potential vacation destinations and nearby hotels by filtering for weather preference.

## Method
Randomly generated latitudes and longitudes are used to create a selection of potential vacation locations. Weather data is collected from these locations using OpenWeatherMap API, and nearby hotel information is collected from these locations using Google Maps API. User input of a desired temperature range narrows down the potential vacation destinations, and the cities are displayed on a Google map.

If specific cities are selected, a travel itenerary map is also displayed with directions between each location to be visited.


## Results

Potential Vacation Destinations with preferred max temperature between 70&deg;F and 90&deg;F.

![Weatherpy_vacation_map](https://github.com/hkoivisto/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

Directions Map for Four Destinations in Peru

![WeatherPy_travel_map](https://github.com/hkoivisto/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
