Sales Prediction

This project was completed as part of the CodSoft Data Science Virtual Internship.
The goal of this task is to predict product sales based on advertising expenditure using basic regression techniques.

About the Project

The Advertising dataset is a widely used dataset for understanding regression models in machine learning.

In this task, I used advertising spending data from TV, Radio, and Newspaper channels to build a model that predicts Sales.

The focus of this project was not just prediction accuracy, but understanding the complete regression workflow and interpreting model results for business insights.

Dataset

The dataset includes the following key features:

TV

Radio

Newspaper

Sales (target variable)

All features are numerical and represent advertising budget (in thousands of dollars) and resulting sales.

What I Did

The project was completed using the following steps:

Loaded and explored the dataset

Checked for missing values and data types

Visualized relationships between advertising channels and sales

Selected relevant features for prediction

Split the dataset into training and testing sets

Trained a Linear Regression model

Evaluated the model using MAE, MSE, and R² score

Interpreted model coefficients to extract marketing insights

Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Results

Model: Linear Regression

R² Score: ~0.90

MAE: ~1.27

MSE: ~2.90

The model explains approximately 90% of the variation in sales, indicating a strong relationship between advertising spend and revenue.

Radio advertising showed the highest impact on sales, while Newspaper had minimal influence.

Conclusion

This project helped me understand how regression models work and how they can be used to support real-world business decisions.

It strengthened my understanding of feature importance, model evaluation, and practical interpretation of machine learning results.

Overall, this task provided hands-on experience with an end-to-end regression workflow.

Files in This Folder

Sales_prediction.ipynb – Complete implementation of the project

advertising.csv – Dataset used

README.md – Project description
