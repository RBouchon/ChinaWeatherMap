# ChinaWeatherMap
Generate a temperature map for each month, based on the historical average temperature in several chinese cities.

The list of cities with longitude and latitude are scrapped from https://latitude.to.

The historical weather of each city is then scrapped from Bing, as weather API such AccuWeather are not free (free version doesn't allow to get historical weather)

The data is then used to generate map with GIS softwares, such as QGIS.

Example :


Average Maximale Temperatures for each month in China

![alt text](https://github.com/Rapout/ChinaWeatherMap/blob/master/Maps/AnimatedMaps/averageMaxTemperature.gif?raw=true)


Average Minimale Temperatures for each month in China

![alt text](https://github.com/Rapout/ChinaWeatherMap/blob/master/Maps/AnimatedMaps/averageMinTemperature.gif?raw=true)


Highest Temperatures recorded for each month in China

![alt text](https://github.com/Rapout/ChinaWeatherMap/blob/master/Maps/AnimatedMaps/HighestTemperature.gif?raw=true)


Lowest Temperatures recorded for each month in China

![alt text](https://github.com/Rapout/ChinaWeatherMap/blob/master/Maps/AnimatedMaps/LowestTemperature.gif?raw=true)


