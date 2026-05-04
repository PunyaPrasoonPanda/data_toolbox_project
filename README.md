📘 Oceanic Export Data Analysis Using Data Science
📌 Overview
This project focuses on analyzing export data to oceanic countries using Python. The main goal is to understand patterns in export value, identify relationships between quantity and value, and extract meaningful insights using data science techniques.

The project follows a complete pipeline starting from data cleaning and exploratory data analysis (EDA) to statistical testing and machine learning.

🎯 Objectives
To understand the structure and behavior of export data

To perform data cleaning and preprocessing

To identify outliers and patterns in export values

To analyze relationships between Quantity and Value

To apply statistical tests (T-test and Z-test)

To build a Simple Linear Regression model

To visualize insights using meaningful graphs

📂 Dataset
The dataset contains export records with the following attributes:

Country → Destination country

Commodity → Type of goods exported

Value → Export value ($)

Quantity → Quantity of goods

Date → Time of export

⚙️ Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

SciPy

🔍 Project Workflow
1. Data Loading
The dataset is loaded using pandas and inspected using:

head()

info()

describe()

2. Data Cleaning
Renamed columns for simplicity

Converted values to numeric format

Removed missing values

Extracted Year and Month from date

3. Exploratory Data Analysis (EDA)
Summary statistics

Outlier detection using IQR method

Distribution analysis

4. Statistical Analysis
T-test

Z-test

These tests help validate assumptions about export values.

5. Machine Learning
A Simple Linear Regression model is used to study the relationship between:

Independent Variable → Quantity

Dependent Variable → Value

6. Model Evaluation
R² Score

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

7. Visualizations
The project includes multiple meaningful visualizations:

Boxplot (Outlier detection)

Heatmap (Correlation)

Scatter plot (Relationship)

Regression plot

Histogram + KDE (Distribution)

Bar charts (Country comparison)

Pie chart (Export share)

Line plot (Yearly trend)

Area plot

Stacked area chart

📊 Key Insights
Export values are highly uneven with noticeable outliers

A positive relationship exists between Quantity and Value

A few countries dominate export performance

Export distribution is skewed

Market shows concentration in top-performing regions

🚀 Future Scope
Apply advanced machine learning models

Perform time-series forecasting

Build interactive dashboards using Power BI

Include more economic variables for deeper analysis

📌 Conclusion
This project demonstrates how data science techniques can be applied to real-world export data to extract meaningful insights. It highlights the importance of data cleaning, visualization, and modeling in understanding trade patterns.

👨‍💻 Author
Punya Prasoon Panda
