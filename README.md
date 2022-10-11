# PyBer Challenge Analysis
## Purpose:

Use Python and Pandas to create summary dataframes for ride-sharing by city types. Use matplotlib to create a line graph in order to show the total fares of each city type by weeks. This chart will help decision makers at Pyber see the data in a readable matter so they can look at the differences in different city types and help them make certain decisions.

## Results:

### Pivot Table of Pyber Average Summary
The table below is a result from merging two data sets (cities_data.csv and ride_data.csv) and then using the groupby() function for find the total rides, total drivers, total fares and then use them to find the average fare per ride and driver.\
![Image](Pyber_Average_Summary.png)
- We can see Urban cities have more than twice the amount of total rides as suburban cities, but Urban cities have significantly more drivers than rides being requested, which then results in a lower average fare per driver. 
- Ubran cities have the lowest average fare per ride but have the largest amount of total rides, resulting in a low average fare per ride compared to suburban and rural cities. 
- Rural drivers have a significantly larger average fare, although there is much less ride requests going on in rural cities.
\
### Total Fare by City Type
The table below is a result from using the pyber summary dataframe and grouping by type and dates and then calculating the sum of the fares in each cross category. Looking specifically at the first quarter of 2019, and then grouping the dates into week long sums. Creating a line chart summary for the total fares in each city type for the first quarter in 2019. 
![Image](pyber_fare_summary_chart.png)
- We can see the weekly Urban fare ranges from approximately $1500-$2500; Suburban fare $500-$1500; and Rural fare $0-500.
- There was a peak in February 2019 for all city types.
- Urban always earned more weekly to Suburban. Suburban always earned more weekly to Rural.\
\
## Summary:

- Incentivize or suggest drivers in Urban cities also seek out rides in suburban and rural areas.
- Reduce the number of drivers in Urban cities.
- Increase the average fare per ride in Urban cities.
