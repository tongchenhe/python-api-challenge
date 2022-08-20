# python-api-challenge
## WeatherPy:
We made api calls from OpenWeatherMap of over 500 cities randomly located around the globe. We stored the weather information in a DataFrame and made scatter plots and linear regressions on the following relationships:
* Latitude vs. Max Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed
* Linear regression models for both North and South Hemisphere of all the relationships above.  

Three observations from the data are also included as markdown text.

## VacationPy:
Using the cities' information we retrieved in WeatherPy, we created a heatmap that displays the humidity of all the cities. Then, we filtered the cities with ideal weather conditions, called the google map api to search for a hotel in each of the ideal cities, and plotted the hotel locations as pins on top of the humidity heatmap.