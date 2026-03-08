# North Carolina County-Level Poverty Analysis

A data analysis project exploring county-level poverty patterns across North Carolina using Python-based data science tools. This project demonstrates a reproducible workflow for data cleaning, exploratory data analysis (EDA), and visualization to uncover geographic disparities in poverty.

## Project Motivation

Statewide averages often mask significant regional differences in economic well-being. By analyzing poverty data at the county level, we can identify geographic patterns and highlight communities that may experience disproportionately high poverty rates.

This project demonstrates how data analysis and visualization can help uncover socioeconomic trends and support data-driven decision making.

## Key Questions

This analysis aims to answer several questions:

Which counties in North Carolina have the highest poverty rates?

Which counties have the lowest poverty rates?

How large is the variation in poverty across counties?

Are there identifiable regional patterns in poverty distribution?

## Tools & Technologies

The analysis was conducted using the following tools:

Tool	Purpose
Python	Core programming language
Pandas	Data cleaning and manipulation
Matplotlib / Seaborn	Data visualization
Jupyter Notebook	Interactive data analysis
Git & GitHub	Version control and project sharing

# Project Workflow

## 1. Data Collection

County-level socioeconomic data was collected from publicly available sources containing poverty-related indicators.

Typical variables include:

County Name

Poverty Rate

Population

Median Household Income

Other socioeconomic indicators

## 2. Data Cleaning

Before analysis, the dataset was prepared through:

Handling missing values

Standardizing county names

Converting columns to appropriate data types

Removing duplicate records

Clean data ensures reliable and reproducible analysis.

## 3. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and distributions within the dataset.

Key analysis steps included:

Examining the distribution of poverty rates

Identifying counties with extreme poverty levels

Comparing poverty rates across counties

Investigating potential economic disparities

## 4. Data Visualization

Visualizations were created to make the results easier to interpret.

Positive Correlation between logged SNAP Recipients and logged Civilians in Poverty in North Carolina

<img width="480" height="342" alt="image" src="https://github.com/user-attachments/assets/d1fbb6f7-f849-415f-8d14-b07b69fe4c3f" />

SNAP Recipients

<img width="480" height="342" alt="image" src="https://github.com/user-attachments/assets/fd83fb32-3109-45d8-b4e0-08662457d59f" />

Line charts highlighting counties with the highest poverty

<img width="480" height="342" alt="image" src="https://github.com/user-attachments/assets/233d361c-ca47-4778-8b56-6ea1b4d69b1d" />

Visualizations help communicate insights clearly and effectively.

Example Insights

Although results depend on the dataset used, county-level analysis typically reveals:

Significant variation in poverty rates between counties

Higher poverty rates in many rural counties

Lower poverty rates in more economically developed regions

These insights highlight how geographic context plays a major role in economic inequality.


# How to Run the Project

Clone the repository
git clone https://github.com/Wabdulla04/North-Carolina_County_Level_Poverty_Analysis.git
Navigate into the project directory
cd North-Carolina_County_Level_Poverty_Analysis
Install dependencies
pip install -r requirements.txt
Run the notebook

Launch Jupyter and open the analysis notebook:

jupyter notebook

# Potential Future Improvements

Several extensions could make the analysis more powerful:

Adding geospatial mapping using GeoPandas

Performing regression analysis to identify poverty predictors

Building an interactive dashboard using Plotly or Streamlit

Incorporating multiple years of poverty data for trend analysis

Creating an automated data pipeline

# Author

Waleed Abdulla

Data Science Student

Teaching Assistant for Applied Regression

Interested in data engineering, analytics, and data-driven decision making

⭐ If you find this project interesting, feel free to explore the notebook and visualizations.
