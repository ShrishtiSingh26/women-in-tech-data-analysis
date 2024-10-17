# women-in-tech-data-analysis
# Diversity in Tech Companies Analysis

## Overview

This project analyzes diversity data from various tech companies, focusing on gender and ethnic representation over the years. Using a dataset that includes information on the percentage of female and male employees, as well as ethnic diversity percentages, we explore trends and correlations in the tech industry.

## Dataset

The dataset used in this analysis is named `Diversity in tech companies.csv`. It contains the following relevant columns:

- **Year**: The year the data was collected
- **Company**: The name of the tech company
- **Female %**: Percentage of female employees
- **Male %**: Percentage of male employees
- **% White**: Percentage of White employees
- **% Asian**: Percentage of Asian employees
- **% Latino**: Percentage of Latino employees
- **% Black**: Percentage of Black employees
- **% Multi**: Percentage of multi-racial employees
- **% Other**: Percentage of employees from other ethnic backgrounds

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

You can install the required packages using pip:

```bash
pip install pandas matplotlib seaborn
```

## Analysis Steps
# Data Cleaning:

Load the dataset and convert relevant columns to numeric types, handling errors by coercing them to NaN.
Optionally, drop rows with NaN values or fill them with the mean of each column.

# Gender Diversity Analysis:

Group the data by year and calculate the average percentages of female and male employees.
Visualize the trends in gender diversity over the years using a line plot.

# Ethnic Diversity Analysis:

Group the data by year and calculate the average percentages for each ethnic group.
Visualize the trends in ethnic diversity over the years using a line plot.
Correlation Analysis:

Compute the correlation matrix between gender and ethnic diversity percentages.
Visualize the correlation matrix using a heatmap.

# Company-Level Analysis:

Group the data by company and calculate the average gender and ethnic diversity percentages.
Sort the companies by the highest female representation and display the top 10 companies.

## Results
The analysis provides insights into gender and ethnic diversity trends within tech companies. The heatmap allows for an understanding of how different diversity percentages correlate with each other, and the company-level analysis highlights companies leading in female representation.

![Screenshot 2024-10-17 225556](https://github.com/user-attachments/assets/be240dae-2d4b-4df6-b272-4ffaae381062)

![Screenshot 2024-10-17 225538](https://github.com/user-attachments/assets/1ed5ffae-d289-42c2-ae17-63b518ee2a20)

![Screenshot 2024-10-17 225515](https://github.com/user-attachments/assets/54cbeae6-bcad-48a4-807c-453b4b31f0a0)


## Usage
You can run the analysis script to view the plots and results directly. Make sure to place the `Diversity in tech companies.csv` file in the same directory as your script.

```bash
python your_script.py
```
