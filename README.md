# Surfs_Up

## Project Overview

The purpose of this analysis was to utilize SQLAlchemy, a query tool designed for use with SQLite, to analyze the weather data on Oahu Island. W. Avy, your  primary investor, is concerned that the weather may negatively impact your planned “Surf ‘n’ Shake” business and before he invests in the business, would like confirmation that the weather will be suitable for surfing and ice cream. Once the data was collected, it was imported into Jupyter Notebook via SQLAlchemy and using the “create engine function”  allowed the data to be queried. The data was then converted into a data frame and  graphed visually for review. Finally, the data was then shared using Flask, a web framework which could be used to share our analysis and data in real time.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Goals:**

1.
2.
3.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Summary**

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

-	June has more temperature data points than December. June has 1700 data points where as December only 1517 data points.

![Summary Statistics - June](https://user-images.githubusercontent.com/92111396/145825691-6ff188d1-51b8-45ff-aca5-4c7f5b2884c6.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Summary%20Statistics%20-%20June.PNG

![Summary Statistics - December](https://user-images.githubusercontent.com/92111396/145825486-c41ecb1f-0f11-4d65-9ba2-e87a7b5d27b3.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Summary%20Statistics%20-%20December.PNG

![Temperature List - June](https://user-images.githubusercontent.com/92111396/145824989-47d60782-4a6d-4a1d-a735-f1f0dd157115.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Temperature%20List%20-%20June.PNG

![Temperature List - December](https://user-images.githubusercontent.com/92111396/145825008-d76a198d-345d-4cdc-8ee8-175dd023d4ae.PNG)
https://github.com/mcbride249/surfs_up/blob/main/Resources/Temperature%20List%20-%20December.PNG

-	June on average is slightly warmer than December, however this may be due to the fact that June has more datapoints compared to December itself. The average temperature for June is 74 °F and December is 71 °F.
-
-	The maximum temperature are comparable; June has a maximum temperature of 85 °F , while December has maximum temperature of 83 °F. 

-	The minimum temperature differ significantly, particularly for surfing temperature in Hawaii. June has a minimum temperature of 64 °F, while December has a minimum temperature of 56 °F.


