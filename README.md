# PyBer Rideshare Analysis by City Type

## Overview:
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Purpose:
The purpose of this analysis is to visualize the difference in PyBer traffic between different city types. Using both pandas and matplotlib, we are supposed to visualize the difference between fare price, rides, and driver count between each city type. The questions we ask ourselves are: what is the average fare price per city type, how many drivers are in each city type, and how many rides are given per city type? By using pandas data frame and matplotlib visualization tools, we can easily analyze and plot the results in a comprehensive way. Although we were not asked specifically about outliers in the challenge, the module allowed us to plot box and whisker plots to visualize potential outliers within our dataset.

## Resources:
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter Notebook 6.4.8, Python 3.7.13, Pandas 1.3.5, Matplotlib 3.5.1

## Results 
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type

From the Ride Count Data (2019) and Driver Count Data (2019), we see that the urban cities have the highest range and amount of rides and drivers. Where as the rural has the lowest. Additionally, the entire driver count in rural cities is below the median of the suburban cities. The same for suburban cities is below the urban cities. From the % of Total Fares by City Type and % of Total Drivers by City Type, we see that the urban cities have the highest percent of total fares (62.7%) and total drivers (80.9%) where as the rural has the lowest(6.8% and 2.6%, respectfully).

<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig2.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig3.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig5.png" width="600">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Fig7.png" width="600">

From this ride-sharing summary by city type of average fares, we find that rural city types have the highest average fare per ride and highest average fare per driver. We also find that urban city types have the lowest average fare per ride and lowest average fare per driver, but they do have the highest total rides by 13 times the lowest of rural city type. From the Total Fare by City Type line chart, we find that the 

<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/pyber_summary.png" width="800">
<img src="https://github.com/laneyberm/PyBer_Analysis/blob/main/Analysis/Challenge_fare_summary.png" width="800">
A multiple-line chart of total fares for each city type.

## Summary
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. 
By replacing the math and reading scores for ninth graders at Thomas High School with NaNs, we created a better analysis for the school board of the Math and Reading Test Scores. For the district, the % Passing Math, % Passing Reading and % Overall Passing was reduced to 74.8, 85.7, and 64.9 respectfully. The % Overall passing for Thomas High School changed from 65% to 90%. Additionally, Thomas High School moved to the Top Performing School List when the ninth graders were replaced. 
