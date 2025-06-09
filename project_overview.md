# Summary

## Overview
This project is associated with Udacity's Data Analyst Nanodegree program. The goal of this project is to analyze local and global temperature data and compare the temperature trends near where I live to overall global temperature trends.

---

## Data Provided
Training Data:
* city_data.csv - average yearly temperatures for the city of Detroit
* global_data.csv - global average yearly temperatures

For reference:
* This data was extracted from a SQL database.


## Submission Files
* Exploring_Weather_Trends_Presentation.pdf -- a report documenting observations regarding global vs local weather trends

---

## Data Handling
Data Wrangling
- Queried global & Detroit weather data from a Udacity SQL database & exported data to Excel
- Temperatures were missing for the first fews years of the Detroit dataset. Opted to only use years that temperatures were present in both datasets: 1750 - 2013
- Calculated 5-year, 7-year, and 10-year moving averages (MA)
- Calculated differences in global & detroit 10-year MA temperatures.

Data Exploration
- Graphed each & decided 10-year MA was the best to use. It smoothed out the data while still providing good information.

Data Visualizations
- Created a line chart of global vs Detroit 10-year MA temperatures. Included a trend line for both global & detroit average temperatures.
- Created column chart with difference in global & Detroit 10-year MA temperatures.

## Observations
1) Is your city hotter or cooler on average compared to the global average? Has the difference been consistent over time?
- Overall Detoit averages temperatures are very close to global average temperatures.
- Since 1769, Detroit temperatures have been with in 1 degree Celsius of global temperatures.
- Detroit is generally ~0.2 degrees Celsius colder than global temperatures.

2) How do the changes in your city's temperatures over time compare to the changes in the global average?
- Detroit temperatures seem to be following suit with the changes in global temperatures.
- The temperatures in Detroit are changing alomg with the global temperatures. I fyou look at the "Moving Average" chart, the linear regress for Detroit temperatures is roughly parallel to the global temperatures.

3) What does the overall trend look like? Is the world getting hotter or cooler? Has the trend been consistent over the last few hundred years?
- Temperatures seem to be slightly increasing over time both locally & globally.
- About 1 degree Celsius from 1769 - 2013.
- It is hard to say longitudically since we only have data dating back to 1769, and 244 years of data isn't enough to rely on when we consider how old the earth is.