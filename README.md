# ENGR315-Final-Project-
Project Group 19: Alex Otti, Andrew Fricke, Josh Hostetter

1. Motivation and Dataset Overview

Area of interest and motivation: All three of us have interest in civil engineering, with two of us working in traffic and transportation. 

Dataset name and public download URL: Motor Vehicle Collisions – Crashes (NYC Open Data) https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes

Dataset origin and collection: (Who collected it, how and why it was collected, date range, number of observations, and file type/size.)
This was collected by the city of new york, and was a combination of all police reports filed from the city that resulted in an injury, a death, or damage over $1,000. This data set was published in 2021, and was updated on July 31, 2026. It can be downloaded as a CSV, JSON, or XML. The data set contains over 1,00,000 data points, going 2017. 

Relevant data: Data includes, the date the crashes occurred, the time the crash occurred, the zip, latitude, longitude, what street it was on and the cross street, number of people in the accident, number of injuries, number of fatalities, the contributing factor, the collision ID,  and the vehicle types. The data set is comprehensive, and allows us to answer a wide range of questions 

Selected Question 1: What 15 minute interval has the most crashes? (which produced the highest number of fatal accidents) 
Analysis method: Analyze each unique 15 minute period to determine which has the highest number of crashes.
Expected finding/inference: A data set that explains the specific period of time with the maximum number of crashes and the location it occurred in We expect the highest number of crashes to occur somewhere inside of rush hour. 

Figure 1 placeholder: Scatter plot of 15 minute intervals, with number of crashes on the x axis, and fatalities on the y axis, to display the most dangerous 15 minute period. 

Selected Question 2: What intersection produces the most crashes relative to average daily traffic 
Analysis method: indexing each unique intersection combination where crashes occur, and seeing which has the highest number of crashes. 
Expected finding/inference: We would expected the highest number of crashes to occur at an intersection where both roads have a high number of average daily traffic

Figure 2 placeholder: Heat map of new york, color coded to show each intersection, would provide a visual representation of each crash site

Selected Question 3: Top 5 most traveled boroughs that had the most fatal accidents involving cyclists? (deaths or injuries)
Analysis method:  Analyze each borough to determine the one with the most fatalities
Expected finding/inference: A graph comparing the name of the borough with the amount of fatal car crashes. 

Figure 3 placeholder: Two data plots expressing max and min number of fatal accidents versus borough location. The data set includes all the boroughs in the city and a column that records numbers of persons injured and killed. 

Sub task 4
Question 1: “What 15 minute interval has the most crashes? Which has the highest percentage of fatal crashes.  (which produced the highest number of fatal accidents)”
What metric might be calculated from that data that could help your analysis
Total amount of crashes per 15 minute interval, and number of crashes in that interval where fatal crashes > 0. Intervals may be collected by creating 1440 unique intervals, and sorting each crash into applicable bins, each crash should fit into 15 different bins, which will allow us to find the unique 15 minute interval with the most crashes
Potential fatal crash percentage, to represent especially dangerous intervals. 
If any additional python packages would be useful in analysis
Pandas, is useful for data analysis
Numpy potentially for processing data 
What type of plot or visualization would be helpful? 
A line plot with the start of the 15 minute interval on the x ,and the amount of crashes in on the y, we could have a second line below it representing fatal crashes as well. 
Question 2: “What intersection produces the most crashes relative to average daily traffic”
What metric might be calculated from that data that could help your analysis
Total number of crashes at each intersection
Average daily traffic, accounting for the amount of vehicles passing or approaching the intersection per day.
Number of crashes relative to traffic exposure
If any additional python packages would be useful in analysis
Scipy.stats, would be useful for analyzing data
Pandas 
What type of plot or visualization would be helpful? 
Geographic heat map to display crash sites across the city. 
Ranked bar chart, to compare the top 10 intersections by traffic rates
Question 3: “Top 5 most traveled boroughs that had the most fatal accidents involving cyclists? (deaths or injuries)”
What metric might be calculated from that data that could help your analysis
Amount of daily traffic between streets/boroughs
Number of cyclist involved accidents including fatalities or injuries
Percent of cyclists involved in accidents 
If any additional python packages would be useful in analysis
Pandas 
Scipy
Numpy
What type of plot or visualization would be helpful? 
Line graph showing cyclists deaths and injuries over a period of time in different locations 

RESULTS:

CONCLUSIONS : 

ACTIONS THAT NEED TO BE COMPLETED:

REFERENCES: 






