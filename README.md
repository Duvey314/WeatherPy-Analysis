# WeatherPy-Analysis
---
This projects is an example of API interfacing in python. The code randomly generates a set of 500+ latitude and longitude pairs and then uses the CityPy module to get alist of cities. Then we used the [OpenWeatherAPI](https://openweathermap.org/api) to get the weather data at each of those locations. This data is then used to graph: Temperature vs. Latitude, Humidity vs. Latitude, Cloudiness vs. Latitude, and Wind Speed vs. Latitude.

The VacationPy notebook first reads the cities and weather csv generated from the Weather_Database notebook. The user is then prompted for the temperature range they are looking for in a vacation and if they want snow or rain. The code then sorts the dataframe for cities matching the user inputs and finds hotels near those cities before plotting them on a map using [gmaps places api](https://developers.google.com/places/web-service/search).

As an example, four cities in Canada are selected for a trip (Tsihombe, Matagami, Chapais, La Tuque) in the Vacation_Itinerary notebook. Directions between these cities are then mapped using the [gmaps directions api](https://developers.google.com/maps/documentation/directions/start).

The dataframes containing the location and hotel data can be found in the data folder. Images of the maps can be found in the images folder.

