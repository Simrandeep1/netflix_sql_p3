# netflix_sql_p3
This project analyzes Netflix movies and TV shows data using SQL. The main goal is to find useful insights and answer real-world business questions from the dataset.
It includes writing SQL queries to explore the data, solve problems, and understand trends in content, such as types of shows, release patterns, and other key details.
Overall, the project shows how SQL can be used to analyze data and support better decision-making.

Objectives
1)Analyze the number of Movies and TV Shows on Netflix.
2)Find the most common ratings for Movies and TV Shows.
3)Explore content by release year, country, and duration.
4)Categorize content using different conditions and keywords.

Dataset
https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download

Database Schema
This project uses a Netflix dataset stored in a SQL Server database.
The netflix table contains information about Movies and TV Shows available on Netflix, including title, director, cast, country, release year, rating, duration, genre, and description.

Main Steps Performed:
Created the netflix table with all required columns. 
Imported data from the netflix_titles dataset into the new table. 
Performed basic data exploration using SQL queries. 
Checked total content count and different content types. 
Removed unnecessary tables after data import. 
Table Includes Information Such As:
Show ID
Content Type (Movie or TV Show)
Title
Director and Cast
Country
Release Year
Rating
Duration
Genre (listed_in)
Description


Business Problems & Analysis
This project solves 15 business problems using the Netflix dataset in SQL Server.

Analysis Included
Counted the number of Movies and TV Shows.
Found the most common ratings for Movies and TV Shows.
Listed all movies released in a specific year.
Identified the top 5 countries with the most Netflix content.
Found the longest movie on Netflix.
Retrieved content added in the last 5 years.
Found Movies and TV Shows directed by Rajiv Chilaka.
Listed TV Shows with more than 5 seasons.
Counted content items in each genre.
Analyzed yearly Netflix content released in India.
Listed all documentary movies.
Found content without a director name.
Counted Salman Khan movies released in the last 10 years.
Identified the top 10 actors appearing in Indian movies.
Categorized content as Good or Bad based on keywords like “kill” and “violence” in descriptions.

SQL Concepts Used
CTEs (Common Table Expressions)
Aggregate Functions
GROUP BY and ORDER BY
String Functions
CASE Statements
Window Functions
Date Functions
Filtering and Data Analysis Queries


Project Summary:
Content Distribution: The dataset includes different types of Movies and TV Shows with various ratings and genres.
Common Ratings: The most common ratings help to understand the target audience of Netflix content.
Geographical Insights: The top countries and yearly content releases from India show how content is distributed across different regions.
Content Categorization: Categorizing content using keywords helps identify the type and nature of content available on Netflix.
