# M_L-Project
Project Overview
Objective:
Predict the Customer Lifetime Value (CLV) for an auto insurance company in the USA. The goal is to identify high-value customers to improve retention, optimize promotional offers, and better allocate marketing resources.

Business Context:
In a competitive insurance market, premium isn’t the sole factor in customer decisions. By focusing on CLV—a metric that captures the long-term value of each customer—the company can:

Enhance customer retention and acquisition strategies.
Prevent churn and target promotions effectively.
Make data-driven decisions on marketing investments.
Dataset Description
Size & Scope:
The dataset includes over 9,134 records and more than 24 features.

Content:
It contains both numerical and categorical features such as customer demographics, policy details, premium amounts, claim amounts, and more.

Source:
Data is provided via a Google Sheets link, and the file used in this project is an Excel file.

Project Steps
Data Loading & Preprocessing:

Load the dataset from Excel.
Clean the data by removing unnecessary columns (like customer IDs and dates).
Encode categorical variables (using one-hot encoding) and handle missing values.
Exploratory Data Analysis (EDA):

Analyze the distribution and correlation of features.
Visualize relationships between key variables (for example, how premium amounts and claim history relate to CLV).
Model Training:

Use various regression models such as Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, and AdaBoost.
Evaluate model performance using metrics like R² score and RMSE.
Hyperparameter Tuning:

Optimize the best-performing model (Random Forest in this case) using GridSearchCV to fine-tune parameters such as the number of estimators and maximum tree depth.
Prediction & Deployment:

Make predictions on test data and for individual new records.
Save the trained model for future use.
Project Submission:

Upload the final project code and files to GitHub.
Include a README that documents your approach, thought process, and findings.
Business Impact
By accurately predicting CLV, the auto insurance company can target marketing efforts, retain valuable customers, and plan budgets more efficiently, thereby improving overall customer satisfaction and revenue.

