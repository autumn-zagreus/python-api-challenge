# python-api-challenge
A repository to hold files for Module 6 Challenge (homework)

In this homework, we started in weatherpy by parsing through a list of cities to return cities with non-outlier data in humidity.
After this, we created scatter plots of latitude vs max temperature, humidity, cloudiness, and wind speed, before creating regressions for positive (northern hemisphere) and negative (southern hemisphere) latitude against max temperature, humidity, cloudiness, and wind speed.

Found positive correlation for:
Southern Hemisphere Lat vs Max Temp
Southern Hemisphere Lat vs Cloudiness
Norther Hemisphere Lat vs Wind Speed

Found negative correlation for:
Northern Hemisphere Lat vs Max Temp
Southern Hemisphere Lat vs Humidity
Northern Hemisphere Lat vs Cloudiness
Southern Hemisphere Lat vs Wind Speed
Northern Hemisphere Lat vs Humidity

For vacationpy, I was able to create a heatmap, but the dataframe of ideal weather conditions came back empty. I suppose this means that there aren't any cities in my set of data which have a maximum temperature of between 70 degF and 80 degF,  wind speed of less than 10 mph, AND a cloudiness of 0%. There are, however, cities that meet just 1 or 2 of these conditions, but not all 3, in my dataset.