# Python API 

## Part I - WeatherPy: What's the Weather Like?

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we be utilizing citipy Python library, the OpenWeatherMap API to create a representative model of weather across world cities.

Step 1: Create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Note: Analyze and explain relationships in each scatter plot.

Step 2: Run linear regression on each relationship for Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Note: Analyze and explain relationships in each scatter plot.


Suggestion: There are multiple linear regression plots. To optimize the code, write a function that creates the linear regression plots.

Final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### Part II - VacationPy - Let's check vacation places using Google Places API

* Create a heat map that displays the humidity for every city from the part I.
* Narrow down the DataFrame to find your ideal weather condition. 
* Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
* Using Google Places API to find the first hotel for each city located within 5000 meters of the city coordinates.
* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

#### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
