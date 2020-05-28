# Sample-Weather-App

This project is on Creating an Android Weather App using Kotlin. To get the weather information I used OpenWeatherMap API. Informations like Temperature, Pressure, Humidity, Weather status, Time of Sunrise and Sunset etc. are passed from the API.

Suppose you want to request weather information using a Latitude & Longitude of a place, then you should use:

response = URL("https://api.openweathermap.org/data/2.5/weather?lat=$LAT&lon=$LON&units=metric&appid=$API").readText(
                    Charsets.UTF_8
                )
where LAT and LON will be the Latitude & Longitude respectively. If you want to implement this project to display weather information of user's current location you'll just need detect the current latitude & longitude.
