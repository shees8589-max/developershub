📦 Importing Data Analysis and Visualization Libraries

In this project, Python libraries are imported to analyze medical data and visualize patterns related to heart disease. These libraries play a crucial role in understanding the dataset before applying machine learning models.

🐼 Pandas
import pandas as pd


Purpose:
Pandas is a powerful Python library used for data loading, cleaning, and manipulation.

Role in This Project:

Load the heart disease dataset from a CSV file

Handle missing values

Select and filter columns

Perform statistical analysis

📌 Why Pandas?
Medical datasets are usually structured in tabular form, and Pandas makes it easy to work with such data.

📊 Matplotlib
import matplotlib.pyplot as plt


Purpose:
Matplotlib is used for basic plotting and data visualization.

Role in This Project:

Plot graphs such as ROC curve

Display trends and comparisons

Visualize results of model evaluation

📌 Matplotlib provides full control over plot appearance.

🎨 Seaborn
import seaborn as sns


Purpose:
Seaborn is a high-level visualization library built on top of Matplotlib. It is mainly used for statistical graphics and EDA (Exploratory Data Analysis).

Role in This Project:

Create count plots for target variable

Generate box plots for age vs heart disease

Draw correlation heatmaps

Visualize confusion matrix

📌 Seaborn makes plots cleaner, more informative, and visually appealing.

🔍 Why Visualization is Important in Medical Data

Helps understand patterns and trends

Identifies risk factors for heart disease

Detects outliers and imbalance

Supports better clinical interpretation

🧠 Summary Table
Library	Main Use
Pandas	Data handling & preprocessing
Matplotlib	Basic plotting
Seaborn	Advanced statistical visualization
📝 One-Line Exam Explanation

Pandas was used for data manipulation, while Matplotlib and Seaborn were used to visualize trends and patterns in the heart disease dataset.
