# Data Modeling with Cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

Purpose of this project is to create an Apache Cassandra database which can be used to query song play data to answer Sparkify's questions.

## Project Overview

In this project, you'll apply what you've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, you will need to model your data by creating tables in Apache Cassandra to run queries. You are provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Details of Data Model and Queries

Details of data model/queries are explained in IPython notebook.

## Note:

Provided CSV files reading code was not working properly. So, I changed that to following line to get all 6000+ rows from all csvs.
```file_path_list = glob.glob(os.path.join(filepath, '*'))```

Please revert this code if this doesn't work on your machine.
