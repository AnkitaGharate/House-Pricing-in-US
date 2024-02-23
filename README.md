
Factors influence the home prices across U.S
Objective:
Found publicly available data for key factors that influence US home prices nationally. Then, built a data science model that explains how these factors impacted home prices over the last 20 years.
The project aims to build a data science model to predict U.S. home prices based on key economic factors over the last 20 years.

The following variables are chosen for the study-
Unemployment Rate
Employment Rate
Per Capita GDP
Real Median Household Income
Construction Prices
CPI
Interest Rates
Working Population
Mortgage
Housing subsidies
Number of Households
As a proxy to the home prices, S&P CASE-SHILLER Index is used.
Most of the data is downloaded from [https://fred.stlouisfed.org/].

Steps
1.	Data Collection:
Utilized the S&P Case-Schiller Home Price Index as a proxy for home prices, sourced from the Federal Reserve Economic Data (FRED) website.
2.	Key Factors:
Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, etc.
3.	Data Cleaning and Processing:
Cleaned and processed the data, addressing missing values, converting date formats.
4.	Exploratory Data Analysis (EDA):
Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.
5.	Model Selection:
Explored various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, Support Vector Regression (SVR), and XGBoost.
6.	Model Training and Evaluation:
Trained each model using a subset of the data, evaluated performance using metrics such as Root Mean Squared Error (RMSE) and R-squared.
7.	Feature Importance:
Analyzed feature importance for models like Random Forest, XGBoost, and Gradient Boosting to understand the factors influencing home prices.
8.	Model Comparison:
Compare the performance of different models based on metrics such as Mean Squared Error (RMSE) and R-squared.
Select the best-performing model that provides accurate predictions and insights into the factors influencing home prices over the last 20 years.
9.	Visualization:
Create visualizations to illustrate the relationships between actual and predicted home prices for each model.
Visualize the importance of different features or coefficients in influencing home prices.


10.	Conclusion:
Identified strong contender for the best model, considering their low RMSE and high R-squared values.
Draw conclusions about the key factors that have historically influenced US home prices.
11.	Overall Implication:
The project contributes to understanding the key factors influencing U.S. home prices over the last 20 years and provides a foundation for building robust predictive models in the real estate domain.

Conclusion:
Random Forest and Gradient Boosting appear to be strong contenders, as they have low RMSE and high R-squared values. Additionally, both models provide insights into feature importance.
XG Boosting also performs well but with a slightly lower R-squared compared to Random Forest and Gradient Boosting.
Linear Regression and ElasticNet have higher RMSE values, indicating potential limitations in predictive accuracy.
SVR has a considerably higher RMSE and lower R-squared, suggesting lower performance compared to other models.

Article referred -
https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp
Research Paper referred -
https://www.atlantis-press.com/article/25841966.pdf
