# Binary Classification using Logistic Regression

## What does this project do?
This project predicts whether a student will Pass or Fail based on the number of hours they studied using a Logistic Regression model.

## Features used
- Hours Studied

## Libraries used
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How it works
1. Created a dataset with hours studied and pass/fail outcomes
2. Trained a Logistic Regression model on the data
3. Predicted pass/fail outcome and probability for new students
4. Evaluated the model using a Classification Report
5. Plotted the Sigmoid curve to visualize the decision boundary
6. Plotted a Confusion Matrix to visualize model performance

## How to run
1. Install libraries:
   ```
   pip install numpy matplotlib seaborn scikit-learn
   ```
2. Run `logistic_regression_for_binary_classification.py`

## Sample Output
- A student who studied 5.5 hours → Pass with 88% confidence
- Decision boundary at 0.5 probability threshold

## Key Concepts Covered
- Logistic Regression for binary classification
- Sigmoid function and probability prediction
- Decision boundary
- Precision, Recall and F1 Score
- Confusion Matrix
