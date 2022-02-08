# Project: Communicate Data Findings [Fifa GoBike System Data]

## By: Kamel Mohamed
### Dataset Description 

> Fifa GoBike System Data includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

> The dataset consists of 183412 rows and 16 columns --> 2 columns converted from string to datetime, 9 numerical columns and 5 object(string) columns.

> The dataset after cleaning and adding some feature engineering became 174952 rows and 21 columns.

### Most Used columns:
 - duration_sec.
 - start_time (After Filtration and turned into weekday and day and hour).
 - member_birth_year(Used as age).
 - member_gender.
 - user_tyep.
 
### Conclusions:
 - The duration vary from 100 to 5000 sec but it has a high peak at 500.
 - The Age vary from 15 to 80 and has a high peak at 35.
 - Most of the users are males and there is a few females and few other types.
 - Most of the users are subscribers not customers.
 - Weekend days has the least rides.
 - 8 A.M and 5 P.M (17) has the most rides.
 - There are no relation between the monthdays and the number of rides.
 - Most of rides start and end in different stations.
 - Customers do longer trips than subscribers.
 - Females - in general - do longer trips than males and others.
 - Older males do longer trips than females and others.