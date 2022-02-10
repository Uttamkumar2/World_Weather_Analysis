# World_Weather_Analysis

## Project Overview

PlanmyTrip is a top travel technology company specialized in internet related serices in Hotel and Lodging  Industries. The porpose of this project UI team, collect and present data for customer via the search page which they will enter based on their prefered travel criterial in order to find their ideal hotel in the world. The will also enhance the user inteface and functionality of the PlanMyTrip App with following additional criterial.

1. Retrive weather data including the prefered min and max temprature , weather condition over 500 cities accross the world.
2. Create travel plan detination map.
3. Create travel itinerary.

## Resource 

* Data Source: 
  *   Used [NumPy](https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.uniform.html) : To generate more than 2000 random latitude and longitude.
  *   Used [citiPy](https://pypi.org/project/citipy/) : To List the nearest city to the latitude and longitudes.
  *   Used [OpenWeatherMap API](https://openweathermap.org/current): To request the current weather data from each unique city in your list. Parse the JSON data from the API request and add it to a Pandas dataframe.
  *   Used [Google Map & Direction and Palces API](https://mapsplatform.google.com/): To find a Hotel from the cities coordinates using Google Maps and Places API and Search near by.

* Software : Python 3.8.0, Anaconda Navigator, Jupyter Notebook, Microsoft Visual Code.

## Result

Using all the Visualization tool like NumPy, CitiPy and Panda's dataframe with Google Map , Place and Direction APIs, collected close to 2000 latitude and Longituded , which further filtered with valid cities accross the world that is More than 500 cities accross the world along with its latitude and longitude, we also collected Humodity , Max Temp and city current description.

![citi_data](https://user-images.githubusercontent.com/91766890/153345011-9a2dea60-aac7-4ae7-a659-ca686bbc54c2.png)

### Create a customer travel destination map
With Jupyter's ggmaps plugin and user's prefered input data and requests to the [Google Map API](https://openweathermap.org/current), that API generates customoer travel destination map.


![gmaps_locations](https://user-images.githubusercontent.com/91766890/153345255-43e9f9b8-b9b0-4d63-a4a6-1f695472be11.png)

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/91766890/153345263-82e367b4-bfeb-4d22-a05c-b28ca0039ea3.png)

### Create tavel Itinerary map

Using the [Google Maps Direction API](https://developers.google.com/maps/documentation/directions/overview) the app generates a travel route between 4 cities selected by users.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/91766890/153345319-7024143f-1137-4eb2-ba9f-8e5d7fb09dc3.png) ![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/91766890/153345339-698079d6-1208-456a-835a-34e6334e242f.png)


