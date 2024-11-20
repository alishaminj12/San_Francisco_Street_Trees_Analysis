# San Francisco Street Trees Analysis: Identifying Top Locations for Tree Appreciation Program

## Overview
This project is part of the **Google Business Intelligence Professional Certificate** and involves analyzing street tree data from San Francisco to assist in planning for the city's annual tree appreciation event. The dataset contains information on trees planted along city streets.

### Objective:
- Identify the top 10 addresses with the most trees planted along the streets.
- Provide insights for the mayor’s team to plan for tree decoration and cleanup.

## Dataset
The data used in this analysis is from the **San Francisco Street Trees** dataset, which is publicly available on the City of San Francisco's data portal. You can download the dataset using the following link:
- [San Francisco Street Tree List Dataset](https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq/data_preview)

### Methodology:
1. **Data Extraction**: The data was extracted using **Google BigQuery**, a cloud-based data warehouse solution. SQL queries were used to identify the top 10 addresses with the most trees.
2. **Data Cleaning**: Removed null values and irrelevant data points.
3. **SQL Analysis**: Utilized SQL queries to analyze tree distribution and aggregate data by address.
4. **Visualization**: Created visualizations to illustrate tree distribution across the top addresses.

## Tools:
- **Google BigQuery**: A powerful, serverless data warehouse solution used for SQL-based analysis.
- **Google Business Intelligence Tools**: Part of the Google Business Intelligence Certification course.

## Results:
The top 10 addresses with the most trees are as follows:

1. **100X Cargo Way** - 135 trees
2. **700 Junipero Serra Blvd** - 125 trees
3. **1000 San Jose Ave** - 113 trees
4. **1200 Sunset Blvd** - 110 trees
5. **1600 Sunset Blvd** - 102 trees
6. **2301 Sunset Blvd** - 94 trees
7. **1501 Sunset Blvd** - 93 trees
8. **2401 Sunset Blvd** - 92 trees
9. **100 STAIRWAY5** - 87 trees
10. **2601 Sunset Blvd** - 84 trees

### Conclusion:
This analysis identifies the top 10 locations with the highest number of trees, helping the mayor’s team plan for the tree decoration and cleanup events efficiently. The next steps may involve additional data visualizations and creating optimized routes for event logistics.

## Files:
- `Street_Tree_Analysis_Report.pdf`: Detailed report with findings.
- `Top_10_Tree_Addresses.csv`: CSV file containing the top 10 addresses and their tree counts.
- `Tree_Distribution_Chart.png`: A chart showing tree distribution across different locations.
