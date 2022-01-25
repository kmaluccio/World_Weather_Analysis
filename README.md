# World_Weather_Analysis
Analyze the relationship between latitude and weather for cities around the world using Python in Jupyter Notebook, Pandas, and APIs. Create plots using the Matplotlib library and create heatmaps with markers using Google Maps API.

## Overview of Analysis
- In this weather analysis we:
	- 1) Retrieved desired weather data for cities around the world based on the current temperatures
	- 2) Created a personalized travel destinations map using customer preferences
	- 3) Created a travel itinerary map for a trip to four cities that appeared in the destinations based on customer preferences
- For (1) above, we used pandas, matplotlib, numpy, and citipy to write code in jupyter notebook to create a list of random cities around the world and we saved the weather data for those cities into a single DataFrame. With this DataFrame, we created a CSV file of all the city weather data which we use to create our travel map and trip map.
- For (2) above, we used pandas, google maps (gmaps) with our API key to create a list and map of the travel destinations based on the temperatures entered by the customer. This code prompts the user to enter a minimum and maximum desired temperature for vacation. Then, we get a list of cities from our weather data CSV file with the desired temperatures and with this list, we create a map with markers in each of the possible vacation cities.
- For (3) above, we use pandas, gmaps along with our API key to create one possible travel map for a vacation. We selected four cities from the previous map in step 2 which are all in the same country, so relatively close together. The maps created are maps connecting each of the desired cities to show where the customer can travel if interested in this trip. 

Note: Temperatures can be adjusted in step 2 which will change the list of cities.Then, the code in step 3 can easily be adjusted for any other cities on the list by replacing the city names in the code to the new desired cities. Lastly, each map can be recreated with the new city data to see new travel destinations and a new travel itinerary map.

![World Weather Map](https://github.com/kmaluccio/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Results
Based on the temperatures entered for this particular weather analysis, we found cities with temperatures between 70 and 90 degrees. These are the list of recommended vacation spots with the appropriate weather during this time of year. Four cities were selected in South Africa and there is a map with each of the cities and their weather data to make an itinerary to visit these four locations during one trip.

![Vacation Map](https://github.com/kmaluccio/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
