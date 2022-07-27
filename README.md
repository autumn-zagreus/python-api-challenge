# python-api-challenge
A repository to hold files for Module 6 Challenge (homework)
For some reason, the temperatures were initially in Kelvins and had to be converted to degrees Fahrenheit.
In this homework, we started in weatherpy by parsing through a list of cities to return cities with non-outlier data in humidity.
After this, we created scatter plots of latitude vs max temperature, humidity, cloudiness, and wind speed, before creating regressions for positive (northern hemisphere) and negative (southern hemisphere) latitude against max temperature, humidity, cloudiness, and wind speed.

Found positive correlation for:
Southern Hemisphere Lat vs Max Temp
Southern Hemisphere Lat vs Humidity
Northern Hemisphere Lat vs Cloudiness

Found negative correlation for:
Northern Hemisphere Lat vs Max Temp
Southern Hemisphere Lat vs Cloudiness
Southern Hemisphere Lat vs Wind Speed
Northern Hemisphere Lat vs Humidity
Northern Hemisphere Lat vs Wind Speed

Although both lines of best fit for Lat vs Cloudiness seem to correlate positively or negatively (depending on hemisphere), looking at the data alone implies that lattitude does not play a factor in cloudiness, or if it does, it is only one of more factors.

For vacationpy, we are able to create a heatmap, then a df of hotel locations nearby, and then a heatmap with markers for the hotels in the areas. Some slight modification had to be done for the marker formation code as one of the lines wasn't working.