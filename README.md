# Netflix-Data
## Project Overview

This project focuses on performing data analysis and insight extraction from a Netflix Dataset using Apache Hive.
The primary goal is to utilize Hive’s SQL-like querying capabilities to analyze key trends such as content type distribution, genre popularity, release year trends, and country-based content insights.
The project demonstrates how to manage and query structured entertainment data on a Big Data platform (Cloudera/Hadoop) using HiveQL for large-scale analytics and business decision-making.

## Dataset Description

The dataset, netflix_cleaned.csv, contains detailed information about movies and TV shows available on Netflix, including:

Show ID

Type (Movie/TV Show)

Title

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Listed In (Genre/Category)

Description

## Objectives

##The key objectives of this project are:

To import and store the Netflix dataset into Hive tables efficiently.

To perform analytical queries on Netflix content trends.

To extract meaningful insights such as:

Number of movies vs TV shows.

Most popular genres.

Country-wise distribution of Netflix content.

Year-wise addition of new titles.

Top directors and actors with most titles.

## Technologies Used

Apache Hive

Hadoop (Cloudera Environment)

HiveQL (SQL-like Queries)

CSV File Data Ingestion

HDFS Storage

## Steps Performed

Created a database and Hive table schema for the Netflix dataset.

Loaded the CSV data from local storage or HDFS into the Hive table.

Executed multiple Hive queries to analyze Netflix content:

SELECT COUNT(*) → Total number of titles.

GROUP BY type → Distribution of Movies vs TV Shows.

GROUP BY country → Country-wise content analysis.

GROUP BY listed_in → Popular genres and categories.

ORDER BY release_year DESC → Recent content trends.

Generated analytical reports summarizing Netflix content insights.

## Key Insights

Identified the ratio of Movies to TV Shows on Netflix.

Found top countries contributing the most Netflix titles.

Discovered the most common genres across global audiences.

Highlighted most frequent directors and actors appearing on Netflix.

Observed trends in content release over different years.

## Conclusion

This project demonstrates how Apache Hive can be effectively used for large-scale data analysis on streaming platform datasets.
By leveraging Hive’s SQL-like capabilities on the Hadoop ecosystem, analysts can extract content insights, audience trends, and strategic recommendations that help in understanding global entertainment patterns and content planning for streaming services like Netflix.
