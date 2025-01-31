# Project Overview: Data Cleaning and Exploratory Data Analysis (EDA) for Layoff Data

# Project Objective:

The goal of this project is to clean, standardize, and analyze a dataset containing information about global layoffs. The dataset includes various details such as company names, industries, locations, the number of employees laid off, and other relevant factors. By performing data cleaning and exploratory data analysis (EDA), the project aims to prepare the data for deeper insights and better decision-making.

# Key Steps Involved:

# 1. Data Cleaning:
- Staging Table Creation: A new staging table is created to work with a copy of the raw data, preserving the original dataset in case of errors during cleaning.
- Duplicate Removal: Duplicates are identified based on key attributes like company, location, industry, total laid-off employees, and date. These duplicates are removed to ensure the integrity of the data.
- Data Standardization: Issues such as inconsistent industry names (e.g., "Crypto Currency" vs. "Crypto"), blank or null values in key columns, and date formatting problems are addressed. Columns with inconsistent or incorrect values are cleaned, and missing values are handled appropriately.
- Handling Null Values: Empty fields, especially in columns like industry, total_laid_off, and percentage_laid_off, are carefully reviewed. In some cases, nulls are populated based on existing data (e.g., using the company name to update missing industry values).
- Removing Unnecessary Data: Rows and columns with irrelevant or missing data (such as rows where both total_laid_off and percentage_laid_off are null) are removed to make the dataset more useful.

# 2. Exploratory Data Analysis (EDA): After cleaning the data, the project proceeds with exploratory analysis to identify trends, patterns, and anomalies in the layoffs:
- Total Layoffs by Company: Analyzing which companies have the largest total layoffs.
- Layoffs by Location: Identifying which locations (countries, regions, or cities) are most impacted by layoffs.
- Time-Based Analysis: Examining how layoffs have evolved over the years, as well as the monthly trends.
- Industry Trends: Grouping data by industry to see which sectors have been most impacted by layoffs.
- High Percentage Layoffs: Identifying companies where 100% of their workforce was laid off, which is common in startups or businesses facing closure.

# 3. Advanced Queries:
- Top Layoffs by Company and Year: A more granular breakdown of layoffs by year to understand patterns over time.
- Rolling Layoff Totals: A cumulative view of layoffs over time (e.g., by month), allowing the identification of specific months with significant layoffs.
- Yearly Breakdown: Analyzing the layoffs for each year, which helps identify trends across multiple years.

# 4. Deliverables:
- Cleaned Dataset: A fully cleaned, standardized dataset that is ready for further analysis and decision-making.
- Exploratory Data Analysis Report: A summary of key findings from the analysis, including trends in layoffs by company, industry, location, and time.
- SQL Scripts: A collection of SQL scripts used for data cleaning and analysis, which can be reused or modified as needed.
- Insights and Recommendations: Based on the analysis, strategic recommendations will be provided to help stakeholders understand the broader trends in layoffs and workforce reductions. This can assist in making informed decisions about future business or HR strategies.
