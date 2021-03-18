# weather-dashboard

## Acceptance Criteria

GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city

### TODOs

- Convert icon IDs to img src
- Convert Unix dates
- Conditional styling on UV Index
- Put past searches in DOM as buttons
- Past searches array needs to load to / from Local Storage
- Event listeners on all past searches - click calls the getWeather function
- Add media query for aside width and top / bottom margins on 5-day blocks
- Error handling - if user enters a nonsense city display an error

### Resources

https://openweathermap.org/current
https://openweathermap.org/api/one-call-api

Icons:
http://openweathermap.org/img/wn/10d@2x.png
Put 3 digit icon id after wn/ and before @