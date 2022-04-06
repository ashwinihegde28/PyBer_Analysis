# PyBer_Analysis
Analyze and Visualize the Ride sharing data using the power of Python, Pandas and Matplotlib


## Project Description
Creating visualizations of rideshare data for PyBer, a ride-sharing business to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. This analysis aims to create a summary Data frame that will display ride-sharing information by city type (rural, urban, suburban) using the Python skills and knowledge of Pandas along with multiple-line graph using Matplotlib that shows the total weekly fares for each city type.



## Results:

### Summary DataFrame
Calculated the average fare per ride and average fare per driver in the summary DataFrame for all city types by merging two data sets and using the groupby() functions. The following screen shot displays the numbers
![Summary](https://github.com/ashwinihegde28/PyBer_Analysis/blob/main/Resources/FormattedPyberSummary.PNG) <br>

1. The Urban city type had more total drivers than total rides, because of which the Urban drivers had the lowest average fare per ride compared to other city types. The total number rides are the highest compared to rural and suburban.
2. In Rural city type, the total drivers are lesser making highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type. It has the least number of rides.
3. The Suburban analysis has always been in between urban and rural. 



### Total Fare by City Type with multiple-line chart

From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks using pivot() and resample() to show the total fares by city type. The multiple-line chart "Total Fare by City Type" visualizes the data from January through April 2019.
 - Total fare is at peak from mid of February for all the city types, in April for rulral and urban only.
 - Rural and Suburban witness less during March but not Urban. 
 - The month of May witnesses a drop in fare again
 

![ResampledDf](https://github.com/ashwinihegde28/PyBer_Analysis/blob/main/Resources/ResampledDf.PNG) <br>




![PyBerGraph](https://github.com/ashwinihegde28/PyBer_Analysis/blob/main/Resources/PyBerGraph.PNG) <br>

## Summary
1. Since there are a greater number of drivers available in urban, PyBer can come up with any innovative process of utilizing the extra drivers productively so that the income of the driver is also increased.
2. Rural has a smaller number of driver and rides, increasing the driver count will help to increase the average fare. This is also beneficial to the rural population.
3. Increasing the fare during peak months will increase the sale in other months since people tent to avoid peak charges.
