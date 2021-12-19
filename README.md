# Python_APIs_Challenge
---

## Overview
This project utilizes two APIs, OpenWeatherMap and Gmaps, to compile a list of cities across the globe to analyze their weather patterns. The program focuses on four aspects of weather, maximum temperature, humidity, cloudiness and wind speed. The information gathered for the cities is then used to graph the different weather elements and then make comparisons between the northern and southern hemisphere. From the cities gathered an analysis is then done in a separate notebook to narrow down the list based on optimal temperature, humidity, and wind speed. Using the newly generated data frame, hotels near each city are located and mapped.

## WeatherPy
This script makes use of python libraries, citipy and requests, as well as the OpenWeaterMap API to generate a random list of that is then iterated over to make successive API calls of which the JSON is returned and the data list is appended. Once the list of dictionaries is compiled, the data is written to a csv file and read back in to create weather data graphs.

