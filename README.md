# Covid - 19’s Impact on NYC Travel 
#### Abstract: 
This project aimed to examine the affect of coronavirus 19 on New York City travel. Looking at Citi Bike ridership data January - June for 2019 and 2020, a t-test was applied to compare the difference.
## Introduction 

#### Beginning of a pandemic 
March 2020 NYC had its first confirmed case of covid-19, the 2019 novel coronavirus outbreak, first identified in Wuhan China. 
By April, the city had more confirmed coronavirus cases than China, the U.K., or Iran. 
March 22, Governor Andrew Cuomo issued an executive order closing down all non-essential businesses. 
Subway services shut down from 1am to 5am. Buses ran with enhanced services during those hours.

#### Surviving a pandemic
New Yorkers hunkered down and confirmed cases started to drop. June 8, NYC entered **Phase** 1 opening the following:
* Construction
* Agriculture & Forestry 
* Fishing & Hunting
* Retail - Limited
* Manufacturing
* Wholesale Trade

June 22, **Phase 2** opened the following:
Professional Services
* Retail
* Administrative Support
* Real Estate / Rental & Leasing
* Restaurants for Outdoor Dining


The goal of this project was to look at travel via subways, buses, bikes and brides and tunnels during the pandemic and explore how it was affected.

### Exploring Data

Here is how NYC subways, buses and bridges and tunnels were affected from 3/1/2020 - 7/19/2020

![alt text](https://github.com/tnesfield/NYC-Travel-During-Covid19/blob/master/subway.png)
![alt text](https://github.com/tnesfield/NYC-Travel-During-Covid19/blob/master/buses.png)
![alt text](https://github.com/tnesfield/NYC-Travel-During-Covid19/blob/master/bandt.png)

Comparing subway ridership to covid-19 cases, hospitilzations and deaths

![alt text](https://github.com/tnesfield/NYC-Travel-During-Covid19/blob/master/sub_covid.png)

### Null Hypothesis
H0-There is no statistical difference in Citi Bike ridership between 2019 and 2020 from January to June. 


![alt text](https://github.com/tnesfield/NYC-Travel-During-Covid19/blob/master/citibike_riders.png)

### In Conclusion

Performing a t-test on the Citi Bike riders between Jan - June of 2019 and 2020 with a critial value of .05. 
Here are my results:
* T-value = 2.0782
* P-value  =  .0428

Therefore, I reject the null hypthesis. There was a difference in ridership January - June for 2019 and 2020.
