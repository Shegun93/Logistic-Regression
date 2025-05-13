## Logistic Regression for Cancer Classification
# Overview
This project implements a logistic regression model to classify cancer data. The model is trained on a dataset to predict whether a tumor is malignant or benign based on various features. The implementation includes data preprocessing, model training, and evaluation using a confusion matrix and accuracy score.

## Features
- Data Preprocessing: The dataset is split into training and test sets, and feature scaling is applied to standardize the data.
- Model Training: A logistic regression model is trained on the preprocessed data.
- Evaluation: The model's performance is evaluated using a confusion matrix and accuracy score, achieving an accuracy of approximately 94.74%.
## Requirements
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
## Installation
1. Clone the repository
   ```
   git clone https://github.com/Shegun93/Logistic-Regression.git
   ```
2. Navigate to the project directory
   ```
   cd Logistic-Reqression
   ```
3. Install the required libraries
   ```
   pip install pandas numpy matplotlib sklearn
   ```
## Usage
```
jupyter notebook Cancer.ipynb
```
Run each cell in the notebook sequentially to preprocess the data, train the model, and evaluate its performance.
Results
The model achieves an accuracy of 94.74% on the test set. Below is the confusion matrix:

|                | Benign | Malignant |
|----------------|-------------------|----------------------|
| **Actual: Benign**     | 103               | 4                    |
| **Actual: Malignant**  | 5                 | 59                   |


|                   | Predicted
|-------------------|
|
