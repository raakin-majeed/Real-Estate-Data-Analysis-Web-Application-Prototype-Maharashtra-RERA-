# Real-Estate-Data-Analysis-Web-Application-Prototype-Maharashtra-RERA-
 This repository showcases a multi-faceted project focusing on real estate data from the Maharashtra Real Estate Regulatory Authority (RERA) portal. It includes data cleaning, exploratory data analysis, and a foundational Flask web application to demonstrate potential data serving.
This project was developed during my Computer Science Internship at Square Yards in May-June 2023, where I gained hands-on experience in data engineering and web development.

Project Structure & Contents
This repository contains the following Jupyter Notebooks:

rera details data cleaning.ipynb:
Purpose: This notebook is dedicated to cleaning and pre-processing a large dataset of RERA project details. It addresses common data quality issues to prepare the data for analysis.

Key Operations:
Handling missing values in critical numerical fields ('Carpet Area', 'Open Area').
Converting and extracting insights from date columns ('Date of Registration', 'Proposed Completion Date').
Parsing and creating categorical flags from free-text 'Unit Types' (e.g., '1BHK', '2BHK', 'Shop', 'Office').
Extracting 6-digit PIN codes from the 'Address' column using regular expressions.
Saving the cleaned data for further use.
Skills Demonstrated: Data Cleaning, Data Pre-processing, Pandas, Regular Expressions (Regex), Feature Engineering.

Maharashtra.ipynb:
Purpose: This notebook focuses on exploratory data analysis (EDA) of the cleaned Maharashtra RERA data. It aims to derive initial insights and visualize key trends within the dataset.

Key Operations:
Loading and inspecting the processed real estate data.
Analyzing the distribution of projects across different districts.
Visualizing project statuses.
Aggregating and examining total carpet area by district.
Identifying top districts based on project counts and area.
Skills Demonstrated: Exploratory Data Analysis (EDA), Data Visualization (Matplotlib, Seaborn), Pandas, Data Aggregation.

flask.ipynb:
Purpose: This notebook serves as a prototype for a basic Flask web application. It demonstrates the initial steps of setting up a web server and defining API endpoints, with the potential to serve the cleaned real estate data.

Key Operations:
Initializing a Flask application.
Defining simple routes for a home page and a data API endpoint.
Returning basic text or JSON data responses.
Outlines the foundational structure for integrating data-driven web functionalities.
Skills Demonstrated: Web Development Fundamentals, Flask (Python Web Framework), API Design Concepts, JSON handling.
