Customer Churn Analysis (EDA)
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a Customer Churn dataset to identify the major factors influencing customer churn. The analysis helps businesses understand customer behavior and improve customer retention strategies.

The project includes:

Data Cleaning & Preprocessing
Handling Missing Values
Exploratory Data Analysis (EDA)
Data Visualization
Business Insights Generation
📂 Dataset Information

The dataset contains customer-related information such as:

Customer tenure
Monthly charges
Contract type
Payment method
Total charges
Churn status

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
🔍 Steps Performed
1. Data Loading
Imported the dataset using Pandas.
Checked dataset structure and summary statistics.
2. Data Cleaning
Converted data types into proper formats.
Handled missing values in TotalCharges.
Converted categorical churn values (Yes/No) into numeric values (1/0).
3. Exploratory Data Analysis (EDA)

Performed analysis on:

Churn Rate
Contract Type vs Churn
Payment Method vs Churn
Monthly Charges vs Churn
Tenure vs Churn
4. Data Visualization

Created visualizations using Matplotlib and Seaborn:

Count Plots
Histograms
Boxplots
Correlation Heatmap
📊 Key Insights
Customers with month-to-month contracts have higher churn rates.
Customers with high monthly charges are more likely to churn.
Customers with low tenure are at greater risk of leaving.
Certain payment methods show higher churn patterns.
🎯 Project Outcome

This project helps in identifying high-risk customers and provides insights that can support better business decisions to improve customer retention and reduce churn.

🚀 Future Improvements
Build Machine Learning models for churn prediction.
Create an interactive dashboard using Power BI or Streamlit.
Perform advanced feature engineering.
📁 Project Structure
Customer-Churn-EDA/
│
├── churn.csv
├── Customer_Churn_EDA.ipynb
├── README.md
└── requirements.txt
