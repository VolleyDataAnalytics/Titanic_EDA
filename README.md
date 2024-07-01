# Exploratory Data Analysis

## Introduction
In this project, we perform Exploratory Data Analysis (EDA) on the Titanic dataset. 
EDA is a crucial step in the data analysis process that involves summarizing the main characteristics of a dataset, often using visual methods.
This analysis aims to uncover patterns, spot anomalies, test hypotheses, and check assumptions with the help of summary statistics and graphical representations.

# Dataset Description
## Source
The dataset used in this project is obtained from the Kaggle Titanic Dataset.

## Description 
The dataset contains information on passengers aboard the RMS Titanic, which sank during its maiden voyage in April 1912 after hitting an iceberg.
The dataset includes the following features:

PassengerId: Unique ID for each passenger
Survived: Survival (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Name of the passenger
Sex: Gender
Age: Age in years
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Objectives
The primary objectives of this EDA are:

1. To understand the distribution and relationship of the variables in the dataset.
2. To identify any missing values or outliers.
3. To uncover any interesting patterns or trends in the data.
4. To generate hypotheses for further analysis or modeling.
## Methodology
The steps involved in the EDA process are as follows:

1.Data Cleaning: Handling missing values, correcting errors, and ensuring consistency.
2.Data Visualization: Creating various plots and charts to visualize the data distributions and relationships.
3.Statistical Analysis: Calculating summary statistics and identifying significant patterns.
## Results
## Key Findings
1.Survival Rate: The overall survival rate is about 38%.
2.Gender: Females had a significantly higher survival rate (74%) compared to males (19%).
3.Class: Passengers in 1st class had a higher survival rate (63%) compared to those in 2nd class (47%) and 3rd class (24%).
4.Age: Children (age < 16) had a higher survival rate compared to adults.
5.Embarkation: Passengers who embarked from Cherbourg had a higher survival rate compared to those from Queenstown and Southampton.

## Visualizations

Figure 1: Survival Rate by Gender


Figure 2: Survival Rate by Class


Figure 3: Age Distribution

## Conclusion
The EDA provided valuable insights into the Titanic dataset. The analysis revealed that gender, class, and age were significant factors in determining survival. 
The next steps could include building predictive models to estimate survival based on these factors.

