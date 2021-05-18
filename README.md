# World_Weather_Analysis
## Overview

This project is an exercise in analysis, visualization, and statistical skills by retrieving and analyzing weather data for PlanMyTrip. The goal is to parse through a series of random latitudes and longitudes and retrieve city names and countries from these coordinates using citypy. Next, we allow the user to input a min and max temperature of their choosing and further parse through our previous list of cities to find cities with temperatures that match our input.  We want to retrieve the weather data for cities that match the criteria that the customer was searching, specifically returning the max temperature and the current conditions. After this, we use the Google Maps API to find an option for a hotel in the city we are looking at. The next step is to create a map, also using the Google Maps API, with markers of each of these cities telling us the city, country, weather temperature/conditions, and the name of the hotel we found. Finally, we want to create a multi-city itinerary complete with all the previous information and the best driving route to get to each city, once again, using the Google Maps API.

Ultimately the goal is to provide our customers with easy-to-read data and visuals to assist in trip planning.

## Resources

### Files
- WeatherPy_Database.csv in Weather_Database folder
- WeatherPy_vacation.csv in Vacation_Search folder

### Images
- WeatherPy_vacation_map.png in Vacation_Search folder
- WeatherPy_travel_map.png in Vacation_Itinerary folder
- WeatherPy_travel_map_markers.png Vacation_Itinerary folder

### Software/Programs
- APIs:
    - openweathermap.org API
    - Google Maps API

- Software:
    - Python 3.7.6, Jupyter Notebook, Pandas, citypy