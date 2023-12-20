# Real-Estate-Valuation-Analysis-Part-2
Real Estate Valuation Analysis in New Taipei City Part 2

Project Report: Analysis of Real Estate Valuation in New Taipei City
Overview

Part 2 of this project focused on an extensive analysis of the 'real-estate-valuation-data-set.csv', a subset of data from the UCI Machine Learning Repository. This dataset provided insights into the real estate market of New Taipei City, Taiwan, including data on house age, proximity to Mass Rapid Transit (MRT) stations, the count of nearby convenience stores, and the unit price of houses, calculated in 10,000 New Taiwan Dollars per Ping (where 1 Ping = 3.3 square meters).

Objectives & Methods

The project explored various dimensions of the dataset through a series of detailed tasks:

- Multiple Linear Regression Analysis: The data was reloaded in R, and a multiple linear regression model was developed, focusing on the relationship between the unit price (unit_price), the number of convenience stores (convenience_stores), and the distance to the nearest MRT station (distance). The Variance Inflation Factors (VIF) were evaluated to assess collinearity issues between the predictors.
- Model Summary and Interpretation: The summary of this multiple regression model was examined in R, and the coefficients associated with convenience_stores and distance were interpreted in straightforward language.
- F-test Results Interpretation: The results of the F-test for this model were analyzed and interpreted, providing insights into the model's overall significance.
- Coefficient of Determination (R²) Interpretation: The project involved interpreting the coefficient of determination (R²) for this model, offering a clear explanation of its meaning and implications.
- Data Visualization: Plots were created to visually represent the relationships between unit_price and each of the predictors: convenience_stores and distance.
- Model Appropriateness Evaluation: Based on these visualizations, an evaluation was conducted to determine whether the multiple linear regression model was appropriate for this dataset.
- Alternative Model Exploration: Given indications that the relationship between unit_price and distance might be exponential, a plot was created showing unit_price against the logarithm of distance. This was done to explore if a logarithmic transformation would yield a more linear relationship.

Deliverables:

The project culminated in a comprehensive report that detailed the findings from each of these analyses. Through statistical evaluation and visual representations, the report provided a thorough understanding of the factors influencing real estate prices in New Taipei City. It not only highlighted the correlations within the data but also explored the potential for model improvements, particularly in the context of the distance variable. The project demonstrated a methodical approach to data analysis, blending statistical methods with practical evaluations to draw meaningful conclusions about the real estate market.
