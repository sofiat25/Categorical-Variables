Handling Categorical Variables in Machine Learning

This project explores how to effectively handle categorical features in machine learning workflows using scikit-learn. It showcases different encoding techniques—Ordinal Encoding and One-Hot Encoding—and compares their impact on model performance.

Overview

Dataset: Ames Housing Dataset

Goal: Evaluate and compare encoding strategies for categorical variables to enhance prediction accuracy and robustness.

Key Steps:

Identify and separate categorical features.

Apply Ordinal Encoding for ordinal categories.

Apply One-Hot Encoding for nominal categories.

Build and evaluate a Random Forest Regressor with each encoding approach.

Compare results using Mean Absolute Error (MAE).

Technologies Used

Python 3

pandas – Data manipulation

scikit-learn – Preprocessing, Encoding, Random Forest

Jupyter Notebook / Kaggle – Development platform

File Structure
exercise-categorical-variables.ipynb   ← Main notebook implementing categorical encoding and evaluation

How to Run

Clone the repository:

git clone https://github.com/your-username/categorical-variables-exercise.git
cd categorical-variables-exercise


Install dependencies:

pip install pandas scikit-learn


Launch the notebook:

jupyter notebook exercise-categorical-variables.ipynb

Results

The model using One-Hot Encoding demonstrated better performance (lower MAE) compared to Ordinal Encoding, highlighting its effectiveness with nominal categorical data.

Links

## 📎 Links  
- [Dataset on Kaggle](https://www.kaggle.com/c/home-data-for-ml-course)  
- [Kaggle Notebook: Categorical-Variables](https://www.kaggle.com/code/sofiagt25/exercise-categorical-variables)  
- [Course: Intermediate Machine Learning](https://www.kaggle.com/learn/intermediate-machine-learning)  
