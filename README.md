# Bike Sharing with Citi Bike

## Overview of Project
This project analyzes Citi Bike bikesharing data and provides visualizations to understand the data. Screenshots shared below are available as an [interactive public presentation](https://public.tableau.com/app/profile/delia.davila/viz/CitiBikeAnalysis_dd/CitibikeAnalysis "interactive public presentation"), courtesy of Tableau.

### Purpose
This project was completed to help investors understand Citi Bike bikesharing. Data analysis was performed to determine that bike sharing would work for Des Moines, Iowa. 
### Background
Using available Citi Bike data for New York City, I analyzed aspects of the bike sharing business and identified customers and trends, to determine that yes, bike sharing makes sense for Des Moines. In the results sections below, I’ll review what was analyzed. Note: Use the link above to follow along with interactive data. 

## Results
The numbered sections below show reviewed data from multiple angles. Screenshots are provided here for convenience, but the interactive presentation provided linked above allows you to adjust filters.

### 1. Checkout Times for Users
 
![1_CheckoutUsers](https://github.com/DeliaDavila/bikesharing/blob/main/Images/1_CheckoutUsers.png)

As shown in the first graph, the vast majority of trips taken on Citi Bike bikes are under an hour. Hour zero has a huge spike in number of bikes that quickly tapers off for hours after the first hour (Hour zero in the graph). 
Let’s dive into more detail about the people who use Citi Bike.
### 2. Checkout Times by Gender
 
![2_CheckoutGender](https://github.com/DeliaDavila/bikesharing/blob/main/Images/2_CheckoutGender.png)

The second graph shows the breakdown by reported gender. The trip length between male and female looks similar, while the “unknown” gender seems to have more of a spread in how long the bikes were used. This indicates a different kind of rider, as we’ll see in later analysis.
### 3. Trips by Weekday per Hour
 
![3_TripsWkdayHr](https://github.com/DeliaDavila/bikesharing/blob/main/Images/3_TripsWkdayHr.png)
The third graph shows a distribution of ridership by weekday and by hour. It’s easy to see from this graph that there are two main types of riders, those who commute to work and those who rent the bikes on the weekends for fun. Since New York is a great town for tourism, it’s likely that many of the weekend riders are tourists.
### 4. Trips by Gender (Weekday/hr)
 
![4_TripsGender_Unknown](https://github.com/DeliaDavila/bikesharing/blob/main/Images/4_TripsGender_Unknown.png)

On the fourth graph, the previous graph is broken down by gender as well as weekday and hour. When the “unknown” gender is isolated, it’s easy to see that the ridership is heavily concentrated on the weekend afternoons. There is also a bit heavier use in the early evening hours, regardless of days. This supports the idea that the “unknown” gender actually represents tourists renting the bikes while visiting the city. 
### 5. User Trips by Gender by Weekday
 
![5_UserTripsGenderWkdy](https://github.com/DeliaDavila/bikesharing/blob/main/Images/5_UserTripsGenderWkdy.png)

In the fifth graph, we breakdown usage by three things: weekday, gender, and type of user. Subscribers pay a monthly fee to use bikes, where the “Customer” type pay per use. This make it clearer that there are really two riderships who use Citi Bike in New York City. Subscribers have accounts so the rider’s gender is known. These riders use bikes most heavily during the week to get to work. Customers, on the other hand, are more distributed across the graph. The heaviest bands are in the “unknown” gender and the weekend days. These are our tourists, who have a lot to see and rent bikes to get around the city during their vacations.
### 6. CustomerType
 
![6_UserType](https://github.com/DeliaDavila/bikesharing/blob/main/Images/6_UserType.png)

The good news for Des Moines Citi Bike is shown in the 6th graph. The customer base is overwhelmingly in the subscriber type. This indicates that there is a demand for regular use of the bikes for commuting and provides a base of operations to grow from. Weekend use by tourists can supplement the business but it’s not the main business, even in a tourist town like New York City. 
### 7. Trip Duration by Age/Type

![7_TripDurationByAgeType](https://github.com/DeliaDavila/bikesharing/blob/main/Images/7_TripDurationByAgeType.png)

Graph 7 delves into another aspect of the ridership, showing the average trip duration against the rider’s birth year. I added the user type as well. Here again, we see more evidence that the Citi Bike subscriber is a commuter. The trip duration is very consistent for subscribers, regardless of birth year. 

## Summary
### Findings
The data analysis shows that Citi Bike can be used by a city’s residents as well as visitors. Even in New York City, where tourism is one of the main industries, Citi Bike subscribers who regularly use the bikes to commute outnumber the tourists who pay per ride, even in a high tourism month like August. This is good news for Des Moines, because the bike sharing business will be attractive even to cities who aren’t major tourism hubs. Additionally, analysis found that subscribers across genders and ages rented bikes regularly.
 
### Recommendations
Additional analysis would help bring Citi Bike to Des Moines. The central New York area is very compact and multi-use, so many people live close enough to their jobs to commute via bike. Also, the upper limit of commute distance is determined by the geography of the area. To work towards translating this data to Des Moines features and attractions, further analysis on trip limits could be done on the New York data. Determining average trip distances would be helpful for getting an estimate of how far riders will go before turning to other methods. Additionally, looking at maximums and standard deviation, both in trip duration and distance, might help determine whether the average number is a good estimate or should be adjusted up or down.
Additionally, further analysis of the New York data could help determine determine what kind of use to expect throughout the year and over time. One suggested project is to plot the New York data against weather data on the same dates to determine at what point weather causes dips in ridership. Setting the context of ridership drops in terms of extreme temperatures or inclement weather and then comparing to Des Moines weather would help determine a base level of year-round ridership to prepare for.


