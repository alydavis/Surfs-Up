# Surfs Up
## Overview
This SQL database and query project helps a surf shop in Hawaii quickly analyze weather data to plan a store location. 

## Process 
The Hawaii weather dataset (.sqlite) includes weather station, date, precepitation, and temperature (&deg;F). Using SQLAlchemy in Jupyter notebooks, I built a query to filter the temperatures by month, converted the list to a DataFrame with Pandas, and output summary statisctics with the .describe() function. To present my findings to the client, I used Flask to build a webpage in Python.

## Results
June Weather Data ![June_image](Analysis/june_temp_stats.png) December Weather Data ![December_image](Analysis/dec_temp_stats.png)

There are several key Differences in the recorded weather conditions between June and December:
- Major Point 1
- Major Point 2
- Major Point 3

## Summary
High Level Summary 
Two additional queries that could gather more weather data for June and December 
This dataset only included precipitation and temperature. Additional weather data impacting surfing like windspeed and waves?
