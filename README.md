# Movie Industry Performance & Profitability Analysis
Interactive Power BI Dashboard Project

Project Overview

This project presents an end-to-end data analysis of a movie dataset, starting with data cleaning in Microsoft Excel (Power Query) and progressing to advanced visualization in Power BI.
The raw dataset contained missing values, duplicate values and inconsistent format. Using Excel Power Query, the data was cleaned, standardized, and transformed to ensure accuracy and reliability before importing it into Power BI for modeling and analysis.

After cleaning, the dataset was used to build an interactive dashboard that analyzes:

Movie profitability.

Revenue and budget trends.

Genre performance

Director impact on financial success

IMDb rating distribution


This project demonstrates practical skills in:

Data Cleaning using Excel Power Query

Data Transformation & Standardization

Data Modeling in Power BI

DAX Calculations

Business-Oriented Data Visualization


Data Preparation (Power Query)

The dataset was cleaned and transformed using Power Query:

Create a index column named Movie_id

Removed duplicate records using Movie_id

Handled missing values in budget, gross, and IMDb score

Corrected data types (Year, Decimal, Whole Number)

Add custom column named Profit

Add conditional column named Profitability

Rearrange the columns into correct order 

This ensured accurate reporting and reliable insights.
Data Modeling & DAX Measures

Created calculated measures including:

DAX:

Total Movies = COUNT(Movie[Movie_id])

Total Gross = SUM(Movie[gross])

Total Budget = SUM(Movie[budget])

Total Profit = SUM(Movie[Profit])

Avg IMDb Score = AVERAGE(Movie[imdb_score])

Avg cast likes = AVERAGE(Movie[cast_likes])

