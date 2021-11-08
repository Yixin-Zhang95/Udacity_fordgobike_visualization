# Udacity_fordgobike_visualization
# (Ford GoBike System Data)
## by (Yixin Zhang)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.


## Summary of Findings

> Distribution of "__duration_sec__" is heavily left-skwed, I performed the log-transformation to make the points more normally distributed.

> Becase the dataset comes from Feburary fordgobike results, "__Monthly usage__" only has Feburary result.

> As expected, in "__daily usage__", more bikes are used in weekdays. While for the "__Hourly usage__", 8 am and 5 pm have relatively high usage.

> For "__age__" distribution, there are lots of outliers bigger than 60 years old. But after log transformation, it is more easily to identify most ages are around 25 - 40 years old.

> For "__user type__", more than 90% users are subscribers.

> In average, customer has higher usage time compared with subscriber. But the usage time distribution of the customer is more spread which may explain why its average time is higher.

> Users between 25 - 40 years old have higher usage counts.

> In both "customer" and "subscriber" groups, their usage counts tendency is similar, which higher usage happens in weekdays and in rush hours (8 am and 5 pm).

> In average, "customer" users have higher usage time than "subscriber" users. For both two types of users, average usage time is higher in weekends than weekdays.

## Key Insights for Presentation

> Users use these bikes more frequently in weekdays, especially in rush hours (8am and 5pm), but the average usage time is higher in weekends and in 3am !
