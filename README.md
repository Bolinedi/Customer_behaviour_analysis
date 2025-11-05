🧠 Customer Shopping Behavior Analytics Project
🔍 Overview

This project explores and analyzes a Customer Shopping Behavior dataset to uncover insights into customer demographics, purchasing trends, and spending patterns.
It demonstrates a full data analytics pipeline — including data loading, cleaning, exploratory analysis in Python, SQL query execution in MySQL, and visualization through an interactive Power BI dashboard.
The goal is to provide a comprehensive view of how different factors (age, gender, category, discounts, etc.) influence customer purchasing behavior.

🧾 Dataset

Name: customer_shopping_behavior.csv

Source: Kaggle – Customer Shopping Behavior Dataset

Records: 3,900 rows × 18 columns

Description: Contains detailed shopping activity data including demographics, item details, payment preferences, and review ratings.

Key Columns
Column	Description
Customer ID	Unique customer identifier
Age	Age of the customer
Gender	Gender of the customer
Item Purchased	Product name or type
Category	Product category (e.g. Clothing, Footwear, Accessories)
Purchase Amount (USD)	Purchase value in USD
Location	Customer’s region/state
Season	Season when purchase was made
Review Rating	Customer rating (1–5 scale)
Subscription Status	Indicates if the customer is subscribed
Discount Applied	Whether a discount was used
Promo Code Used	Whether a promo code was used
Payment Method	Payment type (Credit Card, PayPal, etc.)
Frequency of Purchases	Frequency of purchases (Weekly, Monthly, etc.)
🛠 Tools & Technologies
Tool / Language	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	Data cleaning, transformation, and exploratory data analysis (EDA)
MySQL	Running analytical SQL queries on the cleaned data
Power BI	Building interactive dashboards and visual reports
Jupyter Notebook / VS Code	Development and documentation
⚙️ Project Steps
1. Data Loading & Exploration

Loaded dataset using Pandas

Reviewed column data types, checked for missing values (Review Rating had 37 nulls)

Performed summary statistics and initial visual exploration

2. Data Cleaning

Handled missing Review Rating values using median imputation

Removed duplicates and standardized categorical values

Extracted new features such as:

Age Group (e.g., 18–25, 26–35, etc.)

Spending Category (based on Purchase Amount)

3. SQL Analysis

Imported the cleaned dataset into a MySQL server

Executed SQL queries for analytical insights, such as:

Top 5 high-spending customers by purchase amount

Most popular product categories by gender

Average review rating by location and season

Payment method trends and their correlation with discounts

4. Power BI Dashboard

Connected Power BI to MySQL database

Designed an interactive dashboard to visualize:

Total and average purchase amount by category and location

Spending behavior by age group and gender

Effect of discounts and promo codes on purchase value

Review ratings and seasonal patterns

5. Reporting & Insights

Created a concise Power BI report summarizing customer patterns

Highlighted actionable insights and business recommendations

📊 Dashboard

The Power BI Dashboard includes:

KPI Cards: Total Revenue, Average Rating, Customer Count

Bar Charts: Spending by Category and Gender

Pie Charts: Payment Method distribution

Line Charts: Seasonal sales trends

Filters: Age group, Gender, and Location

(You can include a screenshot or link here once the dashboard is built.)
