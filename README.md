

# Google Play Store App Analysis
## Overview

All the relevant coding files and reports are in this particular repository along with detailed reports of my findings.  This data analysis is performed using R.

### Objective
The purpose of this project is to perform an exploratory data analysis (EDA) of the Google Play Store dataset.  I will explore the relationships between the variables available in this dataset and what affect the variables have on how consumers interact with these apps in terms of Ratings, Reviews and Installs. Finally, I will perform logistic regression to determine if it is possible to predict the amount of Installs an app receives by using the variables in this dataset. 

### Data Cleaning
The raw data can be found in the zip file "Google-Playstore-Full.zip" and the code for data clean-up can be found under the Data Cleaning section of the “GPS Analysis.Rmd” file. In this section I removed rows with misaligned data and columns with no data.  I also formatted the data in a way that R could process it by removing commas, dollar signs, etc. and assigned each variable the proper data type (numeric/factor/etc.).

### Exploratory Data Analysis
EDA was performed to explore trends in each variable in the dataset. Some of the variables were transformed to achieve a normally distributed bell curve as the tests I planned to use for statistical analysis assumed that variables would have a normal distribution.  The detailed report can be found in the “GPS Exploratory Data Analysis.pdf” file and the code can be found in the Univariate Analysis section of the “GPS Analysis.Rmd” file.

### Statistical Analysis
The trends observed in EDA were subjected to statistical tests and methods, and the code for the same is presented in the Bivariate Analysis and Hypothesis Testing section of the “GPS Analysis.Rmd” file. In these sections I look at the relationship between Installs and all other variables and attempt to confirm assumptions I made about the data. Please reference the “GPS Statistical Analysis.pdf” file for a detailed report of my findings here. 

### Regression
Installs were grouped into a binary classification of “High Installs” and “Low Installs.”  Simple logistic regression was used for Installs and Rating to determine if Rating alone would be a good predictor for the number of Installs an app received.  Next, I looked at multiple logistic regression models to see if I could find better predictors for Installs.  The code for this can be found under the Regression section of the “GPS Analysis.Rmd” file. Further detail for this section can be found in the Final Report below.

### Final Report
A summary of my findings and the conclusion can be found in the final report “GPS Final Report.pdf.”
