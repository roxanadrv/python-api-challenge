# python-api-challenge
Overview
This repository contains Python scripts focused on using APIs to analyze weather data and potential vacation destinations. The main project is structured in the python-api-challenge directory, which includes two key subdirectories: WeatherPy and VacationPy.
WeatherPy
In this section, a Python script (WeatherPy.ipynb) is used to visualize the weather of 500+ cities across the world of varying distance from the equator. The script utilizes the OpenWeatherMap API to perform requests for weather data in JSON format, which is then analyzed using Python libraries such as Pandas, Matplotlib, and SciPy.

Key Steps in WeatherPy.ipynb:

Generating a list of cities based on random latitude and longitude combinations.
Performing API calls to gather weather data for these cities.
Creating visualizations (scatter plots) to showcase relationships between various weather attributes and latitude.
Saving output data and figures in the output_data folder.
VacationPy
VacationPy.ipynb focuses on using weather data to plan future vacations. This script uses Jupyter Gmaps and the Google Places API to create heatmaps for weather parameters and find ideal hotels within a specified radius of the best weather cities.

Key Features:

Data from WeatherPy (output CSV file) is used to identify potential vacation spots.
maps are generated to visualize the humidity of cities across the globe.
Google Places API is used to find hotels near these ideal locations.

Installation and Requirements
To run the notebooks in this repository, you need to have Python installed, along with several libraries including Pandas, Matplotlib, NumPy, Requests, and SciPy. For mapping functionalities in VacationPy, Jupyter Gmaps and the Google Places API are required.

Ensure you have the following API keys set up:
OpenWeatherMap API key (for WeatherPy)
Google Places API key (for VacationPy)
These keys should be stored in a file named api_keys.py as variables weather_api_key and geoapify_key respectively.

Usage
Clone the repository to your local machine.
Navigate to the python-api-challenge directory.
Open the Jupyter Notebooks (WeatherPy.ipynb and VacationPy.ipynb) and execute the cells in sequence.
