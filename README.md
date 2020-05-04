# PyBer_Analysis - Module 5
---
## Class Exercises in PyBer.ipynb
#### Data files are Resources\city_data.csv and Resources\ride_data.csv
---
---
## Challenge - PyBer_Challenge.ipynb
---
#### The purpose of the PyBer_Challenge is to perform additional analysis for the rural, suburban and urban cities, including the total rides, total drivers, total fare (expressed in $’s), average fare by ride and the average fare per driver. In addition, we used the ride data to calculate the daily fare for the period between January 1, 2019 to April 28, 2019 for each type of cities. We uploaded the data in two csv files, the city_data and ride_data, and using pandas, numpy and matplotlib.pyplot as our dependencies, we created a series of new data frames. As a result of the analysis, we determined that the majority of the total rides, total drivers and the highest total fares were in urban cities. But the urban cities had the lowest average fare per ride and the average fare per driver. The rural cities had the highest average fare per ride and per driver, but because there were only 125 rides, which was only 5% of the total number of rides. More than 30% of the total fare revenue were generated in suburban cities, despite have proportionally lower number of rides. 
---
#### The biggest challenge for me was trying to create pivot table for the line graph, I was able to create almost all of the data frames required in the instructions exception item 7., “Reset the index, then create a pivot table DataFrame with the Date as the index and columns = 'City Type'. The Fare for each Date should appear in each row.”  When I attempted to create the pivot_table using “table = pd.pivot_table(fare_datetime_df, index=["Date"], columns=["Fare"], values=["City Type"])” but I had an error messages. 
---
#### The demand for PyBer rides in rural cities is very weak, and the fares and number of rides does not justify having PyBer services in certain remote areas. I would make three recommendations: 
##### 1. Create data frame with the population of each city/town, and compare the city's size to the number of drivers. I could determine that we have too many drivers in small towns or not enough for bigger cities.
##### 2. Compare the total rides and total fare by each day of the week. It would be helpful to know if there is more demand for the weekends vs, week days, and if so, we could recruit more drivers for the weekend.
##### 3. Finally, it would be helpful if we could track the number of drivers each day, and compare with the number of rides; this would provide a better idea on the utilization rate of the drivers. 




