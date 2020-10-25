### API-Challenge
GT Data Bootcamp - Python API HW_Rios

### WeatherPy 

This analyis visualizes the weather of 500+ cities across the world of varying distance from the equator and creates a representative model of weather across world cities. This analysis utilizes a [simple Python library](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api).

### City Weather: Observable Trends
* There are strong correlations between latitude and max temperature (F) in both hemispheres.  In the Northern Hemisphere there is a strong negative correlation (r = -0.88) between latitude and max temperature (F), as a city's latitude increases the temperature decreases.  In the Southern Hemisphere there is a strong positive correlation (r = 0.70) between latitude and max tempearture (F), as a city's latitude increases the temperature also increases. 
* Cities that are closer to the equator have a visible increase in max temperture (F) while cities that are farther away have a visible decrease in max temperture (F) (see linear regression models and r values)
* There are no statistically significant differences in latitude and other weather data, such as humidity, cloudiness and wind speed for both hemispheres (see linear regression models and r values).  


### City Weather Data Scatter Plots
A series of scatter plots were created to showcase the following relationships:

* Temperature (F) vs. Latitude

![Table 1: Temperature (F) vs Latitude](weatherpy/output_weather/lat_temp_plot.png)

* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot add a sentence or too explaining what the code is and analyzing.

Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.
 
