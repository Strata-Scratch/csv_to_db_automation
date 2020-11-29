# CSV File to Database Import Automation
A python script that automates CSV file imports to a postgres database

By: Nate from StrataScratch (nate@stratascratch.com)

Dec 3, 2020
___

## Video Links
Here are the video tutorials showing you how to build the entire python script
- [Part 1: Building the Functionality](https://youtu.be/wqBFgaMgFQA)
- [Part 2: Automating the Script](https://youtu.be/TDwy1lSjEZo)
- [Part 3: Reusing & Scaling the Functions By Applying Software Development Fundamentals](https://youtu.be/TDwy1lSjEZo)

Follow my [Youtube channel here](https://www.youtube.com/channel/UCW8Ews7tdKKkBT6GdtQaXvQ) for more data science resources. We cover a lot of coding techniques in both python and SQL.

## Description

This script will automatically import CSV files to your postgres database. Just place the CSV files in the same directory as the notebook and run the notebook. The notebook will automatically clean the file name and column headers, create the db table, and copy the file over to the database. The table names are the same names as the file names. However, all upper case characters are changed to lower case, spaces are converted to underscores, and all symbols are removed. 

Importing CSV files to a database is a common task needed for data science and analytics and it can be done completely with python using pandas dataframes, numpy, os library, and the posgres database wrapper psycopg2.

## Other Data Science Resources
If you want more coding practice, whether to improve in analytics or to prepare for coding interviews, check out [StrataScratch](https://platform.stratascratch.com/), It's a coding platform with over 500+ coding questions from real data science companies. All questions are free and you can execute SQL and python code in the IDE.
