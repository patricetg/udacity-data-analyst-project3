# Airline on-time performance analysis

## Goal
We are going to investigate flights' datasets in order to gain insights on airline on-time performance from 2005 to 2008. The goal is to understand reasons that tend to make flights delayed or cancelled. In particular, we will be interested in the following key questions:

* Are there certain departure cities that are home to more delays or cancellations?
* What are the preferred periods for flights to occur ?
* When is the best day of week or month of year to fly to minimise delays ?
* Are there any changes over multiple years?
* Do older planes suffer more delays?
* How well does weather predict plane delays?


We are going to explore the data while having three identities in mind:
*  A passenger, who want to know before hand if he may be stuck in an airport waiting for his flight, and plan accordingly.
* An airport administrative, who want to understand issues causing delay, in order to know what he can work on so that he improve the aiport performance.
* A freight company administrative, who also want to understand issues causing delay, in order to know which aspect of his planes he should take note of so that he improve his planes performance.


## Dataset
The dataset reports flights in the US, including carriers, arrival and departure delays, and reasons for delays from 2005 to 2008. It total weight is 2.12 Gb.         
It is downloaded from [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7)                     
Its features description can be consulted [here](https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&Yv0x=D)
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
For the presentation, I focus on the influence of different factors on the departure delays at an airport. Those factors are : the city, the carrier, the month, and the weekday. I also present a comparison on the distribution departures delay and the distribution of arrival delay.        

## More
> **Report date : February 2022**     
> **Written by : [Ekoue LOGOSU-TEKO](https://www.linkedin.com/in/ekouelogosuteko/?locale=en_US)**