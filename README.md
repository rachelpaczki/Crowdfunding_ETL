# Crowdfunding ETL Project

## Overview
This project involved the extraction, transformation, and loading (ETL) of crowdfunding data using Python, Pandas, SQL, and QuickDBD. The goal was to perform a comprehensive analysis of crowdfunding data and create a relational database to store the information.

## Project Specifications
1. **Create the Category and Subcategory DataFrames**
   - Extract and transform the crowdfunding data from an Excel file to create separate DataFrames for categories and subcategories.
   - Export the DataFrames to CSV files and save them to the GitHub repository.

2. **Create the Campaign DataFrame**
   - Extract and transform the crowdfunding data to create a DataFrame for campaign information.
   - Rename and convert columns, handle datetime formats, and match category and subcategory IDs.
   - Export the DataFrame to a CSV file and save it to the GitHub repository.

3. **Create the Contacts DataFrame**
   - Extract and transform contact information from an Excel file using either Python dictionary methods or regular expressions.
   - Split and clean the data, then export it to a CSV file and save it to the GitHub repository.

4. **Create the Crowdfunding Database**
   - Design an entity-relationship diagram (ERD) using QuickDBD to visualize the database structure.
   - Create a table schema for each CSV file, specifying data types, primary keys, foreign keys, and constraints.
   - Save the database schema as a Postgres file and create the crowdfunding_db database.
   - Create the tables in the correct order, import CSV data into each table, and verify the data integrity.

## Contributors
- Lauren Ables-Torres
- Rachel Puzycki
- Rachel Taylor

This README provides detailed information about the Crowdfunding ETL project, including its objectives, specifications, and contributors.
