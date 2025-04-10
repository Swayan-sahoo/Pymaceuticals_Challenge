# Pymaceuticals_Projects
## Pymaceuticals, Inc. - SCC Treatment Study Analysis
# Project Overview
This analysis focuses on a recent animal study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The study evaluates the efficacy of various treatment regimens, including the company’s drug of interest, Capomulin, on squamous cell carcinoma (SCC) in mice. A total of 249 mice were observed over a period of 45 days, with tumor volume recorded at multiple time points. The goal of this study is to compare Capomulin's performance against other treatments.

## Objectives
# The analysis tasks include:

# Data Preparation: Merging datasets, cleaning duplicates, and creating a standardized dataset.
Summary Statistics: Calculating mean, median, variance, standard deviation, and SEM for tumor volume across treatment regimens.
# Visualization:
Bar charts for the count of observations per treatment regimen.
Pie charts showing the gender distribution of mice.
Box plots to analyze the final tumor volumes in the top treatment regimens.
Line plot and scatter plot to visualize individual treatment effects and correlations.
Statistical Analysis: Correlation and regression analysis between weight and tumor volume for Capomulin-treated mice.
Files
mouse_metadata.csv: Contains metadata about each mouse in the study, including gender and weight.
study_results.csv: Contains tumor volume measurements over time for each mouse and drug regimen.
Code Structure
The project includes the following sections:

## 1. Data Preparation
Merge mouse_metadata and study_results datasets.
Identify and remove any duplicate entries for accurate analysis.
## 2. Summary Statistics
Generate a table with mean, median, variance, standard deviation, and SEM for tumor volume for each drug regimen.
## 3. Visualizations
Bar Charts: Show the number of observations (Mouse ID/Timepoints) for each drug regimen using both Pandas and Matplotlib.
Pie Charts: Display the distribution of unique male vs. female mice in the study using both Pandas and Matplotlib.
Box Plot: Analyze final tumor volumes for Capomulin, Ramicane, Infubinol, and Ceftamin, highlighting potential outliers.
Line Plot: Track tumor volume over time for a single mouse treated with Capomulin.
Scatter Plot: Explore the relationship between mouse weight and average tumor volume for Capomulin-treated mice.
## 4. Correlation and Regression Analysis
Calculate the correlation coefficient between weight and tumor volume for mice on Capomulin.
Perform linear regression and plot the regression line over the scatter plot to visualize the relationship.
Key Observations
Effectiveness of Capomulin and Ramicane:

Both Capomulin and Ramicane showed lower average tumor volumes, indicating their potential as effective treatments for SCC.
Relationship Between Weight and Tumor Volume:

There is a positive correlation between mouse weight and tumor volume, suggesting that physiological factors like weight could influence tumor development.
Gender Distribution:

The gender distribution of mice is balanced, reducing bias and ensuring reliable analysis of treatment effects across both genders.
Requirements
Python: Version 3.7+
Libraries:
pandas
matplotlib
scipy
# How to Run the Analysis
Clone the repository and navigate to the project folder.
Ensure you have all required libraries installed.
Run each code block sequentially in a Python environment or Jupyter Notebook to generate the tables and visualizations.
Conclusion
The study highlights Capomulin and Ramicane as potentially effective treatments for SCC. Further investigation into the weight-tumor volume relationship may provide insights into personalized treatment strategies. This analysis forms a foundation for Pymaceuticals’ ongoing research and development in anti-cancer medications.

This README file provides a structured overview of your project, including objectives, code structure, key observations, and instructions for replicating the analysis. Let me know if you'd like to add any specific details!
