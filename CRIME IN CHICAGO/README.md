# EXPLORING CRIME IN CHICAGO (2001-2018)

## Dataset: Chicago Crime Data
This dataset reflects reported incidents of crime that occurred in the City of Chicago from 2001 to 2018. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. The dataset consists of 22 columns and over 7 million rows. The dataset provides us with rich information about the type of crime, location, law enforcement activity and time.

Data : [Chicago Crime Data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g) 

The intended audience are public safety officials, law enforcement organizations, and policymakers. 

## Initial Analysis Questions
We want to know what the data tells us about the crime patterns, so we focus on three main aspects of the crime.  
1. What are the most common crimes in Chicago?  
2. Analysis of Crimes by Time.  
3. Where do crimes occur in Chicago? Analysis on the Locations of crime?  

Chicago has been in the news a lot in the last few years for its Crime rate. So, let’s see if we can find some insights on “Arrests” in Chicago,
4. Interesting insights on Arrests in Chicago.  

## Discoveries & Insights
Our initial analysis of the data tells us about the number of crime records over the years, top common crimes and crimes per ward in Chicago city. 

![image](https://user-images.githubusercontent.com/20474402/55728078-49c07300-5a0b-11e9-8c07-1946bedaa898.png)  
This chart shows the count of records for each year from 2001 to 2018. We can see that the number of records has a decreasing trend over the years. Crimes have subsequently decreased in recent times. There are almost 80000 records less in 2018 than 2001.

![image](https://user-images.githubusercontent.com/20474402/55728162-75435d80-5a0b-11e9-80d3-5c4adf0cdbe7.png)  
Next, we look at the top 10 crimes in the city of Chicago. These are sorted by count of records . We see that Theft is the most prevalent, followed by Battery, Criminal Damage, Narcotics and so on. These top crimes do not vary much and are the same top crimes all the years. 

![image](https://user-images.githubusercontent.com/20474402/55728216-9015d200-5a0b-11e9-83ac-dd73e197146a.png)  
The above bar graph shows us crimes (Primary Type) according to the Wards. The ward is (City Council district) where the incident occurred. Here Ward 42 has the highest rate of crime with “Theft” being the most common crime. Second comes Ward 24 which has “Narcotics” & “Battery” as majority of crime type.


Next part of our analysis will tell us about time of the crime. Knowing where the crime occurs is half the battle, knowing at what time it happened is the other half. We summarize distribution of crime in Chicago through time.  
 
![image](https://user-images.githubusercontent.com/20474402/55728256-a754bf80-5a0b-11e9-87b5-721b27258901.png)   
In the above graph we have plotted number of records to Date. The date is formatted to hours so that we could get good insights on the time of crime. Crime is lowest around 4am-5am, then it starts to increase until 9pm, then there is a considerable increase in noon. 
Crime types are filtered to show only 20 types. The Police should adapt to the crime pattern changes.  

![image](https://user-images.githubusercontent.com/20474402/55728462-0581a280-5a0c-11e9-9979-a0c34c2357d8.png)  
The line graph plots number of records for each month from 2001-2018. This graph shows us an interesting pattern. We can see that for every year the records show us a cyclic pattern. It almost seems like crime rates are similar in month each year.   

![image](https://user-images.githubusercontent.com/20474402/55728510-19c59f80-5a0c-11e9-8a16-efcd48120918.png)  
The bar graph shows us the distribution of crimes over the weekdays and weekends. The graph suggests that Fridays and Wednesdays have the high crime occurrence rate. There is lowest occurrence of crime during the Sundays. 

The next part in analysis will be on the Location of the Crime. To fight crime and prevent it we need to know where it happens. We explore and locate critical areas of criminality in Chicago.  

![image](https://user-images.githubusercontent.com/20474402/55728562-2f3ac980-5a0c-11e9-89a2-a7ca310bf24a.png)  
From the above visualization, we can see a scatter plot map of Chicago for all geo-locations data per district. The districts are sorted in ascending order of the number of crimes. The southern districts of Chicago have the most number of crimes. We also see "null" district, for which we are missing data.

![image](https://user-images.githubusercontent.com/20474402/55728593-41b50300-5a0c-11e9-80e8-16eae259cb71.png)  
This horizontal bar graph shows us location of crimes. The y-axis gives us the description of locations of crime such as Street, School, Bar, Alley etc. We have filtered the top 15 location of the crime. It can be seen that majority of crime occurs in streets which is followed by Resident and apartments. 

![image](https://user-images.githubusercontent.com/20474402/55728616-4f6a8880-5a0c-11e9-94b3-331a41223eab.png)  
The above visualization is similar to the that of the district. In this bubble graph, the size of bubble (district) represents the number of crime records in the that district. 

Now we explore our final question about the arrests in Chicago. To address this question, we will visualize 
1)	If an Arrest is made or not for crimes in each year.
2)	Time of the arrest.
3)	Arrests per district.   
![image](https://user-images.githubusercontent.com/20474402/55728653-63ae8580-5a0c-11e9-9cf1-e37a34ae7e91.png)  
The above graph shows us if arrests were made or not for year 2000-2018. We can see that there is more False arrest than True arrests. The year 2004 had higher number of true arrests.

![image](https://user-images.githubusercontent.com/20474402/55728677-71fca180-5a0c-11e9-87f7-0319a822cbe6.png)   
The line graph shows us at what time the arrest was made. The False arrests are filtered out because our concern is, at what time the criminal is arrested for the crime? The graph shows us that highest numbers of arrests are made during 5pm-9pm, from there, it is a complete decline in arrest until 5am followed by steady increase until 12 noon. 

![image](https://user-images.githubusercontent.com/20474402/55728718-8b9de900-5a0c-11e9-81a8-c446177e4b53.png)  
The above graph shows us the Count of arrests (an arrest is made or not) in each district in Chicago. The districts are sorted in ascending order of count of arrest records. District 8 and 11 have the highest count of arrest. 



## Summary
The intended audience for this project is public safety officials, law enforcement organizations, policymakers and public of Chicago. What we learnt from this visualization,
1)	The most common crimes by type of crime. Exploring how these crimes contribute to the total criminality in the city.
2)	The distribution of crime through time. We found insights on time of crime and derived patterns that law enforcement officials can use to combat crime.
3)	Explore critical locations of criminality in Chicago. 

The decision makers and law enforcement officials can use these insights to make strategies to combat and prevent crime in Chicago.
