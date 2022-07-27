# Surfs Up
## Overview
This SQL database and query project helps a surf shop in Hawaii quickly analyze weather data to plan a store location. 

## Process 
The Hawaii weather dataset (.sqlite) includes weather station, date, precepitation, and temperature (&deg;F). Using SQLAlchemy in Jupyter notebooks, I built a query to filter the temperatures by month, converted the list to a DataFrame with Pandas, and output summary statisctics with the .describe() function. To present my findings to the client, I used Flask to build a webpage in Python.

## Results
**June Weather Data** <br> ![June_image](Analysis/june_temp_stats.png)<br><br> **December Weather Data** <br> ![December_image](Analysis/dec_temp_stats.png)

There are several key Differences in the recorded weather conditions between June and December:
- There were more data points available for the month of June (1,700) than Decemeber (1,517)
- Average temperature was higher in June (75&deg;F) compared to December (71&deg;F).
- Looking at the measures of spread in the data, the temperature has a wider range in December than in June. 


## Summary

This dataset only included precipitation and temperature. Surfs Up investors could consider including more weather data like wind conditions, tide levels, and tropical storms/hurricanes, as they all impact the surfing quality. These additional data queries would be valuable in determining the ideal Surfs Up location. 
