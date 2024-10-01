## Data Analyst Skills Analysis

## Project Overview

Using a dataset of data-related job postings, the analysis focuses on:

- **Top 10 Highest-Paid Skills**: Identifying which skills command the highest median salary for Data Analysts.
- **Top 10 Most In-Demand Skills**: Determining the skills most frequently mentioned in job postings.

## Requirements

To run this project, you'll need the following Python packages:

- `pandas`
- `datasets`
- `matplotlib`
- `seaborn`

## Data Source
The dataset used in this project is from lukebarousse/data_jobs. It contains information about various data-related job postings, including job titles, skills required, and salary information.

##Analysis Steps
The analysis is performed in a Jupyter Notebook or Python script, where the following steps are executed:

Load the dataset and convert the job posting date to a datetime format.
Extract and process job skills from the dataset.
Filter for Data Analyst positions located in the United States.
Explode the job skills column to analyze skills individually.
Calculate the median salary for each skill and the count of job postings.
Create bar plots to visualize the results.
