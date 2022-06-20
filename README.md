# World_Weather_Analysis

### Project Overview
Analysis of weather data for a vacation recommendation service. Weather and geolocation APIs were utilized to create a "Vacation Itenerary" based on locations chosen from a heatmap that showed locales within a certain temperature range. The stops for the itenerary were plotted on the map with travel path and info markers. Random latitude/longitude pairs were generated and citipy was used to find nearest city. Open weather was then used to get local weather conditions. Dataframe with city, country, lat/long, and weather conditions was exported as a CSV for later use in Vacation search, which filtered data based on user input. These filtered locations were then used to find lodging for display on the map info box.

### Technologies/Resources
* Python (pandas, numpy, citipy)
* Open weather API
* gmaps API

### Example Results
![World search based on temp ranges](https://github.com/manBow1119/World_Weather_Analysis/blob/main/Weather_Database/Vacation_Search/WeatherPy_vacation_map.png)

![Australia with map markers](https://github.com/manBow1119/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_travel_map_markers.png)

![Australia travel map](https://github.com/manBow1119/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_travel_map.png)

### Summary
This script can be reused to focus on different filtering paramters depending on user preferences. It can be augmented to generate more lat-long pairs for even more destinations and describe with other gmaps information.



