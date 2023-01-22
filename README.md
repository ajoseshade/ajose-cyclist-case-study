# cyclist-case-study
## Introduction
The Google Data Analytics Certification course on coursera includes capstone projects to complete.This is my first case study and I have chosen the Cyclist Dataset for this project. In order to answer the key business questions, I have followed these steps:
* Ask
* Prepare
* Process
* Analyze
* Share
* Act
## Project Description
## Scenerio
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve your recommendations, so they must be backed up with compelling data insights and professional data
visualizations.
## Question
 How do annual members and casual riders use Cyclist bikes differently?
 
In order to answer this question and for my analysis, I have chosen a twelve month period from September 2021 to August 2022.
This is the original [dataset](https://divvy-tripdata.s3.amazonaws.com/index.html) and [Licence](https://ride.divvybikes.com/data-license-agreement)

Tools I selected for data verification and cleaning are;
* PowerBI
* Excel
###### Initial assessment on the dataset in microsoft excel
* Inspected all 12 datasets to check if they were accurate and reliable
* Columns start_station_name, start_station_id, end_station_name, end_station_id had too many null values.
## Data Cleaning and Manipulation
Imported all dataset into Power BI and merged them.
* By using power query all these were performed to get the data ready for analysis
* Checked for duplicates and deleted all rows with the same ride_id
* Checked and removed all null values
* Trimmed all the columns to make sure there won't be issues with whitespaces.
* Adding a column ride_length, start_day_of_week, start_month, ride_length, and start_month_number which would be needed in the analysis.
* The average ride_length, maximum ride_length and mode of start_day_of_week are also found and are used in the analysis.

## Analysing the dataset
The data is now cleaned and ready for analysis.
# Number of rides versus Analysis of weekday
It is shown that annual members account for 59.02% of the number of rides taken.
![Count of ride ID](https://user-images.githubusercontent.com/68378328/213943922-dbb16444-e4f5-4073-bb44-12e550b25649.jpg)

# Analysis of Number of rides and Weekday
0 being Monday and 6 being Sunday

