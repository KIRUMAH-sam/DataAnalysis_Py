📊 Data Analysis and Visualization Assignment
🎯 Objective

The purpose of this assignment is to:

Load and analyze a dataset using pandas in Python.

Perform basic exploratory data analysis (EDA).

Create simple but insightful visualizations using matplotlib and seaborn.

📂 Dataset

For this project, the Iris dataset was used.

It is a well-known dataset in machine learning and statistics, containing 150 observations of iris flowers.

Each observation has four numerical features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

A categorical feature, species, indicates whether the flower is Setosa, Versicolor, or Virginica.

📝 Tasks Completed
Task 1: Load and Explore the Dataset

Loaded the dataset using pandas.

Displayed the first few rows using .head().

Inspected data types and missing values.

Cleaned the dataset (dropped/fixed missing values if any).

Task 2: Basic Data Analysis

Computed summary statistics using .describe().

Grouped data by species and calculated mean values for numerical columns.

Identified interesting findings (e.g., Setosa has the smallest sepal and petal sizes).

Task 3: Data Visualization

Created four visualizations:

Line Chart – Petal length across observations.

Bar Chart – Average petal length per species.

Histogram – Distribution of sepal length.

Scatter Plot – Sepal length vs. petal length, color-coded by species.

All plots include titles, axis labels, and legends for clarity.

🔍 Findings & Observations

Setosa flowers have noticeably smaller petals and sepals compared to Versicolor and Virginica.

Petal length is a strong feature to distinguish between Setosa and the other two species.

The distribution of sepal length is centered around 5–6 cm.

The scatter plot shows clear separation between Setosa and the others, while Versicolor and Virginica slightly overlap.

⚙️ How to Run

Install the required libraries (if not already installed):

pip install pandas matplotlib seaborn scikit-learn


Open the Jupyter Notebook (.ipynb) or run the Python script (.py).

Run all the cells/commands to see the data exploration, analysis, and plots.

📌 Requirements

Python 3.8+

pandas

matplotlib

seaborn

scikit-learn
