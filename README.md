# Sparkify a Case Study of Data Modeling with Apache Cassandra

## Summary

This is project is intended to help Sparkify music startup to build a database in Apache Cassandra to query their data. Until now their dataresides in a directory of CSV files on user activity on the app.

The code in this repo are ETLs to tables of music by session, user session and played songg by user into a database.

## Instructions

1. Load user activity files to event_data.
2. Run `Project_1B_ Project_Template.ipynb` to extract, transform and load into Apache Cassandra.

## Repo structure

* `event_data`: Contains user activity from the app, which are CSV files. 
* `images`: images.
* `Project_1B_ Project_Template.ipynb`: Notebook with all the code to build the ETL process. It creates the following tables:
    - music_by_session
    - user_session
    - played_songs
