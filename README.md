# Data-Modeling-with-Apache-Cassandra
Data Engineering Nanodegree, project 2.

## Project Introduction
The objective of this project is to create a NoSQL analytics database in Apache Cassandra for a fictional music streaming service called Sparkify. Sparkify's analytics team seeks to understand what, when and how users are playing songs on the company's music app. The analysts need an easy way to query and analyze the songplay data, which is currently stored in raw csv files on a local directory.

As the data engineer assigned to the project, I have implemented an ETL pipeline in python to pre-process the data using pandas. The database tables are modeled on the queries according to the principle of one table per query. I selected the primary and clustering keys for each table in order to ensure a unique identifier for each row.

## File Description
- **event_data** folder nested at the home of the project, where all needed data reside.
- **Project_1B_ Project_Template.ipynb** the code itself.

## Instructions
Simply run **Project_1B_ Project_Template.ipynb**
