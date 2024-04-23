# Team 4 MIST 4610 Group Project 2

## Team Name:
47114 Group 4

## Team Members: 
1. Morgan Busbee [@morgan-busbee](https://github.com/Morgan-Busbee)
2. Corbin Gay [@corbinGay](https://github.com/CorbinGay)
3. Carson Harris [@clh15315](https://github.com/clh15315)
4. Ashley Seelochan [@as88578](https://github.com/as88578)
5. Hank Stocke [@hstocke1](https://github.com/hstocke1)
6. Katie White [@katiewhite29](https://github.com/katiewhite29)

## Problem Description:
We have found a data set that gives us information from the NYPD Shooting Incidents from 2006-2022. This data set has been found from the US Data Gov website. Within this data, the primary key is listed as INCIDENT_KEY and this gives an individual number for each of the incidents. The next column within the data set is OCCUR_DATE and the following one iS OCCUR_TIME, both of these are giving the date and time of when the incident occurred. Next, the column is BORO which shows the NY Borough in which the shooting happened, for example, "Manhattan, Brooklyn, ...". There is also a column for PRECINCT which also gives exact location information about the shooting. There is a LOCATION_DESC column (location description) in order to add details so some of the shootings such as "Grocery store" or "Jewelry Store". Within the data there is a column that is called STATISTICAL_MURDER_FLAG, the data for this column is all true or false and this means that if the shooting was considered a murder or not. After this column, there are 3 columns describing the Perpetrator with their age group, their sex, and their race. Following with 3 columns describing the Victims age group, sex, and race as well. The last columns are describing the Coordinates of where they believe that the shooting took place. 

## Data Model Questions: 
### Question 1: 
Create a map showing the locations throughout the bouroughs of New York during the years 2019, 2020, and 2021. Explain why you think 2020 had an effect on the data.

<img width="1002" alt="Screenshot 2024-04-23 at 6 51 13 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/163003533/04ad038b-a2f2-49df-811e-3422cc1ea914">



During the year 2020, the amount of shootings throughout all of the bouroughs increased. We noticed that the spike in Brooklyn shootings increased the most. Especially throughout July, we can see that that is the month that caused the biggest increase in number of shootings. This data gives us more information about the months during COVID and we can see that during these months and through our graph which the safest bouroughs are throughout New York. We also believed that since the data spiked during the month of July, this is correlated to the civil movements throughout the country at this time. 

### Question 2: 
Create a graph to show the victims who survived vs the murdered victims depending on their races in Manhattan throughout 2019-2021.

<img width="1059" alt="Screenshot 2024-04-23 at 6 44 08 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/150160152/c9811574-c990-48a2-92b9-f53633dfa081">

We created 2 separate graphs of who survived and who did not based on their races and in both of these graphs, the black race was the highest amount of each. This graph gives us information about which race shot at more during these years and how many of the victims survived throughout these years in Manhattan.
## Manipulations to data:
Utilized a calculated field to change the Statistical Murdrer Flag from "True" and "False" to "Murdered" and "Survived" so they data could be understood more easily. 

## Analysis and Results: 

