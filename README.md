Database Purpose and Goals

The purpose of this database is to pull in data from two different sources, clean it and prepare it for analysis. 


Justification

I have created a fact table called songplays which summarises all the most important information. 

There a number of dimension tables that connect to this. This load the key information into the songplays table.

File Explanation

The following files are used in the database
-data files (these contain both the song and log data)
-sql_queries.py - This contains the code that is used for creating tables in the next file as well as the command to pull out song names, artist name and duration
-create_tables.py - this is used to actually create the tables
-etl.py - This is used to extract, transform and then loading the data.
-test.ipynb - This is used to test that our code has worked correctly
-etl.ipynb - This is used to create the etl by checking out code

How to run the script

Simply update your dbname, user and password if necessary then first run the create_tables.py then the etl.py