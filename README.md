# What's the Weather Like?
## WeatherPy
### Objectives:
1. Generate 500+ random coordinates and locate the nearest cities.
2. Use the [Open Weather API](https://openweathermap.org/api) to find weather data on each city.
3. Save the weather to a CSV file.
4. Create a series of scatter plots to showcase relationships between the weather and the cities' latitudes.
5. Run linear regression on each relationship.
## VacationPy

### Objectives:
1. Using the CSV file generated in WeatherPy, create a humidity heatmap.
2. Narrow down the data to find cities with ideal weather conditions.
    * Max temperature between 70 and 75 degreees fahrenheit. 
    * Wind speed less than 5 mph
    * Humidity less than 80% but higher than 40%
    * Cloudiness less than 5%
3. For each city, use the [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview) to find the first hotel located within 5,000 meters and plot the hotels on top of the heatmap. 
![Vacation Heatmap](/output_data/Screenshot_HeatMap.png)