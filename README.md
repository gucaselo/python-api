# Python API

### Using two API, analyzed Weather data and based on that one generated Vacation destinations.

## WeatherPy
### Created a `Python` script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this we used the [citypy library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api). Generated a csv file with the data obtained.

***Please add your API if you intend to use this script.***

The following scatter plots were generated with the data obtained:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


After separating the plots into Northern Hemisphere and Southern Hemisphere, I ran linear regression on the following relationships:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

