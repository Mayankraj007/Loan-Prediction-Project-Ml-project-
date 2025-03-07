# Loan Prediction Project: A Machine Learning Approach
<br>
The Loan Prediction Project aims to automate the process of determining a customer’s loan eligibility based on a set of provided attributes. Using two datasets — a training set (train_ctrUa4K.csv) and a testing set (test_lAUu6dG.csv) — the project builds a predictive model to classify loan approvals (Loan_Status). The training dataset contains 12 independent features, including both categorical (Gender, Education, Property Area) and numerical variables (Applicant Income, Loan Amount, Credit History), with the target variable indicating loan approval status.
<br>
The goal was to use this data to build a model that can predict loan approvals for new applicants.

Before building the model, we cleaned and prepared the data by filling in missing values and converting text-based categories into numbers so they could be understood by machine learning algorithms. We also created new features, like total income, and adjusted the loan amount data to reduce any imbalance. By analyzing the data visually, we discovered important patterns — for example, applicants with a good credit history were more likely to have their loans approved.

We tested several machine learning methods like Logistic Regression, Decision Trees, and Random Forests to find the best approach. We evaluated how well each model performed by measuring their accuracy and other factors like precision and recall. We also fine-tuned the models to improve their performance and made predictions on the test data.

This project shows the complete process of using machine learning to solve a real-world problem. It simplifies loan approval decisions by automating predictions, saving time for banks and reducing human error. By sharing this work on GitHub, we hope it can help others learn about building and improving predictive models.
