# WeatherPy
## Overview
In this project we created a Vacation Itinerary based on weather preferences. We will use OpenWeather and Google API's to retrieve information about weather conditons and geolocations. 

## Results
* Randomly select 2000 latitudes and longitudes in order to search for over 500 cities around the world. [code](API/cities_api.ipynb)
  
* Get the Weather coditions for those cities using API's and then filter the cities by weather preferences.
* Search for hotels in each one of the cities.
* Create a map with markers that contain basic information about that city. 
* Create a driving itinerary between our chosen cities.

## Summary
After retrieving the API's information we got a DataFrame with the weather conditions and hotels for each city.
![Summary_df](https://user-images.githubusercontent.com/43548929/161438303-773de86f-839a-4ac8-ac43-bba9e9b1b324.png)

We can visualize the previous DF in the following map, we have each of those cities with a marker and information about hotels and weather.
![Screen Shot 2022-04-03 at 9 42 34 AM](https://user-images.githubusercontent.com/43548929/161438524-512d463e-37d5-4ca7-a955-90b9c913c4f2.png)

Finally to get the Vacation Itinerary we select only 4 of those cities and get the route we need to follow.
![Screen Shot 2022-04-03 at 9 47 26 AM](https://user-images.githubusercontent.com/43548929/161438722-36b48f76-41c4-4454-ae26-bba51f84286c.png)

