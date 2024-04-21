## Nashville Property Investment Analysis

This repository contains a comprehensive data analysis aimed at assisting a company in making informed investment decisions in the growing Nashville real estate market. The project involves building predictive models to accurately forecast the best sale value deals for properties in the area. Emphasis is placed on comparing sale prices to property values to identify overvalued or undervalued properties. The goal is to provide insights into factors crucial for finding the best house deals in Nashville.

## Project Overview

**Objective:**
To predict the best sale value deals for properties in Nashville using the "Sale Price Compared to Value" as the target variable.

**Models:** 
Includes implementations of Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting models.

**Data Cleaning:**
Ensures data quality through filtering, removal of irrelevant columns, handling missing values, and feature engineering.

**Exploratory Data Analysis (EDA):**
Provides visualizations and insights into property valuation trends in Nashville.

**Prediction Models:**
Constructs predictive models to determine the likelihood of overvaluation or undervaluation of properties.

**Model Performance Evaluation:**
Assesses model performance using accuracy, precision, recall, and F1 score metrics.

**Conclusion:**
Recommends investment strategies based on the analysis results.

## Key Findings

**Data Cleaning:**

The original dataset was filtered for Nashville properties, irrelevant columns were removed, and missing values were handled, resulting in a dataset with 17 relevant variables and 17926 records.

**EDA:**

Visualizations revealed insights into property valuation trends, including the prevalence of overvalued properties compared to undervalued ones, the fluctuation of building values over time, and the distribution of property grades and land use.

**Prediction Models:**

- Logistic Regression: Identified significant variables affecting property valuation, with an accuracy of roughly 76% and a focus on predicting overvalued properties.
- Decision Tree: Achieved an accuracy of approximately 77%, with a focus on predicting overvalued properties and significant importance assigned to the year of sale, property age, and building value.
- Random Forest: Achieved an accuracy of around 76.44%, with similar performance to the decision tree model.
- Gradient Boosting: Outperformed other models with an accuracy of roughly 78% and a focus on predicting overvalued properties. Identified year of sale and building value as significant predictors.

## Conclusion

- The Gradient Boosting model emerged as the most reliable for predicting overvalued properties in Nashville, with an accuracy of 78% and an F1 score of 0.87 for the overvalued class.
- Investment strategies should prioritize undervalued properties, focusing on properties with promising locations, low transaction volumes, and motivated sellers.
- Recommendations include considering the age of the property, transaction history, and location when making investment decisions.

## Future Directions
- Further refinement of models and feature selection.
- Exploration of additional predictive algorithms.
- Integration of external datasets for enhanced analysis.

This repository serves as a valuable resource for investors, real estate professionals, and stakeholders interested in leveraging predictive modeling to optimize investment decisions in the Nashville housing market.

