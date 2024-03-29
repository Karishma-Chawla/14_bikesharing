# Overview
The purpose of the current analysis is to prepare visualizations representing metrics on the bike-sharing business model in NYC to facilitate investment decision. 

<img width="645" alt="bikeshare" src="https://user-images.githubusercontent.com/98617082/186014269-aef6deb4-9cfc-4161-a582-43513d3e0ba1.png">

The bike share data from New York City is visualized using Tableau to present the data to the investors. The key questions being answered in this analysis are:
•	Show the length of time that bikes are checked out for all riders and genders
•	Show the number of bike trips for all riders and genders for each hour of each day of the week
•	Show the number of bike trips for each type of user and gender for each day of the week.

# Data

CSV file containing data on trip duration, start and end time, information on start and end station,bike id, and User information, 

Source:https://ride.citibikenyc.com/system-data; 
Size: 450 MB
![image](https://user-images.githubusercontent.com/98617082/186013052-e814cb79-e1a0-40d5-ada1-67fc39c5b8a2.png)



# Results
Link to Story Board : https://public.tableau.com/app/profile/karishma2980/viz/StoryBoard_16547215770930/StoryBoard
##  Hourly wise Usage during week
Link https://public.tableau.com/app/profile/karishma2980/viz/TripsbyWeekdayperhour_16547134810700/TripsbyWeekdayperhour

![image](https://user-images.githubusercontent.com/98617082/172862918-e0d03bc4-e4fd-4d49-b096-26e1f7ed038f.png)


Analysing use of bikes start time and stop time by day of the week shows that the start time has two peaks times - in morning and evening office commuting hours during the week days .For weekends, late mornings to evenings are busy. 

##  Gender wise Hourly Usage 
Link https://public.tableau.com/app/profile/karishma2980/viz/TripsbyGenderWeekdayperHour_16547143957610/TripsbyGenderWeekdayperHour
![image](https://user-images.githubusercontent.com/98617082/172863150-33ae52b0-c26d-4abb-9ff9-edc3f39edaf1.png)


 

This visualization shows gender wise breakup of bike use during week days. Male users have higher usage of the bikes and their usage is skewed towards the end of the week, Thursday through Saturday than early week days. Female users use the bike lesser but their usage is more evenly spread out across the week.

## Subscribers and customers.
Link https://public.tableau.com/app/profile/karishma2980/viz/UserTripsbyGenderbyWeekday_16547139911690/UserTripsbyGenderbyWeekday

![image](https://user-images.githubusercontent.com/98617082/172863248-78919a7c-6051-42b5-bbe8-1bbac5a5359c.png)


This figure looked at the split of usage between subscribers and customers. Male subscribers are utilizing the bike share most whereas usage amongst customers are spread evenly between Male, female and unknown categories. more during commuting hours where customers are opting to utilize the bike share more during weekends and non-peak commuting hours.




## Checkout time for users
 Link https://public.tableau.com/app/profile/karishma2980/viz/CheckoutTimesforUsers_16547133908210/CheckoutTimeforUsers
 ![image](https://user-images.githubusercontent.com/98617082/172863309-23bd32a3-4bac-488e-ac19-28c5175a7718.png)


This image shows how long of a trip the user rode for. This shows that most frequent trip duration for the bike was less than an hour. 

## Gender wise split of Check out time for users
Link https://public.tableau.com/app/profile/karishma2980/viz/CheckoutTimebyGender_16547134333540/CheckoutTimebyGender

![image](https://user-images.githubusercontent.com/98617082/172863690-b13ab088-8587-4c17-8060-48c9ace03389.png)



 
This image shows how long of a trip the user rode for by each gender. While the most frequent trip duration for the bike was less than an hour for each gender, overall Males were the dominant category of bikes renters. 

## Gender wise users
Link : https://public.tableau.com/app/profile/karishma2980/viz/CustomerType_16547223949510/StoryBoard

 ![image](https://user-images.githubusercontent.com/98617082/172863498-f41286a8-2a39-4649-bea5-5366078a616b.png)


There is a much higher number of male bike share users, than female users. Even if we include users as female, it would still not be equal to male users.


## Usage in August
Link : https://public.tableau.com/app/profile/karishma2980/viz/PeakRidingHours/StoryBoard
![image](https://user-images.githubusercontent.com/98617082/172863629-11b2cc8d-6cd1-4156-8db8-0c0673962891.png)

When looking at the breakdown of peak hours that the bikes are utilized, commuting hours seem to have the highest number of rides. 

# Summary
Overall we can summarize that the majority users were Males who used bileshares for commute to work. On weekends, bikes must be used for recreational purposes and had no gender skew.   
Two additional suggested visualization would  be:
1.	Age wise analysis of the users. Use of calculated fied to categorize users in age buckets and then draw a pie chart to see the understand the age-group in which the maximum users fell.
2.	Bar chart to that shows the count of bikes fr each station to depict the most popular stations.
