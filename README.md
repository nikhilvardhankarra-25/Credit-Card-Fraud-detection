# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning classification algorithms.

The main objective is to classify transactions as legitimate or fraudulent.

## Algorithms Used
- Logistic Regression
- Random Forest Classifier

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset
The project uses a credit card transaction dataset containing 284,807 transactions and 31 columns.

The target column is `Class`:
- 0 – Legitimate transaction
- 1 – Fraudulent transaction

## Project Workflow
1. Importing required libraries
2. Loading the dataset
3. Exploring and inspecting the data
4. Checking missing values
5. Analyzing class distribution
6. Separating features and target
7. Feature scaling using StandardScaler
8. Splitting the dataset into training and testing sets
9. Training Logistic Regression
10. Training Random Forest
11. Evaluating both models
12. Comparing model performance using graphs and confusion matrices

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Visualizations
- Legitimate vs Fraudulent Transaction Distribution
- Model Performance Comparison
- Logistic Regression Confusion Matrix
- Random Forest Confusion Matrix

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries.
3. Place `creditcard.csv` in the notebook's working directory.
4. Open `Credit_Card_Fraud_Detection.ipynb`.
5. Run the notebook cells in order.

## Conclusion
In this project, two Machine Learning algorithms, Logistic Regression and Random Forest, were implemented to detect fraudulent credit card transactions.
Both models were evaluated using Accuracy, Precision, Recall, and F1 Score.
The results showed that Random Forest performed better than Logistic Regression.

**Model Performance:**

- Logistic Regression F1 Score: 72.41%
- Random Forest F1 Score: 87.43%
- 
Random Forest achieved an accuracy of 99.96%, precision of 94.12%, and recall of 81.63%.
Therefore, Random Forest was selected as the better-performing model for this project.
This project demonstrates how Machine Learning can help identify fraudulent credit card transactions.
**Project Type:** Machine Learning – Binary Classification
