# pythonapi_challenge
This repository contains Jupyter Notebook files (WeatherPy.ipynb and VacationPy.ipynb) for WeatherPy and VacationPy respectively. The notebooks provide detailed explanations and code for data analysis, visualization, and interpretation.

## Part 1: WeatherPy
In this part of the project, a Python script is created to visualize the weather of over 500 cities of varying distances from the equator. citipy Python library and the OpenWeatherMap API are utilized to gather weather data for the cities. The deliverable includes:
 - Plots to Showcase the Relationship Between Weather Variables and Latitude
 - Generate scatter plots to showcase the relationships between latitude and temperature, humidity, cloudiness, and wind speed.
 - Compute linear regression for each relationship, separating plots into Northern and Southern Hemispheres. Include the regression line, formula, and r values in the plots.

## Part 2: VacationPy
In this part, weather data obtained in Part 1 is used to plan future vacations in the ideal location. Jupyter notebooks, the geoViews Python library, and the Geoapify API are utilized to create map visualizations. The deliverable includes:
 - Map points for every city in the DataFrame, with the size of the point representing the humidity.
 - Find Ideal Weather Conditions
 - Narrow down the DataFrame to find cities with specific weather conditions, such as temperature, wind speed, and cloudiness.
 - Find Nearby Hotels
 - Use the Geoapify API to find the first hotel located within 10,000 meters of each city's coordinates.
 - Create a new DataFrame to store the city, country, coordinates, and humidity.

## Linked References
- https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html#pandas.to_datetime
- https://docs.python.org/3/library/datetime.html#strftime-and-strptime-behavior
- https://stackoverflow.com/questions/65016116/pandas-converting-a-datetime-y-d-m-hm-to-y-m-d-hm
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html
