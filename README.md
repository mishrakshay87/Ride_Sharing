# Ride_Sharing
Exploratory Data Analysis for a ride sharing application. We analyze the data to find if there are some indicators to predict driver churn behaviour. For this project, a driver is defined as churned if hedoesn't drive for 30 days.

The dataset consis of 3 csv files - 

a) driver_ids.csv - A file containing basic information about the drivers (driver id, onboarding date).
b) ride_ids.csv - A mapping between ride ids and driver ids.
c) ride_timestamps.csv - This file contains information about rides (ride duration, ride distance, pick up time etc.).

We merge the 3 datasets together to get relevant data points for our analysis.

In doing this analysis, we hope to answer the following questions - 

1) Is there a difference in the avergage ride distances made by churned vs non churned drivers?
2) How do the riding dynamics differ between the churned and non churned drivers on weekdays/weekends?
3) Is there a difference in the amount of surcharge applied to the rides of churned vs non churned drivers?


For our analysis we primarily use python's pandas library for data manipulation and seaborn for data visualization.
