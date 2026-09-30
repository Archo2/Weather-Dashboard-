# Weather Dashboard

A weather app that shows current conditions and a 5-day forecast for any city, using the OpenWeather API.

**Live demo:** https://archils.github.io/Weather-Dashboard-/

> **Note:** This app uses OpenWeather's One Call API 2.5, which OpenWeather has since retired. Searches may no longer return data until the app is updated to the newer One Call 3.0 or the free 5-day forecast endpoint.

## Features

- Search weather by city name
- Current weather: city, date, weather icon, temperature, humidity, wind speed and UV index
- 5-day forecast cards with date, icon, temperature and humidity
- Search history saved in `localStorage`; click a past city to search it again
- **Clear History** button

## Built With

HTML · CSS · JavaScript · [OpenWeather API](https://openweathermap.org/api)

## How to Use

1. Open the [live demo](https://archils.github.io/Weather-Dashboard-/) or open `index.html` in your browser.
2. Type a city name and click **Search**.
3. Click any city in your search history to see its weather again.

To run it with your own key, create a free account at [openweathermap.org](https://openweathermap.org/), then replace the API key at the top of `js/script.js`.

## Screenshots

![Screenshot](06-server-side-apis-homework-demo.png)

## Author

**Archils Oburu**
- GitHub: [@Archils](https://github.com/Archils)
- Email: oburuarchils@gmail.com
 Weather-Dashboard is an application to find a weather condition of a given city both the current and 5-Days forecast at the same time. The server-side API used to get response data object is retrieved from the Open Weather APi. The current weather section is including the following weather characters and date.
City, Date, Icon-image,Temperature, Humidity,Wind Speed and UV index
The 5-days weather forecast also displays below the current weather conditions section and it includes the following information for each day
The local storage is used here to store the previous search city and display them to the user in the left side of the page under the list group. The user can also clear the search history by clicking the clear history button. If the user wants to see the past search city weather condition again, just click the list group item cities under the clear history button.


![](06-server-side-apis-homework-demo.png)
