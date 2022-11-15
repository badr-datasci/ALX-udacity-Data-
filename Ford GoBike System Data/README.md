# Ford GoBike System Data Exploration
## by Badreddine Mouttaqui


## Dataset

> This dataset includes records of individual rides made in a bike-sharing system covering the greater San Francisco Bay area in Feb-2019. 

The features of the dataset after the preliminary wrangling :

        - duration_sec.
        - start_time.
        - end_time.
        - user_type : Subscriber & Customer.
        - member_birth_year.                
        - member_gender : Male, Female & Other                     

Besides, I created new columns from given columns:

        - age : derived from the member_birth_year
        - start_hour: to store hour number from start_time.
        - end_hour: to store hour number from end_time.
        - start_weekday: to store week day number from start_time.



## Summary of Findings

> ##### Main findings from the univariate  exploration :

- Most of trips took less than 30min a with a peak 10-12 minutes.
- Male users do more trips than female. 
- Most users age is ranging between 29 & 39 .
- Subscribers use bikes more than customers 
- Peak of use of bike is 8am and 17 for. These are rush hours.
- Trips were mostly took during workdays (Monday-Friday) more than week-end.

##### Main findings from the Bivariate  exploration :

- Customers trip durations are longer than the Subscribers to the system.
- Young adults take longer trips.
- Male users take shorter trips than female users.
- The trips are much shorter on Monday-Friday compared to weekends.

##### Main findings from the Multivariate  exploration : 

- Customers have a higher mean trip duration across all genders.
- The majority of Old users are Subscribers and they spend less time in the bike trips.
- Young Customers trip duration is slightly more than Young Subscribers.
- Subscribers take shorter trips compared to customers all week long. 
- Both user types have increase their trip duration over weekends. 
- Subscribers seems to have efficient use of bike than customers overall by being near the average especially from Monday to Friday.


## Key Insights for Presentation

> Insight 1:  Most of trips took less than 30min a with a peak 10-12 minutes

> Insight 2: Subscribers take shorter trips compared to customers all week long & use the bike system in an efficient way (being near the average from Monday-Friday). 
And both user types increase their trip duration over weekends. 

> Insight 3: Customers have a higher mean trip duration than subscribersacross all genders.

