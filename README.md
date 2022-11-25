# PyBer_Analysis
## Ride Share Fare Differences Among City Types

Code ref: Pandas, Python 3.7.6, Jupyter notebook

### Overview of Project

The purpose of this analysis was to summarize the ride-share fare data by city type and identify any desparities between city types. Reccomdations listed at the bottom of this report. The results are presented below and located in the Pyber_Cahllenge file.

## Summary of Ride-Share Fare Data
### Results: 
* Two datasets (ride_data & city_data) were combined to create dataframes organizing total rides, average fare, total drivers, and driver fare average by the three city types: Urban, Suburban, & Rural.

![Screen Shot 2022-11-21 at 4 20 24 PM](https://user-images.githubusercontent.com/115188500/203160374-8cc73758-4528-49e1-bb9b-0547b0c82573.png)

## Analysis of 2019 Fares
### Results:
* A new dataframe was created to display the average fare for each week starting 2019-01-01 through 2019-04-29 in the three city types and plotted on a line chart. See Fare Summary.png below.

![Screen Shot 2022-11-21 at 4 36 28 PM](https://user-images.githubusercontent.com/115188500/203162953-f2766d44-3be6-437f-a14c-1e24d4dd14b5.png)

### Detailed Results
* As displayed on the dataframes and chart you can see that rides in the Rural city type were significantly lower than that of Suburband and Urban, Urban having the most rides. Due to the low demand in the Rural city types fares were higher on average and per driver while the Urban cities had a higher demand in ride share resulting in loweer fares on average. 
* Based on these results it appears that ride share trasnportation is likley unaffordable and impractical for residents and travelers due to the lack of drivers, lack of demand, and likley high milage traversing the rural landscape. 
* For Urban and Suburban areas, ride share transportation seems to be more frequently called apon, available due to a high number of drivers and affordable likely due to the short distances between destinations. 
* Drivers are more likley to earn a high wage in Urban and Suburban city types due to the frequecy of demand.
### Suggested actions for CEO
1. Rural city type ride share service may be unaffordable to most residents. Consider providing scheduled ride share depatures to popular destinations with larger vehicles, this way multiple passengers can share a vehicle resulting in lower fares per individual while dirvers maintaine their ovreall fare.
2. Further analysis could be conducted to see which months results in higher or lower fares. It is unclear why some fares spike over the weeks displayed in the current chart. Weather and events could factor, however this analysis included several different cities across different regions with different weather.
3. Suburban ride share demand was less than half of the Urban city types, however, the fares were more than double the amount Urban drivers averaged. Suggest drivers alternate their driving service areas between Urban and Suburban on a regular basis. More analysis could be done to track mileage accumulation between city types and fare output over a period of time.
