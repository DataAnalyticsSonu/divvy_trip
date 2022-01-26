# divvy_trip
------------

# Bike-Share Navigate Speedy Success
------------------------------------

## Scenario
===========

> Being a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
our team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
our team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve our recommendations, so they must be backed up with compelling data insights and professional data
visualizations.


## Ask_Phase
============

Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?


### In this analysis we will focus on the first question only : How do annual members and casual riders use Cyclistic bikes
differently?

We will produce a report with the following deliverables:

1. A clear statement of the business task
2. A description of all data sources used
3. Documentation of any cleaning or manipulation of data
4. A summary of our analysis
5. Supporting visualizations and key findings
6. Our top three recommendations based on your analysis


<ins>Case Study Roadmap - Ask</ins>

Guiding questions
-----------------

* What is the problem you are trying to solve?
> We like to understand if increasing the number of annual members is beneficial for the future of the company . So,we want to understand how casual riders and annual members use Cyclistic bikes differently .

* How can your insights drive business decisions?
>We will share the insights with the stakeholder with top recommendation which will help the team to design a new marketing strategy to convert casual riders into annual members.


Key tasks
---------

1. Identify the business task
2. Consider key stakeholders

Deliverable
-----------

A clear statement of the business task

## Prepare
==========

We will use Cyclistic’s historical trip data to analyze and identify trends.

For the purposes of this case study,the dataset is appropriate and will enable us to answer the business questions. 

Data provider : The [data](https://divvy-tripdata.s3.amazonaws.com/index.html) has been made available by Motivate International Inc. under [this
license](https://ride.divvybikes.com/data-license-agreement).This is public data that you can use to explore how different customer types are using Cyclistic bikes.

But note that data-privacy issues prohibit us from using riders’ personally identifiable information. Thismeans that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in theCyclistic service area or if they have purchased multiple single passes.

## Process
==========
1. Download the previous 1 month of Cyclistic trip data.
2. Unzip the files.
3. Create a folder on the desktop or Drive to house the files. Use appropriate file-naming conventions.
4. Open Excel and create a column called “ride_length.” Calculate the length of each ride by subtracting the column “started_at” from the column “ended_at” (for example, =D2-C2) and format as HH:MM:SS using Format > Cells >Time > 37:30:55.
5. Create a column called “day_of_week,” and calculate the day of the week that each ride started using the “WEEKDAY”command (for example, =WEEKDAY(C2,1)) in each file. Format as General or as a number with no decimals, noting that 1 = Sunday and 7 = Saturday.
6. Save the Processed data as data_processed.

## Analyze
==========
1. Open the data_preprocessed.csv from the previous Process Stage.
2. Make a copy of file and name it as data_analyze.csv
3. Where relevant, making columns consistent .
4. Clean and transform the data to prepare for analysis.
5. Conduct descriptive analysis.
6. Run a few calculations to get a better sense of the data layout. 
Options:
	* Calculate the mean of ride_length
	* Calculate the max ride_length
	* Calculate the mode of day_of_week
7. Create a pivot table to quickly calculate and visualize the data. 
Options:
	* Calculate the average ride_length for members and casual riders. 
	Try rows = member_casual; Values = Average of ride_length.
	* Calculate the average ride_length for users by day_of_week. 
	Try columns = day_of_week; Rows = member_casual; Values = Average of ride_length.
	* Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.

8. Save the file as data_analyized.csv .

## Share
==========

1. Creat appropriate visuals of our findings from the Analyze phase.
2. Share our findings as a PPT to the stakeholders along with the recommendation to take necessary business action.
