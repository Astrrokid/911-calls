# 911 Emergency Calls - Exploratory Data Analysis

## Overview
This project focuses on conducting exploratory data analysis (EDA) on a dataset containing emergency calls information. The dataset includes details such as the location, type of emergency, timestamp, and more. The goal of the analysis is to gain insights into patterns, trends, and distributions within the emergency calls data.

## Dataset
The dataset used for this analysis (`911.csv`) contains emergency calls information, including the following columns:
- `lat`: Latitude of the emergency call location
- `lng`: Longitude of the emergency call location
- `desc`: Description of the emergency call
- `zip`: Zip code of the emergency call location
- `title`: Title of the emergency call
- `timeStamp`: Timestamp of the emergency call
- `twp`: Township of the emergency call location
- `addr`: Address of the emergency call location

The dataset provides a comprehensive overview of emergency calls made over a period of time.

## Tools and Libraries Used
- Python
- pandas
- numpy
- matplotlib
- seaborn

## Analysis Steps

1. **Data Loading and Inspection**: Loading the dataset and checking basic information about the data.

2. **Exploratory Data Analysis (EDA)**:
   - Exploring the top ZIP codes and townships with the most emergency calls.
   - Extracting the reason for the call from the title column.
   - Visualizing the count of emergency calls by reason.

3. **Feature Engineering**:
   - Converting the timestamp to datetime format.
   - Extracting additional time-based features such as hour, month, and day of the week.
   - Mapping numerical representations of days of the week to their respective names.

4. **Temporal Analysis**:
   - Visualizing emergency calls over time (by month and day of the week).
   - Analyzing the correlation between days of the week and hours using heatmaps and clustermaps.

## Files Included
- 911-calls.ipynb: Jupyter Notebook containing the Python code for data loading, exploration, preprocessing, and analysis.
- 911.csv: Dataset containing emergency calls information.
- README.md: This file providing an overview of the project.

## How to Use
1. Clone the repository to your local machine.
2. Open the 911-calls.ipynb file using Jupyter Notebook or any compatible IDE.
3. Run the code cells sequentially to reproduce the analysis.
4. Explore the visualizations and insights generated from the analysis.
5. Modify or extend the analysis as needed for further exploration or research.

## Author
Chukwudalu CN
