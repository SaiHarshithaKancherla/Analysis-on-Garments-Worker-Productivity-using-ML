Regression Project

Synopsis:-

Predicted worker productivity in a garment factory using ML models. Analyzed key features like department and team size to identify top drivers of performance.

Objective:-

The  objective of this project is to predict the  actual productivity of workers.

Data:-

Records:1197

Features:

-date

-Year_Quarter

-department

-day

-team

-targeted_productivity

-Time_per_Item

-Work_in_progress

-over_time

-incentive

-Stopped_Work_Time

-Idle Workers

-no_of_style_change

no_of_workers 

Approach:-

Data Preprocessing: Imputed missing values, encoded categorical variables.

EDA: Used boxplots, heatmaps, and time-series plots to identify patterns and outliers.

Models Applied: Linear Regression, KNN, Decision Tree, Random Forest, Bagging, Boosting, XGBoost, Neural Network.

Evaluation Metrics: MAE, MAPE, and model accuracy.

Key Findings:-

Most Influential Features: Department, team size, and WIP. 

Least Impactful: Incentives and style changes.

Best Model: XGBoost delivered the highest accuracy (MAE = 0.0803, ΜΑΡΕ = 0.1501).

Productivity Trends: Highest in Q1, with a gradual decline across later quarters.


