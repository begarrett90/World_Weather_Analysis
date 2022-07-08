# World_Weather_Analysis

Weather analysis, vacation city search based on Open Weather and Google APIs

## Overview of Project

The purpose of this project were to retrieve weather data using a set of 2000 random latitudes and longitudes, retreive the nearest city and perform an API call with OpenWeatherMap. A DataFrame was then created using the weather data. Input statements were used to identify weather preferences and using those preferences potential travel destinations and nearby hotels were identified. Lastly a travel itineary map was created between 4 cities in Brazil. 

## Resources
- Data Source: WeatherPy_Database.csv; WeatherPy_vacation.csv
- Python Code: Weather_Database; Vacation_Search; Vacation_Itinerary
- Software: Python 3.7.11; jupyter notebook
- API's" OpenWeatherMap; Google Maps

## Results
### Weather Database
2000 random latitudes and longitudes were created and the nearest city to them were retrieved. An API call was executed using the OpenWeatherMap API to retrieve current weather information. A DataFrame was create with the updated weather and printed to a csv file. 

[WeatherPy_Database.csv](https://github.com/begarrett90/World_Weather_Analysis/files/9075108/WeatherPy_Database.csv)

### Vacation Search
An input statement was used with minimum temperature of 75 degrees and maximum temperature of 90 degrees to identify travel destinations and nearby hotels matching these preferences. A CSV was created of these possible weather locations as well as a display using Google map with a marker layer showing pop up markers. 

[WeatherPy_vacation.csv](https://github.com/begarrett90/World_Weather_Analysis/files/9075115/WeatherPy_vacation.csv)


<img width="544" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/105942622/178072386-c501d6bd-9f7e-4d29-a4b7-31655970f616.png">

### Vacation Itinerary
Four cities from the list and map created using the weather preferences a travel itinerary was created. 

<img width="543" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/105942622/178072662-75b1e95c-0723-470d-aa7c-65d88f10d733.png">

<img width="823" alt="WeatherPy_tarvel_map_markers" src="https://user-images.githubusercontent.com/105942622/178072707-b75732b0-200e-4e1d-a297-a50e925ae6a9.png">

