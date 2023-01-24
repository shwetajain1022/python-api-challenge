# python-api-challenge

#Part 1: WeatherPy

##Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Create a series of scatter plots to showcase the following relationships:

*Latitude vs. Temperature
*Latitude vs. Humidity
*Latitude vs. Cloudiness
*Latitude vs. Wind Speed

##Requirement 2: Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship for Northern Hemisphere and Southern Hemisphere.
Created separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
*Northern Hemisphere: Temperature (C) vs. Latitude
*Southern Hemisphere: Temperature (C) vs. Latitude
*Northern Hemisphere: Humidity (%) vs. Latitude
*Southern Hemisphere: Humidity (%) vs. Latitude
*Northern Hemisphere: Cloudiness (%) vs. Latitude
*Southern Hemisphere: Cloudiness (%) vs. Latitude
*Northern Hemisphere: Wind Speed (m/s) vs. Latitude
*Southern Hemisphere: Wind Speed (m/s) vs. Latitude

Discussed the difference between the Northern Hemisphere and Southern Hemisphere plots

#Part 2: VacationPy

*Main tasks was be to use the Geoapify API and the geoViews Python library and employ Python skills to create map visualisations.
*Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
*Narrowed down the city_data_df DataFrame to find ideal weather condition. For example:
 -A max temperature lower than 27 degrees but higher than 21
 -Wind speed less than 4.5 m/s
 -Zero cloudiness
*Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
*For each city, used the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
*Add the hotel name and the country as additional information in the hover message for each city in the map



