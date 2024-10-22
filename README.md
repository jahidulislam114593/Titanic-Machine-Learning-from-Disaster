# Titanic Dataset Analysis

## Overview
This project presents an in-depth analysis of the Titanic dataset, exploring various factors that influenced passenger survival. The analysis includes data cleaning, exploratory data analysis (EDA), and basic statistical tests to extract meaningful insights.

The dataset contains information about passengers such as age, gender, class, fare, and survival status. The analysis reveals how these factors impacted the chances of survival in the infamous Titanic disaster.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Statistical Analysis](#statistical-analysis)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
  
## Project Structure
- `Titanic_EDA.ipynb`: Jupyter notebook containing the step-by-step analysis.
- `README.md`: This file explaining the analysis process.
- `titanic.csv`: The Titanic dataset (not included; you can download it [here](https://www.kaggle.com/c/titanic/data)).

## Dataset
The Titanic dataset used in this analysis can be found on [Kaggle](https://www.kaggle.com/c/titanic/data). It contains data on 891 passengers who were aboard the Titanic, along with various features like:
- **Survival**: Whether the passenger survived or not (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, or 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **Fare**: Amount of money paid for the ticket
- And more...

## Data Cleaning
Before analyzing the dataset, we performed the following cleaning tasks:
- **Missing values**: Imputed missing values in the 'Age' and 'Embarked' columns and dropped the 'Cabin' column due to excessive missing values.
- **Duplicates**: No duplicate rows were found.
  
## Exploratory Data Analysis
In this phase, we explored the data to uncover initial insights:
- **Gender Distribution**: The dataset had significantly more males (577) than females (314).
- **Fare**: The mean fare was $32.20, with a median of $14.45. Most passengers paid lower fares, as indicated by the mode fare of $8.05.
- **Age**: The average age was 29 years, with both the median and mode age being 28, indicating a fairly normal distribution.

## Statistical Analysis
We performed the following statistical tests to validate our insights:
- **T-test (Gender and Survival)**: There was a statistically significant difference in survival rates between males and females (p-value ≈ 0).
- **ANOVA (Class and Fare)**: Significant differences in fares across the three passenger classes were observed (p-value ≈ 0).

## Key Insights
- **Higher Survival Rates for Females**: Women had a far better chance of survival than men.
- **Class Impacts Fare**: Passengers in 1st class paid significantly more for their tickets compared to those in 2nd and 3rd class.
  
## Conclusion
This project highlighted the importance of gender, age, class, and fare in determining the likelihood of survival in the Titanic disaster. The analysis provided a foundation for further predictive modeling, such as building machine learning models to predict survival based on passenger attributes.

## How to Run
To run this analysis locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-analysis.git
