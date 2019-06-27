# ChinaWeatherMap
Generate a temperature map for each month, based on the historical average temperature in several chinese cities.

The list of cities with longitude and latitude are scrapped from https://latitude.to.

The historical weather of each city is then scrapped from Bing, as weather API such AccuWeather are not free (free version doesn't allow to get historical weather)

The data is then used to generate map with GIS softwares, such as QGIS.

Example :

![alt text](https://raw.githubusercontent.com/Rapout/ChinaWeatherMap/master/Maps/aMax/9-Sep.png)

Average Maximale Temperatures for each month in China
