# Weather and Vacation Analysis

## Background

I embarked on a project to harness the power of data to answer a fundamental question: "What is the weather like as we approach the equator?" While the concept seemed obvious, my goal was to provide concrete evidence to support our understanding of how weather variables change as we move closer to the equator.

## Part 1: WeatherPy

In WeatherPy, I visualized the weather of over 500 cities of varying distances from the equator. Leveraging the citipy Python library and the OpenWeatherMap API, I created a representative model of weather across cities.

### Requirements:

1. **Create Plots to Showcase the Relationship Between Weather Variables and Latitude**: I generated scatter plots for latitude vs. temperature, humidity, cloudiness, and wind speed.
   
2. **Compute Linear Regression for Each Relationship**: I computed linear regression for each relationship and created scatter plots with linear regression lines for Northern and Southern Hemispheres.

### Findings:

After analyzing the plots and regression lines, I observed trends in how weather variables change with latitude. I provided insights into the relationships and highlighted any noteworthy findings.

## Part 2: VacationPy

In VacationPy, I utilized my weather data skills to plan future vacations. Using Jupyter notebooks, the geoViews Python library, and the Geoapify API, I created map visualizations.

### Tasks:

1. **Create a Map Displaying Cities and Humidity**: I created a map with points representing cities, where the size of the point corresponds to the humidity in each city.

2. **Find Ideal Weather Conditions for Vacation Planning**: I narrowed down cities based on specified weather conditions, such as temperature, wind speed, and cloudiness.

3. **Find Nearest Hotels**: I used the Geoapify API to find the nearest hotel to each city within a certain radius.

### Results:

I generated a map displaying cities meeting my ideal weather conditions along with nearby hotels. Each city's hover message included information about the hotel and country.

## Conclusion

This project challenged me to apply my Python skills to analyze weather data and plan vacations effectively. It provided a strong foundation in data analytics and presented opportunities for continuous learning and improvement.

## Code Citations

Add additional information to the hover message in a plot:
(Found in input cell 7 of VacationPy.ipynb file)

https://discourse.holoviz.org/t/add-an-extra-field-when-hovering-in-hvplot-scatter/2331
