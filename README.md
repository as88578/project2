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
For this project we are utilizing a data set from the US Data Government website that list New York Police Department Shooting Incidents from 2006-2022. Within this data, the primary key is listed as INCIDENT_KEY and this gives an individual number for each of the incidents. The next column within the data set is OCCUR_DATE and the following one iS OCCUR_TIME, both of these are giving the date and time of when the incident occurred. There is a column titled BORO and it shows the New York Borough the shooting occurred in which is one of the following Bronx, Brooklyn, Manhattan, Queens, and Staten Island. There is a column titled PRECINCT which lists location information about the shooting for police purposes. There is a LOCATION_DESC column (location description) in order to add details so some of the shootings such as "Grocery store" or "Jewelry Store". Within the data there is a column that is titled STATISTICAL_MURDER_FLAG, the data for this column is either true or false and this is used to detemined if the shooting resulted in the victim's death which would be counted as a murder. After this column, there are 3 columns describing the perpetrator with their age group, their sex, and their race. Following with another 3 columns describing the victim's age group, sex, and race as well. The last columns are describing the coordinates of where the shooting incident took place. 

## Data Model Questions: 
### Question 1: 
Create a map showing the locations of each distinct shooting incident colored by borough that occured in New York City during the years 2019, 2020, and 2021. Also create a line graph for each of these years showing the number of shooting incident over the year colored by borough. 

<img width="1002" alt="Screenshot 2024-04-23 at 6 51 13 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/163003533/04ad038b-a2f2-49df-811e-3422cc1ea914">

From these visualizations we can see that during the summer months the amount of shootings increased through out almost all of the boroughs during all three years. However, during 2020 the amount of overall shooting incidents increased significantly during the summer months of June and July. This increase was most drastic in Brooklyn and the Bronx.

### Question 2: 
Create a graph to show the victims who survived vs the murdered victims depending on their races in Manhattan throughout 2019-2021.

<img width="1059" alt="Screenshot 2024-04-23 at 6 44 08 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/150160152/c9811574-c990-48a2-92b9-f53633dfa081">

We created 2 separate graphs of who survived and who did not based on their races and in both of these graphs, the black race was the highest amount of each. This graph gives us information about which race shot at more during these years and how many of the victims survived throughout these years in Manhattan.
## Manipulations to data:
Utilized a calculated field to change the Vic Sex from F and M to "Female" and "Male" to better distinguish on the visualization.

## Analysis and Results: 

## Date Source

Police Department (NYPD). (2024). NYPD Shooting Incident Data (Historic). NYC OpenData. https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data

