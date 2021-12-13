# Surfs_Up

## Project Overview

The purpose of this analysis was to utilize SQLAlchemy, a query tool designed for use with SQLite, to analyze the weather data on Oahu Island. W. Avy, your  primary investor, is concerned that the weather may negatively impact your planned “Surf ‘n’ Shake” business and before he invests in the business, would like confirmation that the weather will be suitable for surfing and ice cream. Once the data was collected, it was imported into Jupyter Notebook via SQLAlchemy and using the “create engine function”  allowed the data to be queried. The data was then converted into a data frame and  graphed visually for review. Finally, the data was then shared using Flask, a web framework which could be used to share our analysis and data in real time.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Goals:**

1. Retrieve the precipitation data and plot the data.
2. Find the number of stations and determine the most active stations.
3. Find the low, high, and average temperatures and plot the highest number of observations.
4. Create a precipitation, stations, monthly temperature, and statistics route.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Summary**

1. Retrieve the precipitation data and plot the data.

![Goal 1](https://user-images.githubusercontent.com/92111396/145828269-f14e9a83-da6c-46a1-9a49-5fb4ae0dac3f.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Goal%201.PNG


2. Find the number of stations and determine the most active stations.

![Goal 2](https://user-images.githubusercontent.com/92111396/145828279-cbfe3135-70f1-4a50-8ff0-533e3146122a.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Goal%202.PNG

3. Find the low, high, and average temperatures and plot the highest number of observations from the most active station.

![Goal 3 - 1](https://user-images.githubusercontent.com/92111396/145828287-8b8521ee-edf2-4a96-ac5f-d4f3962f8048.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Goal%203%20-%201.PNG

![Goal 3 - 2](https://user-images.githubusercontent.com/92111396/145828307-a538f255-b02c-43ca-97be-0d7b5e327f26.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Goal%203%20-%202.PNG

4. Create a precipitation, stations, monthly temperature, and statistics route.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Resources**
-Data Source: hawaii.sqlite 
-Software: Python 3.7.10, Visual Studio Code, 1.38.1, 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Module 9 - Challenge** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Purpose##**

The purpose of this analysis was to analyze the temperature trends for the months of June and December in Oahu to determine if the surf and ice cream shop business would be sustainable year-round. This analysis saw the data being imported via SQLAlchemy and queried using the “create engine” function. The imported data was converted into a data frame and filtered by month, and the summary statistics for the months of June and December produced using the “describe function”.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Results##**

![Summary Statistics - June](https://user-images.githubusercontent.com/92111396/145825691-6ff188d1-51b8-45ff-aca5-4c7f5b2884c6.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Summary%20Statistics%20-%20June.PNG

![Summary Statistics - December](https://user-images.githubusercontent.com/92111396/145825486-c41ecb1f-0f11-4d65-9ba2-e87a7b5d27b3.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Summary%20Statistics%20-%20December.PNG

![Temperature List - June](https://user-images.githubusercontent.com/92111396/145824989-47d60782-4a6d-4a1d-a735-f1f0dd157115.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Temperature%20List%20-%20June.PNG

![Temperature List - December](https://user-images.githubusercontent.com/92111396/145825008-d76a198d-345d-4cdc-8ee8-175dd023d4ae.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Temperature%20List%20-%20December.PNG

-	June on average is slightly warmer than December, however this may be due to the fact that June has more datapoints compared to December itself. The average temperature for June is 74 °F and December is 71 °F.

-	The maximum temperature are comparable; June has a maximum temperature of 85 °F , while December has maximum temperature of 83 °F. 

-	The minimum temperature differ significantly, particularly for surfing temperature in Hawaii. June has a minimum temperature of 64 °F, while December has a minimum temperature of 56 °F.

-	June has more temperature data points than December. June has 1700 data points where as December only 1517 data points.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Summary##**

  From the results we can conclude that the temperatures for June and December are relatively comparable and would be suitable for surfing all year long. There are two areas of concern however: one  would be the minimum temperature for December which was 56 °F. While surfing is more than possible at this temperature and would most likely not deter avid enthusiasts, it is unlikely that tourists or beginners would be inclined to pursue the activity at this temperature. The minimum temperature for December however differs greatly form the average temperature for the month which is 71 °F and much more of a comfortable temperature for surfing as well as for eating ice cream. Due to this variance, it is likely that the minimum temperature was an outlier and from the statistic quartiles it is evident that the temperature does fall closer to the average and high temperatures overall. The next area of concern would be the fact that compared to June, December has 183 fewer data points. This could cause problems when comparing the two months and it must be decided as  data scientist how we would want to approach this for comparison; that is to say would we fill the blank data points with null values (NaN) or fill it with the average temperature for that month. 
  
  Two additionally queries that I would also perform would be to determine the length of the rain fall itself as well as what point of the day it occurred. If the majority of the rainfall happened overnight in a short but intense downpour, this would have less of an impact on the ice cream and surf shop business than if the overall rainfall occurred over a longer period of time during the day. Similarly, I would also query and produce the summary statistics for all months, not just June and December.  This would allow us to see the overall temperature trends and see if there are any other months that would have temperatures and precipitation levels that would may impact the business. This data could then be used to determine which months may be expected to have “slow business” and used to determine when upgrades and renovations could be conducted, when large inventory restock should occur, as well as when additional staff may need to be taken on or existing staff should be encouraged to use their vacation. 

  Overall, simply examining the temperature statistics for the months of June and December do not provide any relevant information regarding temperature trends or weather trends as whole. A more complete approach would be to at least compare the temperature data for all months, which would be simple to produce using the code we have (simple change the month) and additionally add in the precipitation data as well. From a business analysis view, it would also be best to retrieve data on tourist information to the island to determine peak seasons which would allow us to predict the “busy” seasons of our new business.
