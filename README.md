# UdacityPostgresSparkify
First project in the udacity data engineering course

# Project Information

## Project: Data Modeling with Postgres
## Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis, and bring you on the project. Your role is to create a database schema and ETL pipeline for this analysis. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.
## Project Description

In this project, you'll apply what you've learned on data modeling with Postgres and build an ETL pipeline using Python. To complete the project, you will need to define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.

## What I actually did

I implemented an ETL (Extract Transform Load) pipeline with the knowledge I learnt in the first lessons of the Udacity Course, used of a jupyter notebook to write code extracting JSON files and properly placing them in a postgres database, through SQL queries utilizing of a star schema. I then transferred the content of the jupyter notebook to a .py script.

# Files in this project and what they actually do
- etl.ipynb: Jupyter notebook used to implement the pipeline
- etl.py: converted jupyter notebook into ETL pipeline python script
- sql_queries.py: queries in sql used to power the pipeline
- test.ipynb: test file to check if the pipeline was properly implemented in postgres
- create_tables.py: creates tables in postgres through psycopg2
