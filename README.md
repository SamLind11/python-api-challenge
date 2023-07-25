# Python API Challenge

## Description

For this challenge, I created two Jupyter Notebook files, WeatherPy and VactionPy.  

### WeatherPy

Using the CitiPy library, 500 city names were generated using randomly chosen latitude and longitude coordinates.  Next, these city names were used to call the OpenWeatherMap API to look up the temperature, humidity, cloudiness, and wind speed for each location.  These data were then assembled into a DataFrame, and were used to create several scatterplots exploring the relationship between latitude and various weather metrics.

### VacationPy

Using the data set created in the WeatherPy file, along with the Geoapify API, I searched for hotels that were near cities that I might want to vacation in.  The original data set was narrowed down based on weather preferences (between 21 and 35 degrees celsius, and less than 50% cloudy), and then a for loop searched for hotels within a 10 km radius around the coordinates of each city.  The results were displayed on a map using the geoViews Python library, with the name of the hotel listed by each point.

## Contributors

The outline for each of the two Jupyter Notebook files was provided by the UNC Data Analytics Bootcamp.  All other code was written by Sam Lind.
