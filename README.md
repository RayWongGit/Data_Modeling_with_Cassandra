# Project: Data Modeling with Apache Cassandra
## Introduction
Sparkify is a startup who have just launched a new music streaming app. They wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. 

The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like us to create an Apache Cassandra database which can create queries on song play data to answer the questions. Our role is to create a database for this analysis. 
## Dataset

For this project, we'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

- event_data/2018-11-08-events.csv
- event_data/2018-11-09-events.csv

## Project Steps
Below are steps we will follow to complete each component of this project.

1. Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
- Develop CREATE statement for each of the tables to address each question
- Load the data with INSERT statement for each of the tables
-  Write SELECT statement to do queries foreach question

