# World_Weather_Analysis

Analyzing world wide weather  

### Overview of the analysis

we have WeatherPy and VacationPy which gives us some information about weather and traveling data which we try to complete it by adding some more information to our data. we are adding the weather description to the weather data we’ve already retrieved in WeatherPy. Then, we use input statements to filter the data for weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, we will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, we will create a travel route between the four cities as well as a marker layer map.

### Results

To Retrieve Weather Data, we Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data in WeatherPy, we retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

in this picture we can see weather description's been added to dataframe.

![This is an image](dataframe.png)

Then we use input statements to retrieve customer weather preferences in WeatherPy_Vacation to use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
which we can see in this picture added hotels to our dataframe.


![This is an image](hotels.png)

and the marker layer map with pop-up markers.

![This is an image](WeatherPy_Vacation_map.png)

now we use the Google Directions API in Vacation_Itinerary to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations which we can see the results in this picture.

![This is an image](WeatherPy_travel_map.png)


Then, we create a marker layer map with a pop-up marker for each city on the itinerary.

![This is an image](WeatherPy_travel_map_markers1.png)


![This is an image](WeatherPy_travel_map_markers2.png)



### Summary Based on the results

After reviewing and upgrading our code we decided to add weather description to make it easier to decide where to travel and by showing a route map we showed the route between four possible cities which could be proper to choose based on the chosen weather. I think next upgrade could be client choosing four city and our app give them the proper route based on their chosen weather.   