# WeatherPy with Python APIs
## Purpose
In this module I learned about APIs and how to use them to request data from different sources and use that data for my application. For the challenge, I was tasked with retrieving weather data and using it to create a list of desirable cities to travel to and display an itinerary using Google APIs. The itinerary included the hotels to stay in, the city names, countries, along with the weather details for each city.

## Results
For the first part of the challenge I created a list of 2,000 latitudes and longitudes and then found the nearest cities to these coordinates using Pandas. With the city list created I used an OpenWeatherMap API to pull weather data such as temperature, humidity, and cloudiness and create a dataframe that displayed all this information. The second part of the challenge consisted of filtering the original dataframe using the "client's" preferred weather conditions to generate a new dataframe that met these preferences. With the filtered dataframe I then used the Google Places API to pull the hotels that are in each city and add markers showing the locations in a map.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/88118759/136708087-89e93527-883b-415c-af76-d22a8ebd1226.PNG)

Lastly, I used the Google Directions API to generate a travel itinerary of 4 cities, containing the directions to each city, the hotel, and the weather details.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/88118759/136708213-f378c7ec-b3c7-48b7-b69e-805fc8f3e8db.PNG)
