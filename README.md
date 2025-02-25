# Predicting-Term-Deposit-Subscriptions-Using-Decision-Tree-Analysis
Project Overview
This project aims to predict client subscription to term deposits using a decision tree classification model. By analyzing a comprehensive bank marketing dataset, this project identifies key predictors of client behavior, offering insights to enhance targeted marketing strategies. The dataset includes various demographic and financial attributes derived from previous marketing campaigns.


Dataset
The dataset used in this project is collected from multiple marketing campaigns conducted by a bank. It includes the following key variables:

Age: Age of the client.
Job: Type of job.
Marital: Marital status.
Education: Level of education.
Balance: Average yearly balance in euros.
Housing Loan: Housing loan status.
Personal Loan: Personal loan status.
Previous Contact Outcomes: Results from previous marketing campaigns.
Subscription Status: Whether the client subscribed to a term deposit.

Analysis Methodology

Data Exploration: Initial exploration includes reviewing data distributions, correlations, and segmenting client profiles to identify patterns.
Preprocessing: Handling missing values, encoding categorical variables, and feature engineering to prepare data for modeling.
Modeling: Applying a decision tree classification model to predict subscription likelihood, with hyperparameter tuning for optimal performance.
Evaluation: Assessing model performance using accuracy, precision, recall, and F1-score, and visualizing results with a confusion matrix.

Results
The decision tree model achieved an accuracy of 86.19%, with key predictors including previous contact outcomes, client balance, and education level. These insights support data-driven marketing strategies for improving client engagement and campaign effectiveness.
Installation and Usage
Prerequisites

Python 3.x
Required Python libraries: pandas, numpy, scikit-learn, matplotlib

Clone the repository:bash  Copy codegit clone https://github.com/FabcanK6/bank-marketing-analysis.git

License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Thanks to the UCI Machine Learning Repository for providing the bank marketing dataset.
Special thanks to all contributors who have helped improve this project.
