# PyBer_Analysis
PyBer with Matplotlib
## Purpose
We were asked by V. Isualize to help Omar create a summary Data Frame of ride-sharing data by city type. Using Pandas and Matplotlib, we created graphs that shows the total weekly fares for each city type (urban, suburban, rural). 
## Results
We started by merging the two data sets and used the groupby() function to easily review all of the data and checked to ensure the merge was successful, by using the head() function: 
image.png
We were then able to determine the totals for each city type, which showed that the Urban city type had more total drivers than total rides, but had the highest total ride count. Rural city types had the highest fare per ride, but the total fares was highest in urban city types. 
image.png 
We ultimately discovered by creating a multiple line plot, which showed us:
![Alt text](../../../../c:/Users/casey/PyBer_Analysis/Resources/PyBer_fare_summary.png)
1. All city types had a similar peak at end-February. 
2. Suburban city types did not have additional peaks after the end-February high, but started to rise toward the end of April. 
3. Urban city types had a pretty consistent peak schedule, fluctuating evenly through April. 
4. Rural city types had a relatively consistent fare schedule with slight peaks, but there was not as much fluctuation in this city type compared to urban and suburban. 
## Summary
Based on the results, there should be a focus on hiring more rural drivers to keep up with the demand for rides. As there were less drivers than total rides for rural cities, the average fare per ride was increased but the overall ride count was lower than the other categories. 
Another suggestion would be to reassign urban drivers that are not receiving rides to the rural areas for additional compensation due to the average fare rate increasing in the rural areas. There would be several dependencies on having drivers switch areas, such as mileage between their starting destination vs the rural area, but it could be considered. 
An item that warrants looking in to is the average miles per ride based on city type. One could assume that ubrna rides have a lower mileage average than suburban or rural. 
