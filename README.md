# San Francisco Street Trees Analysis

## Project Overview
This project extracts and analyzes data from the publicly available **San Francisco Street Trees dataset** using Google BigQuery. The goal is to identify the top 10 street addresses with the highest number of trees for a tree appreciation program.

## Objectives
- Extract tree data from the dataset into a target table.
- Identify and rank the top 10 addresses by tree count.
- Save results for further analysis and planning.

## Steps Taken
1. Used the following SQL query in BigQuery:
   ```sql
   SELECT
       address,
       COUNT(address) AS number_of_trees
   FROM
       `bigquery-public-data.san_francisco_trees.street_trees`
   WHERE
       address != "null"
   GROUP BY address
   ORDER BY number_of_trees DESC
   LIMIT 10;
