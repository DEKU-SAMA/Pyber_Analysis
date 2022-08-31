# Pyber_Analysis
# Purpose

After completing an exploratory analysis for PyBer, a ride-sharing business, a deeper dive into reviewing the data by city type was requested by the CEO. The scope of 
work includes using Python, Pandas, and Matplotlb to create a summary DataFrame and a multi-line graph of the total weekly fares for each city type: Rural, Suburban, and 
Urban.

# Summary DataFrame Table
After merging two data sets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by city 
type.
pyber_summary_df(img)
1) The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare that a driver could make per ride. The Urban drivers 
had the lowest average fare per ride and earned significantly less than the Rural drivers.

2) The Rural city type had the least number of total drivers giving way to having the highest average fare per driver even though the ratio of total rides to total  
drivers is equivalent to the Suburban city type.

# Total Fare by City Type
This line graph is from the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped together by weeks to show the total fares by city type.
![Analysis PyBer_Fare_Summary](https://user-images.githubusercontent.com/109875421/187588516-d9b07449-d849-41d6-b9ed-be9502dc61b3.png)
All three city types start to rise to a peak at the end for February. For the Urban city type, that oscillating peak lasts through April, while the other city types wane 
in the month of March.

The Rural city type increases again leading into the month of April. The Suburban city type starts to peak again at the end of April, while the Rural city type drops 
off.
