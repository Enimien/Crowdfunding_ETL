# Crowdfunding_ETL
## Description
This project aims to understand the patterns and trends in crowdfunding campaigns, helping creators and backers make informed decisions
This project has the resources file, the crowdfunding_db_schema file,crowdfunding ERD file, the select statement and the ETLMini project.
Firstly  we started by creating,
Created the Category and Subcategory DataFrames
Created the Campaign DataFrame
Created the Contacts DataFrame
Created the Crowdfunding Database


Export the category DataFrame as category.csv and save it to your GitHub repository.

Extract and transform the crowdfunding.xlsx Excel data to create a subcategory DataFrame that has the following columns:

A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories

A "subcategory" column that contains only the subcategory titles

Also we Extract and transform the crowdfunding.xlsx Excel data to create a campaign DataFrame and Export the campaign DataFrame as campaign.csv

 Also we Imported the contacts.xlsx file into a DataFrame.
Iterate through the DataFrame, converting each row to a dictionary.
Iterate through each dictionary, doing the following:
Extract the dictionary values from the keys, add the values for each row to a new list.
Create a new DataFrame that contains the extracted data.
Split each "name" column value into a first and last name, and place each in a new column.
Clean and export the DataFrame as contacts.csv

For this part of the project we Created the Crowdfunding Database
Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBDLinks to an external site..

Use the information from the ERD to create a table schema for each CSV file.

We  specified the data types, primary keys, foreign keys, and other constraints.

Save the database schema as a Postgres file named crowdfunding_db_schema.sql

We Created a new Postgres database, named crowdfunding_db using the database schema, create the tables in the correct order to handle the foreign keys.

 Running a SELECT statement for each table just to verify the tables

Import each CSV file into its corresponding SQL table.

Verify that each table has the correct data by running a SELECT statement.