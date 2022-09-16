# PyBer_Analysis

## Overview of the analysis

The project purpose was to create a DataFrame for the different city types fares and create a plot for analysis.   The three city type
are urban, suburban, and rural.

## Results

The first chart shows a comparison between the three city types.  The chart shows a large number of rides in the urban area.   This is a 10x greater
number of rides than the smallest rural type.   This correlated closly with the number of drivers for both.  The urban area had a much larger amount
of drivers by 20x compared to the rural area.   The average fare per ride was slightly higher in the rural area compared to both the urban and
suburban areas.   Since the amount of drivers in the rural area was less, the average fare per driver was greater for rural.

![](https://github.com/crashdean/PyBer_Analysis/blob/main/Resources/City_type_sum.png)


This second table shows the fares by week date by city type. This seperates the DatFrame into a weekly report so we can plot the DataFrame.


![](https://github.com/crashdean/PyBer_Analysis/blob/main/Resources/Sum_by_city_type.png)


Then we use the matplotlib to plot the resamled DataFrame with the corect color and lables.

![](https://github.com/crashdean/PyBer_Analysis/blob/main/Resources/Total_fare_city_type.png)

## Summary

1. Plot summary - There are obvious diffenences in the three city types when looking at the graph.  
 
*  The urban drivers with $2466.29 for the week of 2019-02-24 and a low of $1661.68 on 2019-01-06.   
*  The suburban high of $1412.74 on 2019-02-24 and a low of $721.60 for 2019-01-06, urban fare totals for the week were 57% higher than suburban 
fare totals.  The urban and suburban high totals accured in the same weeks.   
*  The rural high fare total was $501.24 on 2019-04-07 and a low of $67.65 on 2019-01-13.   
*  The rural high was only 20% of the high from the urban fare totals.  
*  The urban fares ,as seen on the plot, started off low in January and stay steady through April.   There were serveral peaks for the fares from 
late Febuary thru mid April.  
*  The suburban fare totals followed a simular plot as the urban, but with fewer noticeable peaks.
*  The urban fare totals were the lowest of the three but had multiple small peaks in fare totals.

2. Business Recommendations
*  The first recommendation would be to increase the number of rural drivers.  This might work for some rural cities, but further analysis would
need to be done to determine how many need more driver coverage.
*  Increaed profits might come from increasing drivers in the urban cities also.  Determing factors such as wait times for drivers to arrive and
missed rides do to other ride companies taking from the total rides needed.
*  Adding more drivers in key times would help to increase driver to rides needed.   Peak times could be determined from the plot and moving drivers
from one city type to another might level the amount of drivers needed.
