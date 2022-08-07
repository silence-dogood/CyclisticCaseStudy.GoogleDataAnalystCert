# Table of Contents

1. Introduction
2. Business Task
3. Data
4. Processing and Cleaning
5. Analysis and Visualization
6. Conclusion and Recommendations


# Introduction
The project is a part of Google Data Analytics Certification course capstone. The scenario involves analysis of the trip data of Cyclistic bike share company.

The company has two models for availing service: individual passes which are called "casual" riders and annual subscriptions called "member" riders. The company operates in Chicago with around 6000 bicycles at 700 stations.

Maximizing the number of annual members will be key to future growth as it ensures financial sustainability and customer retention. The insights can help devise effective marketing strategies aimed to convert more casual riders into annual members.

# Business Task
How do annual members and casual riders use Cyclistic bikes differently ?

>Objective : To clean, analyze and visualize the data to observe how casual riders use the bike rentals differently from annual member riders.

# Data
* Data source : Public data from Motivate International Inc. (Divvy Bicycle Sharing Service from Chicago) under this license.
* Cyclistic’s historical trip data (2013 onwards) available in .csv format.
* Our date range : May 2020 to April 2021 (608 MB data)
* The dataset has individual ride records consisting of ride start-end date & time, station information, bike type, rider type (casual/member).
* Data uploaded to Microsoft SQL Server in order to import the large files.

# Processing and Cleaning
* Data imported from Excel into Microsoft SQL Server for manipulation and analysis using SQL.
* Visualizations to be developed in Tableau.
* Datatypes made consistent and then consolidated into one view using this query.
* To assist in analysis, 4 new columns were added (start point location, end point location, ride start day name and ride duration in seconds).
3,742,624 rows were returned but required cleaning.

## Cleaning process :
* Missing start and end station names found using this query.
* Other columns checked using this query.
* Negative and zero ride duration values found using this query.
* Following the cleaning and consolidating data in one table, 3,476,354 rows were returned for proceeding to analysis. All of this was achieved using this single master query. JOIN, WITH, UNION ALL, WHERE, subqueries and many other SQL functions were used here.
