# H1 Jeremy's_Data_Analytics_Portfolio
Olympic data analyzed, Fire fighters resources and schedules optimized, advanced SQL joins



things to note for good story telling on this:
Intro, problem statement, skills demonstrated, data sourcing, data transformation, data modeling, analysis and visualization, conclusion and recommendation.


Intro (Power BI concepts applied), DAX, Data modeling (Star Schema)

Start with a stock image.




# Intro
This is an individual Final Exam project I was assigned in my Data Visualization course. In this scenario, I represented a consulting company where I was able to work with real data from a fire department. In this scenario, we met with a Fire Department chief. He had a few things he wanted me to keep in mind during the meeting. He wanted to improve morale within the organization. The nature of a firefighter shift is 24 on, 24 off where a minimum of 4 people work a shift. Some people felt overworked because they were working too many holidays. Balance the workload. He also stated they were not allocating resources by data-driven decision-making but instead by a gut feeling. Use the data to drive data driver resource allocation. Finally, he explained training must be held every year and schedule the training during the slow seasons throughout the year. 

# Problem Statement



# Data Sourcing
.csv file, extracted into Power Bi.

Describe the columns and values etc.

# Data Transformations

![alt text](image.jpg)



![Inital Observation of the Data Given](nul_values_in_data.PNG)

### I noticed immediately upon loading the data that there was a significant amount of null values where the data was supposed to be. 

![Inital Observation of the Data Values Incorrect](character_where_numeric.PNG)
## While analyzing the data a bit more I noticed that values for the Priority column were supposed to be numeric (1-3) but were instead labeled as characters (N for Non-Emergency and E for Emergency) 

![Errors Loading Data](Errors_with_data.PNG)
### As expected, errors were seen when loading the data into PowerBi.


![Completed joined tables with holidays](complete_date_table_w_Holidays.PNG)
### Now holidays which is needed for understanding the morale can be analyzed.






How I changed the data. Screenshot of data modeling

Screenshot of visual and description




# Data Modeling 
![Schema of Transformed Data](tables_schema.png)
##I finally adjusted the dates by Creating a table that contained all the federal holidays and joining it to the data table. I then linked that to the date table to create a connection with a cardinality of 1 to many as there can be many cases per day. Finally, the data could be properly formatted for analysis.



# Analysis
![Interesting trend](interesting_trend.PNG)
I noticed some interesting trends at first glance. Here The dashboard conveys an increase in call volume, but a  steep drop off in the "other" category and an increase in Fire, and Code 2 transport. Suggesting reporting standards increased between 2013-2014. You expect with call volume going up all types of calls would go up.


# Visualization

Publish powerBi
Take screenshots


# Conclusion


Thank you for reading! :-)


