# Motor Vehicle Dataset Management Project

## Overview

This repository houses a project that involves a comprehensive approach to managing datasets obtained from the International Organization of Motor Vehicle Manufacturers (OICA). The workflow is characterized by a meticulous process, encompassing various steps such as data loading, refining nomenclature, restructuring the data format, converting temporal variables to numeric, excluding non-country entries, rearranging rows for coherence, preserving the cleaned dataset, and culminating in the visualization of the refined data.

## Project Steps

### 1. Loading the Data
   - Loaded data from an Excel file using the `read_excel` function.

### 2. Cleaning the Names
   - Cleaned column names using the `janitor` package, ensuring consistency and clarity.
   - Renamed columns, including the conversion of non-numeric data types to numeric.
   - Addressed missing values in columns.

### 3. Reshaping the Data
   - Used the `pivot_longer` function to transform the dataset into a long format, focusing on columns related to sales for each year.
   - Selected relevant columns (country, year, and sale) for further analysis.

### 4. Converting Year to a Number
   - Separated the year from the column name and converted it to a numeric format for better analysis.

### 5. Dropping Rows That Aren't Countries
   - Removed rows corresponding to regions and entities that are not individual countries.

### 6. Rearranging the Rows
   - Arranged the dataset by country and year for better organization and readability.

### 7. Saving the Cleaned File
   - Saved the cleaned dataset as a CSV file for future use.

## Summary Visualization
   - Generated a summary visualization using the `ggplot2` package to showcase passenger car sales trends over the years for China, the United States of America, and other countries.

This project enhances the usability of the passenger car sales data by ensuring data cleanliness, organization, and visualization, providing a solid foundation for further analysis and insights.





#### Do check out the folder with the document make sure to unzip it 
