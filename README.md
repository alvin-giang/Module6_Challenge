# Module6_Challenge
## Python API Challenge
### WeathePy
In this challenge, I will create a Python script to visullise the weather of over 500 cities of varying distances from the equator. I will use the citipy Python library, the OpenWeatherMap API, and my problem-solving skills to create a a representative model of weather across cities.
The code required to generate random geographic coordinmates and nearest city to each latitude and longitude combination is provided. 
I also create a series of scatter plots to showcase the following relationships:
    Latitude vs Temparature
    Latitude vs Humidity
    Latitude vs Cloudiness
    Latitude vs Wind Speed
I also compute the linear regression for each relationship, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Then, I create a series of scatter plots:
    Northern Hemisphere: Temperature (C) vs. Latitude
    Southern Hemisphere: Temperature (C) vs. Latitude
    Northern Hemisphere: Humidity (%) vs. Latitude
    Southern Hemisphere: Humidity (%) vs. Latitude
    Northern Hemisphere: Cloudiness (%) vs. Latitude
    Southern Hemisphere: Cloudiness (%) vs. Latitude
    Northern Hemisphere: Wind Speed (m/s) vs. Latitude
    Southern Hemisphere: Wind Speed (m/s) vs. Latitude
The scatter plots also include the linear regression line, the model's formula, and the rvalue, and the explaination of what the linear regression is modelling.

### VacationPy
In this challenge, I will use my weather data skills, Jupyter notebooks, the geoViews Python library, and the Geoapify API to plan future vacations.
First, I create a map that displays a point for every city in the city dataframe. The size of the point is the humidity in each city.
Second, I narrow down the city datadframe to find your ideal weather condition which is a max temperature lower than 27 degrees but higher than 21, wind speed less than 4.5m/s, and zero cloudiness.
Next, I create a new dataframe called hotel dataframe to store the city, country, coordinates, and humidity.
Fourth, for each city, use the Geoapify API to find the first hotel located within 10,000 metres of the coordinates.
Final, I add the hotel name and the country as additional information in the hover message for each city in the map.
