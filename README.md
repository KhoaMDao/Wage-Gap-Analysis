# Understanding the Gender Wage Gap: A Comparative Analysis of Income Disparities with Linear Regression

## Project Overview
This project aims to analyze income disparities between genders using multivariate regression models. We utilize the IPUMS USA dataset, specifically the 2022 American Community Survey (ACS), to explore the associations between individual income and various factors such as gender, age, race, education, and geographic location. Our primary objective is to understand the wage gap and contextualize its significance within the United States.

## Key Findings
+ **Gender Pay Gap:** Our analysis reveals a persistent gender pay gap, with males earning on average 26.9% more than females, after controlling for other factors.
+ **Geographic Influence:** Geographic location significantly impacts income, with certain regions showing higher average incomes than others.
+ **Educational Impact:** The field of degree has a substantial effect on income, with STEM and Business degrees associated with higher earnings compared to fields like Arts and Design or Education.
+ **Racial Disparities:** There are notable income disparities across different races, with some racial groups earning significantly less than their white counterparts.

## Methodology
+ **Data Cleaning and Preparation:** The dataset was cleaned, re-coded, and transformed to ensure accurate analysis.
+ **Regression Modeling:** A multivariate regression model was created to study the relationship between income and various factors: 
  $$log(INCTOT)=AGE+AGE^2+SEX+RACE+WorkRegion+UHRSWORK+DEGFIELD$$
+ **Cross-Validation:** We performed 10-fold cross-validation to validate the model and ensure its robustness.

## Authors
+ Khoa Dao
+ Jake Birnbach
+ Yan Mazheika








