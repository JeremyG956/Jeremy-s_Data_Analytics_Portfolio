# H1 Jeremy's_Data_Analytics_Portfolio
Olympic data analyzed, Fire fighters resources and schedules optimized, advanced SQL joins



things to note for good story telling on this:
Intro, problem statement, skills demonstrated, data sourcing, data transformation, data modeling, analysis and visualization, conclusion and recommendation.


Intro (Power BI concepts applied), DAX, Data modeling (Star Schema)

Start with a stock image.




# Intro



# Problem Statement



# Data Sourcing
.csv file, extracted into Power Bi.

Describe the columns and values etc.

# Data Transformations

![alt text](image.jpg)



![Inital Observation of the Data Given](nul_values_in_data.PNG)

## I noticed immediately upon loading the data that there was a significant amount of null values where the data was supposed to be. 

![Inital Observation of the Data Values Incorrect](character_where_numeric.PNG)
## While analyzing the data a bit more I noticed that values for the Priority column were supposed to be numeric (1-3) but were instead labeled as characters (N for Non-Emergency and E for Emergency) 

![Errors Loading Data](Errors_with_data.PNG)
## As expected, errors were seen when loading the data into PowerBi.


![Completed joined tables with holidays](complete_date_table_w_Holidays.PNG)
##Now holidays which is needed for understanding the morale can be analyzed.


![Schema of Transformed Data](tables_schema.png)
##I finally adjusted the dates by Creating a table that contained all the federal holidays and joining it to the data table. I then linked that to the date table to create a connection witha  cardinality of 1 to many as there can be many cases per day. Finally, the data could be properly formatted for analysis. 




How I changed the data. Screenshot of data modeling

Screenshot of visual and description




# Data Modeling
![alt text](image.jpg)





# Analysis



# Visualization

Publish powerBi
Take screenshots


# Conclusion


Thank you for reading! :-)


