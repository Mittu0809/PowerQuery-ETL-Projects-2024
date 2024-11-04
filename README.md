# PowerQuery-ETL-Projects-2024
This repository showcases Power Query projects demonstrating ETL workflows in Excel, including data extraction from web and local sources, cleaning Olympic medal data, and transforming staff information into dynamic, refreshable models. Each project highlights best practices in data transformation and management for effective analysis.


This repository contains two distinct Power Query projects that involve data extraction, transformation, and loading (ETL) processes. The first project connects to a Wikipedia page on the 2020 Summer Olympics Medal table, and the second project focuses on cleaning HR data from a local Excel file. Each project demonstrates essential Power Query techniques for dynamic data cleaning and transformation to prepare data for analysis in Excel.

Project 1: 2020 Summer Olympics Medals Data

Project Overview : 
This project connects to a Wikipedia page containing the 2020 Summer Olympics Medal table and imports the data into Power Query. The goal is to clean and transform the data, then load it into Excel in a structured format.

Source: https://en.wikipedia.org/wiki/2020_Summer_Olympics_medal_table

Goal: Extract, clean, and structure the data for analysis. 

Key Steps : 

1. Extract: Connect to the Wikipedia URL and load data into Power Query.
2. Data Cleaning:
Set headers, rename columns, and fix errors such as removing unnecessary characters (e.g., asterisks in country names).
Fill missing ranks where countries share the same rank.
3. Transformation:
Calculate the percentage of gold medals in total medals for each country.
Filter out unnecessary rows, like the "Total" row.
4. Load: Load the transformed data into Excel as a refreshable table that dynamically updates from the live Wikipedia page.
   
Features : 
- Dynamic Data Refresh: Refresh the table in Excel to pull the latest updates from Wikipedia.
- Automated Data Processing: Each step in Power Query is documented, ensuring reproducibility and data accuracy.

  
Project 2: Sample Staff Data Cleaning and Transformation

Project Overview : 
This project connects to a sample HR data file in Excel to clean and standardize the information for analysis. The data includes columns for employee names, departments, salaries, and start dates, which are transformed to create a clear, usable dataset.

Source: Local Excel file containing sample staff data.

Goal: Clean and standardize HR data, creating additional fields to support analysis.

Key Steps : 

1. Extract: Connect to the sample staff data file from a local directory.
2. Data Cleaning:
Trim extra spaces, replace null values in the Gender column with "Missing," and correct erroneous department values.
Remove irrelevant rows based on salary information, and fix inconsistent formats in the Start Date column.
3. Transformation:
Split names into first and last names and create a conditional salary bucket column.
Calculate employee tenure based on the start date and categorize work types based on FTE.
4. Load: Load the cleaned data into an Excel table with dynamic refresh capabilities.
   
Features 

- Data Standardization: Ensures consistent formatting for improved analysis and filtering.
- Custom Calculations: Adds calculated fields like Salary Bucket and Tenure to enrich HR insights.
- Dynamic Refresh: Data in Excel reflects any changes made to the source file.

Technologies Used : 

- Power Query
- Excel
- Data Cleaning Techniques

How to Use : 
Clone the repository and open each project file in Excel.
Follow the detailed steps within each project’s Power Query editor to understand the transformations.
Use the Refresh option in Excel to dynamically update the data as the source changes.







