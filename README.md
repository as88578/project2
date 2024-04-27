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
For this project we are utilizing a data set from the US Data Government website that list New York Police Department Shooting Incidents from 2006-2022. Within this data, the primary key is listed as INCIDENT_KEY and this gives an individual number for each of the incidents. The next column within the data set is OCCUR_DATE and the following one is OCCUR_TIME, both of these are giving the date and time of when the incident occurred. There is a column titled BORO and it shows the New York Borough the shooting occurred in which is one of the following Bronx, Brooklyn, Manhattan, Queens, and Staten Island. There is a column titled PRECINCT which lists location information about the shooting for police purposes. There is a LOCATION_DESC column (location description) in order to add details so some of the shootings such as "Grocery store" or "Jewelry Store". Within the data there is a column that is titled STATISTICAL_MURDER_FLAG, the data for this column is either true or false and this is used to determine if the shooting resulted in the victim's death which would be counted as a murder. After this column, there are 3 columns describing the perpetrator with their age group, their sex, and their race. Following with another 3 columns describing the victim's age group, sex, and race as well. The last columns are describing the coordinates of where the shooting incident took place. 

## Data Model Questions: 
### Question 1: 
Create a dashboard visualizing the age group, race, sex, and time of day of NYC shooting victims.

<img width="1000" alt="Screenshot 2024-04-25 at 6 19 30 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/163003533/11d30c41-4159-44c1-bcaa-d85e4e1579bb">

From these visualizations, we observed that shootings occur more frequently in NYC during the late night and early morning hours. We also observed that victims were predominantly male. In addition, there is a notable concentration of victims aged 25-44 among the Black community.  


### Question 2: 
Create a map showing the locations of each distinct shooting incident colored by bourough that occured in New York City during the years 2019, 2020, and 2021. Also create a line graph for each of these years showing the number of shooting incident over the year colored by borough. 

<img width="1002" alt="Screenshot 2024-04-23 at 6 51 13 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/163003533/04ad038b-a2f2-49df-811e-3422cc1ea914">

From these visualizations, we observed that during the summer months the amount of shootings increased through out almost all of the boroughs. However, during 2020 the amount of overall shooting incidents increased significantly during the summer months of June and July. This increase was most drastic in Brooklyn and the Bronx. 

## Manipulations to data:
Utilized a calculated field to change the Statistical Murdrer Flag from "True" and "False" to "Murdered" and "Survived" so they data could be understood more easily. 

## Analysis and Results: 
Our data gave us a lot of information about the risks and possibilities of there being a shooting throughout New York. In our first question, we were able to go more into depth about a certain person who is more likely to become a victim of a shooting. This data will become very useful to the public and police department in order to keep people safe and off the streets at a certain time that is more likely to become a shooting. Our second question gave us insight into the data throughout the different bouroughs in a 3 year period. This data gives us a visual map in order to better visualize which parts of


## Date Source

Police Department (NYPD). (2024). NYPD Shooting Incident Data (Historic). NYC OpenData. https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data

