# World_Weather_Analysis

## Overview
Cities for 2000 randomly generated set coordinates was retrieved using the CitiPy module. OpenWeather API requests were made for each successfully identified city and the resulting JSON was parsed for various weather data and stored in [WeatherPy_Database.csv](weather_database/WeatherPy_Database.csv). Then, user input statements for minimum and maximum temperatures identified destinations within customer preferences with nearby hotels and current weather descriptions. These destinations, and their corresponding information, are then displayed as pop up markers on a map. Finally, a travel itinerary was generated from this filtered list of destinations and a travel route between four cities was displayed with popup markers for each city on the itinerary.

## Resources

Software:
* Python 3.7.10
* [citipy](https://github.com/wingchen/citipy) 
* OpenWeather API
* Google Maps Platform API (Places, Maps Javascript, Directions)
* Jupyter Notebook
* Anaconda

# Results
![weather_database_df](https://user-images.githubusercontent.com/90335218/145691491-422a1e97-613d-4262-92a1-1a68597d892b.png)
![WeatherPy_vacation_df](https://user-images.githubusercontent.com/90335218/145691399-0ac33e84-54e6-4d55-a790-d2085d7d6dad.png)
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/90335218/145691400-4314ac9a-fa30-43b6-a567-3ff69d67206d.png)
![WeatherPy_travel_df](https://user-images.githubusercontent.com/90335218/145691471-b79d3287-fb32-47a4-9d61-589abac1c660.png)
![WeatherPy_travel_map](https://user-images.githubusercontent.com/90335218/145691482-6acad631-46ab-42bd-bcb6-b36b71080743.png)
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90335218/145691486-a73bf445-62b8-4f74-b467-464d5effc107.png)
