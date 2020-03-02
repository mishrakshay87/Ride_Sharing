# Ride_Sharing
Exploratory Data Analysis for a ride sharing application. We analyze the data to find if there are some indicators to predict driver churn behaviour. For this project, a driver is defined as churned if hedoesn't drive for 30 days.

The dataset consis of 3 csv files - 

* driver_ids.csv - A file containing basic information about the drivers (driver id, onboarding date).
* ride_ids.csv - A mapping between ride ids and driver ids.
* ride_timestamps.csv - This file contains information about rides (ride duration, ride distance, pick up time etc.).

We merge the 3 datasets together to get relevant data points for our analysis.

In doing this analysis, answered the following questions - 

1) Is there a difference in the avergage ride distances made by churned vs non churned drivers? - 

We see that there is a difference between the ride distances of the drivers who churned vs drivers who didn’t churn, the differences primarily come into play during the weekdays when the non churned drivers make longer rides ~12miles as compared to the drivers who churned ~ 2.5 miles.

2) How do the riding dynamics differ between the churned and non churned drivers on weekdays/weekends? -

* The drivers that were not churned accept more requests early morning and late night.
* On the weekdays, the distribution of requests is almost identical between the two sets of drivers.

3) Is there a difference in the amount of surcharge applied to the rides of churned vs non churned drivers? -

We notice that the surcharge percentage (surcharge duration/ride duration) is higher for non churned drivers than it is for churned drivers and the difference becomes greater on the weekends. This seems to be a major predictor of whether a driver is going to churn or not.

For our analysis we primarily use python's pandas library for data manipulation and seaborn for data visualization.
