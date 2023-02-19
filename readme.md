# Arline on-time performance analysis



## Dataset
Our dataset reports flights in the US, including carriers, arrival and departure delays, and reasons for delays from 2005 to 2008. It total weight is 2.12 Gb.         
It is downloaded from [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7)                     
Its features can be consulted [here](https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&Yv0x=D)
After data wrangling, we were left with 17014015 flights and 38 features.

 

## Summary of Findings
In the exploration, I found that: 

* Flights departure delay is mainly related to the months of the year and the weekdays. There are higher delay on Thursday and Friday, closely followed by Sunday and Monday. As for the months, the higher delays span from December to March. We extrapolate that such a distribution of the delay is related to the congestions at an airport in a period of holidays and the week-end, due to the high number of passengers and flights.

* A plane, in its youth, has higher departure delay. We have a very high departure delay for planes of age 0.
* There are high departure delay in some cities while others have a very small departure delays.
* There is a high amount of flights all months around, and the number of flights is nearly the same from one month to another.
* The number of flights per weekdays is nearly the same, except on Saturday where the number is a litte less. And Saturday is also the day with the less departure delay.
* The most used plane is of type `Fixed Wing Multi-Engine`.


## Key Insights for Presentation
For the presentation, I focus on the influence of different factors on the departure delays at an airport. Those factors are : the city, the carrier, the month, the weekday, and the plane age. I also present a comparison on the distribution departures delay and the distribution of arrival delay.        
More specifically, I present:
* The Departure and Arrival delays distribution.
* The relatisionship between a plane flights count, its mean departure delay, the mean of each delay reason (weather, NAS, ...)
* The mean departure delay per carrier
* The mean departure delay per city
* The mean departure delay per month
* The mean departure delay per weekday
* The mean departure delay per plane ages

------------------------

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.


------------------------------------------------

Dataset at : https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009

Variables description : https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&Yv0x=D

## More
> **Report date : February 2022**     
> **Written by : [Ekoue LOGOSU-TEKO](https://www.linkedin.com/in/ekouelogosuteko/?locale=en_US)**