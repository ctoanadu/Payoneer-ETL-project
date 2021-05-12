# Payoneer-ETL-project
Data / Analytics Engineer Homework Exercise: Design a suitable data schema for storing log lines from Nginx and store it in a postgresql database.

## Project Description
 In this project, I will be designing a data model from the web log provided and build an ETL pipeline using Python. To complete the project, you will need to manipulate the log file to look like a table that can be stored in a database, this manipulation was done with pandas. The ETL pipeline that stores the panda dataframe into postgresql was done with the help of sqlAchemy Library.
 
## Project File
1. etl.ipynb-Thisfileextractsthedata,manipulateitandstoreinthe postgresql database.
2. test.ipynb-Thisfilewasusedtocheckthedatabaseconnectedandalso check if the tables were created and data inserted in tables. This also provides solution for the sql query that was required for this assignment (Write a small script / tool that, when run, will query the database and print a count of all requests grouped by status code).
3. READme-Documentationoftheproject.

## How to run the project
1. Install postgresql, Jupyter notebook, pandas, SqlAchemy
2. Run etl.ipynb in jupyter notebook and execute each line of code one after the other.
3. Run test.ipynb in jupyter notebook to check if the data was stored in the database. Also to display the results for the query.
## Note : The etl.ipynb and test.ipynb should be executed on a jupyter notebook.
