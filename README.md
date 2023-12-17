# Sqlalchemy-challenge
Analyzes Hawaii climate data including precipitation and temperature observations from multiple weather stations.

Analysis overview including commands
Imports necessary Python libraries like Pandas, SQLAlchemy, Matplotlib, NumPy, and datetime

Reflects SQLite database tables into SQLAlchemy models

Performs a series of climate data analyses and visualizations:
Precipitation analysis over the last year of data
Summary statistics of the precipitation data
Number of weather stations
Most active weather stations
Temperature data for the most active station
Histogram plot of the last 12 months of temperature

This resulted in the analysis providing a timeseries of precipitation data, a histogram plot of the last 12 months of temperatures, and printouts of query results like count of stations. 

# Climate Analysis API
This API serves climate data from a SQLite database containing temperature and precipitation measurements from weather stations in Hawaii.

The API allows accessing:

Precipitation data over past year
List of weather stations
Temperature observations from most active station over past year
Minimum, average, and maximum temperatures for date range queries

Endpoint include:
Retrieving JSON of date and precipitation for past year of data
JSON list of all station names in dataset
Queries for temperature observations from most active station over past year. 
Returning min, avg, and max temperautres form start date onward
Retrieving min, avg and max temps for given start-end date range