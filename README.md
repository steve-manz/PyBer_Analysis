# PyBer_Analysis - Module 5
---
## Class Exercises in PyBer.ipynb
#### Data files are Resources\city_data.csv and Resources\ride_data.csv
---
---
## Challenge - PyBer_Challenge.ipynb
---
#### The purpose of the PyBer Challenge is to perform additional Pyber data for the rural, suburban and urban cities, including the:
•	Total rides
•	Total drivers 
•	Total fare (expressed in $’s)
•	Average fare by ride
•	Average fare per driver
In addition, we used the ride data to calculate the total fare every day from January 1, 2019 to April 28, 2019 for each type of cities. We uploaded the data in two csv files, the city_data and ride_data, and using pandas, numpy and matplotlib.pyplot dependencies, we created a series of new data frames. As a result of the analysis, we determined that the urban cities had the majority of the total rides and total drivers, and also had the highest total fares. The urban cities had the lowest average fare per ride and the average fare per driver. The rural cities average fare per ride and per driver were the highest, but because there were only 125 rides, which was only 5% of the total number of rides. More than 30% of the total fare revenue were generated in suburban cities, despite have proportionally lower number of rides. 
The biggest challenge for me was trying to create pivot table for the line graph, I was able to create almost all of the data frames required in the instructions exception item 7., “Reset the index, then create a pivot table DataFrame with the Date as the index and columns = 'City Type'. The Fare for each Date should appear in each row.”  When I attempted to create the pivot_table using “table = pd.pivot_table(fare_datetime_df, index=["Date"], columns=["Fare"], values=["City Type"])” but I had an error messages. 
The demand for PyBer rides in rural cities is very weak, and the fares and number of rides does not justify having PyBer services in certain remote areas. I would make three recommendations: 
•	Create data frame with the population of each city/town, and compare to the number of rides
•	I would compare the total rides and total fare by each day of the week. It would be helpful to know if there is more demand for the weekends vs, week days, and if so, we could recruit more drivers for the weekend. 
•	Finally, it would be helpful if we could track the number of drivers each day, and compare with the number of rides; this would provide a better idea on the utilization rate of the drivers. 




