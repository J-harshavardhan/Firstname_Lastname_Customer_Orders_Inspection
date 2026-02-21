📊 Customer Orders Inspection
📌 Project Overview

This project performs structural inspection and statistical analysis on an e-commerce dataset (orders.csv) from an online electronics store.

The analysis was completed using Python (Pandas) in Google Colab.

📂 Dataset Description

The dataset contains order records with the following columns:

Column Name	Description
order_id	Unique order identifier
customer_name	Name of the customer
product	Product ordered
quantity	Number of units ordered
unit_price	Price per unit in INR
order_date	Date the order was placed
status	Current order status
========================================================================================
✅ Tasks Completed
------------------------
🔹 Task 1 – Data Loading
--------------------------------
Loaded dataset from Google Drive

Set order_id as the index

Displayed first 5 and last 5 rows
==============================================
🔹 Task 2 – Structural Inspection
-----------------------------------
Dataset contains 20 rows and 6 columns

Missing values detected:

quantity → 4 missing values

order_date → 4 missing values

Converted order_date from object to datetime format using:

pd.to_datetime(df['order_date'])
==============================================
🔹 Task 3 – Statistical Summary
----------------------------------
Generated summary statistics using df.describe()

Median unit_price: ₹2,500

Mean unit_price: ₹20,224.60

Identified right-skewed distribution due to high-value outliers (maximum ₹85,000)
======================================================================================
📈 Key Insights
-----------------
The dataset has minor missing values.

unit_price distribution is positively skewed.

A few high-value orders significantly increase the mean price.
=====================================================================================
🛠 Tools Used

Python

Pandas

Google Colab

GitHub
====================================================================================
📎 Repository Contents
Customer-Orders-Inspection/
│
├── Firstname_Lastname_Assignment.ipynb
└── README.md
======================================================================================
👨‍💻 Author
J-Harshavardhan
