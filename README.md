API-based data retrieval and analysis using Python, OpenWeatherMap, and Geoapify. Collects, analyzes, and visualizes weather data to identify ideal vacation destinations.

Description
This project was completed as part of the GWU Data Analytics Bootcamp’s API module. It focuses on requesting and processing data from external APIs, analyzing patterns, and applying the results to a travel-related use case. The work is split into two Jupyter Notebooks:

WeatherPy – Weather Data Collection & Analysis

Generates a random set of cities for analysis using Python libraries.

Retrieves weather data per city via the OpenWeatherMap API.

Saves the collected data to CSV for use in subsequent analysis.

Creates scatter plots showing correlations between latitude and wind speed, temperature, cloudiness, and humidity.

Splits the dataset into Northern and Southern Hemispheres, then generates linear regression plots for each weather metric by hemisphere.

VacationPy – Destination & Hotel Filtering

Loads the WeatherPy CSV dataset.

Visualizes all cities on an interactive hvPlot map.

Filters cities based on “ideal” weather conditions for vacation travel.

Uses the Geoapify API to locate hotels within 10,000 meters of selected city coordinates.

Displays hotel name and country as interactive hover data on the map.

This project not only reinforced API integration and data visualization skills but also showed how the same methods could be adapted for real-world use cases—such as extracting container information from ocean carriers with minimal code changes.
