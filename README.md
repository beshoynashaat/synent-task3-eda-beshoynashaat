# synent-task3-eda-beshoynashaat
Netflix Content Analysis - Exploratory Data Analysis (EDA)
This project performs an Exploratory Data Analysis on the Netflix dataset to uncover trends, distribution patterns, and historical growth of content on the platform.

1. Problem Statement
With thousands of titles available, understanding the composition of Netflix's library is crucial for market analysis. This task aims to answer key questions:

What is the balance between Movies and TV Shows?

How has the volume of content releases evolved over the decades?

What are the primary statistical characteristics of the dataset?

2. Dataset Details
The script processes the Netflix Titles dataset (netflix_titles.csv).

Data Types: A mix of categorical (type, director, country) and numerical (release_year) information.

Scope: Contains information regarding the title, cast, release year, rating, and duration for both movies and series.

3. Approach
The analysis is broken down into two main phases using pandas, matplotlib, and seaborn:

Statistical Profiling
Data Structure Audit: Uses df.info() to identify data types and the presence of missing values.

Descriptive Statistics: Utilizes df.describe(include='all') to get a high-level summary of both numerical trends and categorical frequencies.

Visual Trend Identification
Categorical Distribution: A count plot is generated to compare the volume of Movies vs. TV Shows, providing a clear visual of Netflix's primary content focus.

Temporal Analysis: A histogram with a Kernel Density Estimate (KDE) is used to visualize the distribution of release_year. This highlights how content production has accelerated over time.

4. Results
Content Preference: The visualizations provide an immediate breakdown of which content format dominates the library.

Historical Growth: The release year distribution reveals the "long tail" of older content versus the recent explosion of digital-first releases.

Data Health: The summary statistics highlight which features (like director or country) may require further cleaning due to missing entries.

How to Run
Ensure you have the required libraries: pip install pandas matplotlib seaborn.

Update the file path in the script to point to your netflix_titles.csv.

Run the script: python synent_task3_eda_beshoynashaat.py.
