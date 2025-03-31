# Student-Admission-Prediction
This R Markdown project demonstrates the use of machine learning techniques to predict student admission outcomes based on a synthetic dataset with 15 features. The main focus of the project is to apply Random Forest and XGBoost algorithms for predictive modeling, while also interpreting feature importance and evaluating model performance.

Key Steps:
Data Loading & Preprocessing: The dataset is loaded, cleaned, and prepared for analysis using tools like dplyr and recipes.

Exploratory Data Analysis (EDA): Various visualizations (e.g., GPA vs. Admission status) are generated to understand data distributions and relationships between features.

Model Building: Predictive models are built using Random Forest and XGBoost, and their performance is evaluated.

Model Interpretation: Feature importance and model performance metrics are analyzed to understand the factors influencing admission predictions.

Libraries Used:
tidyverse: Data manipulation and visualization

caret: Model training and evaluation

randomForest: Random Forest algorithm

xgboost: XGBoost algorithm

pROC: Performance evaluation with ROC curves

ggplot2: Data visualization

How to Run:

Clone the repository
git clone https://github.com/gudythecoder/Student-Admission-Prediction.git

Install necessary packages
install.packages(c("tidyverse", "caret", "randomForest", "xgboost", "vip", "pROC", "GGally"))

Run the R Markdown file to generate an HTML report
rmarkdown::render("admission.Rmd")
