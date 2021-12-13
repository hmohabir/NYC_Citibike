# Using Tableau to present data


## Overview of the analysis:

The purpose of this analysis is to present data that was gathered previously and present it in a readable format via Tableau. The data collected showed bike sharing servive in New York City for August, 2019.

## Resources

Jupyter Notebook
Tableau Public 2021.3
Ride Sharing data provided by Citi Bike System Data page (https://ride.citibikenyc.com/system-data)

## Results

### Data cleaning

The raw data was cleaned to obtain trip duration in a DateTime format
![Data cleaning](https://github.com/hmohabir/NYC_Citibike/blob/main/Cleaned%20data.PNG)

### Tableau story

[Link to Tableau dashboard](https://public.tableau.com/app/profile/harry.mohabir/viz/NYC_CitiBike_Visualizations_16387611210080/Overallfindings?publish=yes)

#### Starting and ending locations
![Starting and Ending locations](https://github.com/hmohabir/NYC_Citibike/blob/main/Starting%20and%20ending%20locations.PNG)

The rides generally originate and end at the same location. The larger and darker circles point to a higher concentration of rides vs the smaller and lighter circles. It seems as though the rides start and end at similar locations. This could be due to the fact that there is a dedicated base of general users.

#### Checkout times(duration of use)

![Duration of use](https://github.com/hmohabir/NYC_Citibike/blob/main/Duration%20of%20use.PNG)

We can see the largest number of trip durations generally last for 5 mins, for both males and females. For the unknown gender, this spreads out fro 5-30 mins. No one seems to be taking rides that lasts more than an hour.



#### Usage by time of day

![Time-of-Day Usage](https://github.com/hmohabir/NYC_Citibike/blob/main/Time%20of%20day%20Usage.PNG)

Highest usage on weekdays occur at 7-9am and 4-7pm. On weekends it is between 11am and 1pm on Saturdays and 12 - 4pm on Sundays.

#### Male vs Female riders

![Male vs Female riders](https://github.com/hmohabir/NYC_Citibike/blob/main/Male%20vs%20Female.PNG)

Even though males use the bikes three times more than females, the time-of-day usage seems to have the same. Wednesday afternoons have the lowest usage. Maybe most riders have other plans on this day.

#### Subscribers

![Subscribers](https://github.com/hmohabir/NYC_Citibike/blob/main/Subscribers.PNG)

Although males tend to subscribe a lot more than females, the higest level of subscriptions occur on Thursdays for both males and females. Understandable, Wednesdays have the lowest level.



## Summary

Additional visualizations include:

#### Bike Utilization

![Bike utilization](https://github.com/hmohabir/NYC_Citibike/blob/main/Utilization.PNG

There is no direct relation to heavier bike usage and repairs. This may poise an issue for the company. The company may want to have a robust plan for bike replacements/repairs.

#### Gender utalization

![Gender utalization](https://github.com/hmohabir/NYC_Citibike/blob/main/Gender%20utalization.PNG)

Over 82% of riders are males compared to 25% being females. About 12% are of unknown gender.

From the results, we can gather some important information:

Male users and subscribers account for the majority of trips made. The company may want to work on a plan to increase usage among females. It may want to investigate why Female usage is so much less than make usage. 
Due to the lowest usage occuring between 11pm - 7am, Maintenance can occur during this timeframe to cause the least impact to users.
Bike sharing is consistently more in urban aread vs suburban and rural areas.
Bike sharing peak times occur at standard times during commute time on weekdays. On weekends, this is not the case.


If the company was to consider introducing the bike share into new areas, they might want to consider these:

Type of environment - rural, urban, semi-urban. 
Gender percentage living in these areas.
Existing ride shares or mass transit systems already in place.


