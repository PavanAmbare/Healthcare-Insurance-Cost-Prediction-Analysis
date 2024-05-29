
# Healthcare Insurance Cost Prediction & Analysis

## Project Overview
This capstone project focuses on predicting the optimum insurance cost for individuals based on their health and habit-related parameters. The project leverages a dataset containing various attributes to build a predictive model and extract actionable insights, aiming to enhance pricing strategies and improve public health.

## Table of Contents
- [Introduction](#introduction)
- [Business Problem Statement](#business-problem-statement)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Business Insights](#business-insights)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

## Introduction
In the healthcare industry, insurance cost estimation is crucial for both providers and customers. This project aims to predict insurance costs based on various health and lifestyle parameters using machine learning techniques. Accurate predictions help in optimizing insurance premiums and promoting healthy lifestyles.

## Business Problem Statement
The objective is to develop a predictive model that estimates the optimum insurance cost for an individual based on their health and habit-related parameters. The project addresses the critical nature of healthcare, the importance of proactive health management, and the financial implications of insurance.

## Data Description
The dataset contains the following attributes:
- years_of_insurance_with_us
- regular_checkup_last_year
- adventure_sports
- occupation
- visited_doctor_last_1_year
- cholesterol_level
- daily_avg_steps
- age
- heart_decs_history
- other_major_decs_history
- Gender
- avg_glucose_level
- bmi
- smoking_status
- Year_last_admitted
- Location
- weight
- covered_by_any_other_company
- Alcohol
- exercise
- weight_change_in_last_one_year
- fat_percentage
- insurance_cost

## Data Preprocessing
Data preprocessing steps included:
- Handling missing values in the BMI and Year Last Admitted columns.
- Encoding categorical variables.
- Standardizing numerical features.
- Addressing class imbalance in the dataset.

## Exploratory Data Analysis (EDA)
EDA was conducted to understand the distribution and relationships within the data. Key steps included:
- Analyzing the distribution of insurance costs.
- Visualizing the relationships between insurance costs and other attributes.
- Identifying outliers and anomalies in the data.
- Clustering customers based on attributes to uncover distinct segments.

## Model Building
Various machine learning models were built and tuned for predicting insurance costs, including:
- **PARAMETRIC MODELS** 
- Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression

  
- **NON PARAMETRIC MODELS**
- Random Forest Regression
- Gradient Boosting Machine
- XGBoost
- AdaBoost

## Model Evaluation
Models were evaluated based on performance metrics such as Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE),  R-squared and Adjusted R-squared . Residual plots were analyzed to assess bias and model performance. The best-performing model was selected based on these metrics.

## Business Insights
The project provided several business insights, such as:
- Identifying key factors influencing insurance costs.
- Understanding the impact of lifestyle habits on health insurance premiums.
- Segmenting customers to tailor insurance products and pricing strategies.
- Recommending proactive health management practices to reduce insurance costs.

## Conclusion
The project successfully developed a predictive model for insurance costs and provided actionable insights for optimizing pricing strategies and promoting healthy lifestyles. The findings contribute to better decision-making in the healthcare insurance domain.

## Future Work
Future enhancements could include:
- Incorporating more diverse datasets to improve model generalizability.
- Exploring additional machine learning algorithms.
- Implementing real-time prediction systems for dynamic pricing.
- Conducting longitudinal studies to track changes in insurance costs over time.

