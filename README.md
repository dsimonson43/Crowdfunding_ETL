# Crowdfunding_ETL
# This project was focused on creating an ETL pipline for csv data processing. It was extracted and transformed, then loaded into PostgreSQL. An ERD is included to visualize the relationships.

#program features
- extracts, transforms data from excel files
- creates an ERD and schema for the SQL database
- creates database tables in PostgreSQL

# how to install
1. clone repo
2. install pandas and other dependencies
3. setup a new SQL server (pgAdmin4 recommended) and name crowdfunding_db.

# how to use
1. run jupyter notebook in local repo file
2. use crowdfunding_db_schema.sql to create tables in postgreSQL
3. load the csv files into the corresponding tables
4. run queries on the database to verify correct placement

# programs used
- python w/ pandas vua jupyter notebook
- postgreSQL(pgAdmin4)
- excel .csv
