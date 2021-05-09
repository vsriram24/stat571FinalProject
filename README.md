# Stat 571 Final Project

All code can be found in "dataintegration_combined.Rmd". This markdown file includes code for combining and cleaning of the data, removal/imputation of missing values, exploratory data analysis, Principal Components Analysis, and Regression Analysis.

All relevant data files can be found in the data folder. Both happiness and health data were downloaded from Kaggle at the following links:
- https://www.kaggle.com/mathurinache/world-happiness-report
- https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete

2019.csv corresponds to happiness data from the year 2019.

All other datasets that are not nnumbered correspond to health data for countries around the globe for set years. Certain datasets are missing data for certain years, and the same missingness applies for countries as well. In terms of data processing, the most recent value of each variable was taken to include for analysis. The final full dataset for which EDA and regression were performed is "./data/fullHappiness.csv".
