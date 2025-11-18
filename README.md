# Ridge-Lasso-Regression-Salary-Prediction-Machine-Learning-Project

This project demonstrates how Ridge Regression and Lasso Regression can be applied to a simple dataset to predict salaries based on experience level. It showcases the impact of L1 (Lasso) and L2 (Ridge) regularization on model performance, overfitting control, and coefficient shrinkage.

📂 Project Overview

We use a small custom dataset containing two columns:

level – Experience level (1 to 10)

salary – Corresponding salary values

🎯 Objectives

Fit Ridge Regression and Lasso Regression models

Compare how both techniques handle regularization

Visualize regression curves on a scatter plot

Evaluate performance using R² Score

🧠 Tech Stack

Python

NumPy

Pandas

Matplotlib

Scikit-learn

📊 Visualizations

✔ Scatter plot of level vs salary
✔ Ridge regression curve
✔ Lasso regression curve

📈 Model Evaluation

Both Ridge and Lasso models were trained and tested on the dataset.
The R² score was computed to evaluate how well the models fit the relationship.

📝 Key Insights

Ridge Regression (L2) reduces coefficient magnitude but does not eliminate them

Lasso Regression (L1) performs feature selection by shrinking some coefficients to zero

Both techniques help prevent overfitting, especially with noisy or small datasets

Ridge tends to perform more stable results on small datasets like this one
