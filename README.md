# Bike Sharing Analysis

## Overview

### Purpose
Using Tableau, Citi Bike data for New York city was analyzed to get a better understanding of the business model. My friend Kate & I are interested in seeing if this service could be provided within Des Moines, Iowa at a profit. We have an angel investor, and are analyzing data to understand the scale and function of Citi Bike within New York.

The Tableau public files can be viewed here: [link to dashboard](https://public.tableau.com/app/profile/kojo0501 "link to dashboard")

## Results

### Checkout Times for Users
![checkout_times_for_users](https://user-images.githubusercontent.com/24308495/147860070-04a09b96-3f17-41fc-9a2f-a89088e0e124.PNG)
This data shows the duration for bike rentals. Based on this data, the signifcant portion of rentals last for less than an hour. The duration of use has a single crest at five minutes with ~147K bikes rented for that time frame. By the 14 minute mark, it's half that amount, with only ~72K bikes rented for that duration.

### Checkout Times by Gender
![checkout_times_by_gender](https://user-images.githubusercontent.com/24308495/147860071-6600ea73-ec3f-45b2-a282-90fdbfc836a3.PNG)
This has the bike duration data broken into gender categories. Men are signficantly more likely to rent the Citi Bikes than women. Based on the shape of the lines it seems women are likelier to ride slightly longer than men, on average.

### Trips by Weekday per Hour
![trips_by_weekday_per_hour](https://user-images.githubusercontent.com/24308495/147860075-f1ca435a-52d1-470a-a522-e19d7a2245aa.PNG)
Based on this data, bikes are most frequently rented during weekday morning commute hours (8AM-9AM) and weekday evening commute/dinner hours (5PM-7PM). The glaring exception to this is Wednesday evenings which have significantly fewer riders than other weekdays. Weekend usage is relatively steady between 9AM-8PM, with Sunday having a higher rate of usage than Saturday.

### Trips by Gender (Weekday per Hour)
![trips_by_gender_weekday_per_hour](https://user-images.githubusercontent.com/24308495/147860077-3a96347b-2edf-4db9-8c9d-02fddac46cc5.PNG)
Men and women have similar patters of usage based on Weekday and time of day. There's no notable disparity where either gender signficantly favors one day/time over the other. It is worth noting that "unknown" gender has a higher rate of usage on Saturday and Sunday than might be expected, in comparison to male/female; this may be because more non-subscribers are riding on the weekend, and there may be a less demogrpahic data collected on those who do not subscribe to this as a service.

### Trips by Gender (by Weekday)
![trips_by_gender_by_weekday](https://user-images.githubusercontent.com/24308495/147860078-a477f41b-7d64-4e9d-b32d-f0403c3d77d4.PNG)
This data shows bulk signficant number of rides come from subscribers; specifically male subscribers who ride on weekdays. Customers who do not subscribe make up only a small amount of bike usage. Based on this data, we can see much of the "unknown" gender data is from "customers" and not "subscribers." This data confirms the above suspcian that there's a higher rate of "customer" riders of "unknown" genders on Saturdays.

### Top Starting Location
![top_starting_loc](https://user-images.githubusercontent.com/24308495/147860079-047dbe75-910f-4eff-83ff-50d2682722df.PNG)
The usage is clustered in Manhattan, an area with notoriously congested and hostile commuter traffic and limited parking. Considering the relatively short length of time bikes are being used, and the fact that the majority of usage is from subscribers, it seems possible that these bikes are being used to provide quicker transporation to subway stations or parking ramps.

### Top Ending Location
![top_ending_loc](https://user-images.githubusercontent.com/24308495/147860080-35a7690b-7809-4c50-9abb-08676e3a8ad5.PNG)
I chose to analyze starting location versus ending location to get a sense of how bikes may need to be arranged or staged. My concern was that there would be signficant usage from one destination to another, which would lead to a surplus that needed to be redistributed. As we can see from comparing ending locations with starting locations, they are very similar in starting/ending distribution. There are disparities but nothing to suggest that a large number of bikes would need to be moved each day.

## Summary

### Summary of Findings
The Citi Bike business model seems more about providing an alternative to the congestion of commuter driving than providing bikes for tourists. This can be seen by the ratio of subscriber use to customer use, and the areas in which it is most heavily used. A business like this one could work in Des Moines but I don't think it could be structured like the one in New York because Des Moines lacks density and doesn't have the same automobile commuter hardship; additionally, more people own cars in Des Moines, live in the suburbs, and are able to park easier in the downtown area.

### Additional Analysis
To find a model that would work for Des Moines, I would do a deeper study of pleasure cruises instead of commuter usage. Des Moines has beautiful parks that are distanced far apart, and it has bike path infrastructure to potentially support a Citi Bike service. Within the NY Citi Bike data, I recommend doing an analysis of trips that are distanced far apart, and evaluate whether it is subscribers or customers taking those trips.

Within the pool of longer trips, I would also try to evaluate whether the bikers are checking the bike back into the original station or leaving it at a distant station. I think a large cost that went unexplored in the module is the potential expense of reallocating bikes. I tried to explore that data in the starting/ending location maps analyzed above but the amount of short-distance commuter traffic makes it challenging to evaluate long-distance traffic.
