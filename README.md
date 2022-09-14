# PyBer Rideshare Analysis by City Type

## Overview:
PyBer, a rideshare company, wants to create visualizations of rideshare data to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. V. Isualize has given Omar and I a brand-new assignment. We’ll create a multiple-line graph that shows the total weekly fares for each city type. We'll use Python graphing library Matplotlib, which is a favorite tool among data scientists and data anylists becasue of its robust visualization features. Additionally, we’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer. 

Using our Python skills and knowledge of Pandas, we’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we'll create a visualization for the difference between fare price, rides, and driver count between each city type and a multiple-line graph that shows the total weekly fares for each city type. To compare Ride Count and Driver Count by City Type, we created box-and-whisker plots to determine if there were any outliers that would be affecting the data.  

## Resources:
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter Notebook 6.4.8, Python 3.7.13, Pandas 1.3.5, Matplotlib 3.5.1

## Results 
  
  From the following visualizations from the dataframe, we are able to find a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.
  
  From the Ride Count Data (2019) and Driver Count Data (2019), we see that the urban cities have the highest range and amount of rides and drivers. Where as the rural has the lowest. Additionally, the entire driver count in rural cities is below the median of the suburban cities. The same for suburban cities is below the urban cities. From the % of Total Fares by City Type and % of Total Drivers by City Type, we see that the urban cities have the highest percent of total fares (62.7%) and total drivers (80.9%) where as the rural has the lowest (6.8% and 2.6%, respectfully). 
  
  From this ride-sharing summary by city type of average fares, we find that rural city types have the highest average fare per ride and highest average fare per driver. We also find that urban city types have the lowest average fare per ride and lowest average fare per driver, but they do have the highest total rides by 13 times the lowest of rural city type. From the Total Fare by City Type line chart, we find that the highest peaks of total fare for all city types is between February and March.

<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig2.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig3.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig5.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig7.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/pyber_summary.png" width="800">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Challenge_fare_summary.png" width="800">


## Summary
With the goal for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods, we have three business recommendations to the CEO for addressing any disparities among the city types. 

1. Assuming that ride share per mile is the same rate for all city types, we can find that drivers in rural cities make higher average fare per ride and per driver. But they have the lowest amount of total rides and lowest amount of total drivers. So, rural cities need more drivers to be able for the customers. We should enact additional marketing to these areas focusing on hiring drivers to have available to the customers. This would increase revenue for the overall company because rural cities make higher average fares. 
