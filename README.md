# Python_APIs_Challenge
---

## Overview
This project utilizes two APIs, OpenWeatherMap and Gmaps, to compile a list of cities across the globe to analyze their weather patterns. The program focuses on four aspects of weather, maximum temperature, humidity, cloudiness and wind speed. The information gathered for the cities is then used to graph the different weather elements and then make comparisons between the northern and southern hemisphere. From the cities gathered an analysis is then done in a separate notebook to narrow down the list based on optimal temperature, humidity, and wind speed. Using the newly generated data frame, hotels near each city are located and mapped.

## WeatherPy
This script makes use of python libraries, citipy and requests, as well as the OpenWeaterMap API to generate a random list of that is then iterated over to make successive API calls of which the JSON is returned and the data list is appended. Once the list of dictionaries is compiled, the data is written to a csv file and read back in to create weather data graphs.

 ![Max_Temp](output/Fig1.png)
 
Looking at city latitude versus max temperature, it can be seen that temperature increase as one approaches the equator or a latitude of 0. It can be inferred from this that the data gathered contains more cities in the northern hemisphere and had there been more from the southern hemisphere a stronger bell shape may have been created.

 ![Humidity](output/Fig2.png)
 
When looking at humidity versus latitude, there is no clear relationship between the two. Irregardless of latitude, cities tend to have higher percentage of humidity. A surprising amount of cities had upwards of 80% humidity when this data was collected.

 ![Cloudiness](output/Fig3.png)

Similar to humidity, there is no clear relationship between latitude and a city's level of cloudiness. The percent of cloudiness is scattered with significant gathering occuring at 0 and 100 percent.

  ![Wind_Speed](output/Fig4.png)
 
Wind speed and latitude did not display a strong relationship but a very weak one can be teased from the graph. Wind speeds seem to very slightly increase as the latitude increases. Again this relationship is very weak but is something of interest here.


