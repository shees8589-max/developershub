📦 Importing Required Python Libraries

Before building the heart disease prediction model, it is essential to import the required Python libraries. These libraries provide tools for data handling, visualization, machine learning, and model evaluation.

🐼 Pandas
import pandas as pd


Purpose:
Pandas is used for data manipulation and analysis. It allows us to load datasets, clean data, handle missing values, and perform statistical operations.

Key Uses in This Project:

Load the heart disease dataset from CSV

Handle missing values

Select features and target variable

Perform basic data inspection

📌 Example Use:

pd.read_csv("heart.csv")

🔢 NumPy
import numpy as np


Purpose:
NumPy is used for numerical computations and handling arrays efficiently.

Key Uses in This Project:

Numerical operations

Supporting mathematical computations in ML models

Efficient array handling

📌 NumPy works in the background for most machine learning operations.

📊 Matplotlib
import matplotlib.pyplot as plt


Purpose:
Matplotlib is used for data visualization.

Key Uses in This Project:

Plot ROC curve

Visualize confusion matrix

Display graphs and charts

📌 Example:

plt.plot(x, y)
plt.show()

🎨 Seaborn
import seaborn as sns


Purpose:
Seaborn is built on top of Matplotlib and is used for advanced and attractive statistical visualizations.

Key Uses in This Project:

Count plots

Heatmaps

Boxplots

Confusion matrix visualization

📌 Seaborn helps in Exploratory Data Analysis (EDA).

🤖 Scikit-Learn (Machine Learning Library)

Scikit-Learn is used to build, train, and evaluate machine learning models.

🔀 Train-Test Split
from sklearn.model_selection import train_test_split


Purpose:
Splits the dataset into:

Training set (used to train the model)

Testing set (used to evaluate performance)

📌 Helps prevent overfitting.

⚖️ Standard Scaler
from sklearn.preprocessing import StandardScaler


Purpose:
Standardizes features so that all values have:

Mean = 0

Standard deviation = 1

📌 Why needed?
Logistic Regression performs better when features are on the same scale.

🧠 Logistic Regression
from sklearn.linear_model import LogisticRegression


Purpose:
Used to build a binary classification model.

In This Project:

Predicts whether a patient has heart disease (0 or 1)

Widely used in medical diagnosis problems

📌 Produces probability-based predictions.

📈 Model Evaluation Metrics

These metrics help evaluate how well the model performs.

✔ Accuracy Score
from sklearn.metrics import accuracy_score


Purpose:
Measures the percentage of correct predictions.

📌 Simple and easy to understand but not always sufficient for medical data.

🔲 Confusion Matrix
from sklearn.metrics import confusion_matrix


Purpose:
Shows:

True Positives

True Negatives

False Positives

False Negatives

📌 Very important in medical diagnosis to detect missed cases.

📉 ROC Curve & AUC
from sklearn.metrics import roc_curve, roc_auc_score


Purpose:

ROC Curve: Shows trade-off between sensitivity and specificity

AUC: Measures overall classification performance

📌 Higher AUC = Better model

🧠 Summary Table
Library	Purpose
Pandas	Data loading & cleaning
NumPy	Numerical computations
Matplotlib	Plotting graphs
Seaborn	Statistical visualizations
Scikit-Learn	Machine learning & evaluation
📝 One-Line Exam Explanation

Required libraries were imported to perform data preprocessing, visualization, machine learning model training, and evaluation for heart disease prediction.
