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

Tools I selected for this project are;
* PowerBI
* Excel
###### Initial assessment on the dataset in microsoft excel
* Inspected all 12 datasets to check if they were accurate and reliable and then noticed columns start_station_name, start_station_id, end_station_name, end_station_id had too many null values.
## Data Cleaning and Manipulation
After the assessment, the data was imported into Power BI and merged.

By using power query all these were performed to get the data ready for analysis;
* Checked for duplicates and deleted all rows with the same ride_id
* Checked and removed all null values
* Trimmed all the columns to make sure there won't be issues with whitespaces.
* Adding a column ride_length, start_day_of_week, start_month, ride_length, and start_month_number which would be needed in the analysis.
* The average ride_length, maximum ride_length and mode of start_day_of_week are also found and are used in the analysis.

The data is now cleaned and ready for analysis.

## Analysing the dataset

###### Number of rides versus Analysis of weekday

![Count of ride ID](https://user-images.githubusercontent.com/68378328/213943922-dbb16444-e4f5-4073-bb44-12e550b25649.jpg)

It is shown that annual members account for 59.02% and 40.98% for casual riders of the rides taken

###### Analysis of Number of rides and Weekday

![day of the week](https://user-images.githubusercontent.com/68378328/214164915-3cc639cf-818d-4f2d-af7a-4266f3885604.jpg)

This shows the rides taken in a week, 0 being Monday and 6 being Sunday. For both casual riders and members, the number of rides taken fluctuates as the week goes by from Monday and is at it's highest on Saturday.However, the number of rides taken by Casual riders are more on Saturday than that of Members and for the rest of the week, the number of rides taken by Casual riders are lower than that of Members.

###### Queried to check if Casual riders and Members prefer to ride in any specific month as compared to others


![Monthly analysis](https://user-images.githubusercontent.com/68378328/214172301-8e77c2c8-ed41-4af3-81ea-6ccfbf43f8d5.jpg)

Throughout the year, the number of rides taken by Casual riders is lower than that of Members. We can also see that for both Members and Casual riders, the number of rides taken fluctuates in the first four month, then in May it increases and reaches it's highest point in August and then declines for the rest of the year.
###### Checked to see if Casual riders or Members preferred any type of bike

![Rideable type#](https://user-images.githubusercontent.com/68378328/214173874-eb1a6914-7d01-4828-aaea-afa81888a215.jpg)

Both Casual riders and Members preferred the docked_bike and the least favourite was the electric_bike

###### The mean ride length

![Mean](https://user-images.githubusercontent.com/68378328/214175339-5730cc78-54c2-43f6-abed-b3ef3599db18.jpg)

The mean ride length for Casual riders is greater than that of Members
