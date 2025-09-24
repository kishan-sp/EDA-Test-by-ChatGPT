# 🧠 The Scenario
You’re a Data Scientist for an online food delivery startup. Your boss just dumped raw CSV files on your desk and wants “insights by Monday” (classic corporate move, right? 😅).
Your job: Clean, merge, explore, and produce actionable insights — no excuses.

# 📂 The Data

You have three CSV files:
1. customers.csv
- customer_id (unique)
- name
- signup_date
- city
- age
- gender

2. orders.csv
- order_id (unique)
- customer_id
- restaurant_name
- order_date
- order_amount
- payment_method

3. restaurants.csv
- restaurant_id (unique)
- restaurant_name
- cuisine_type
- rating
- city

# 🎯 Your Task Requirements

You must solve and present the following steps:

## 1. Data Wrangling

Load all 3 datasets into Pandas.
Check for missing values and decide how to handle them (justify your choice).
Identify and remove duplicate entries.
Standardize date formats (YYYY-MM-DD).
Ensure data types are correct (e.g., order_amount as numeric).
Handle inconsistent naming in city and restaurant_name columns (e.g., "mumbai" vs "Mumbai").

## 2. Data Merging

Merge orders with customers on customer_id.
Merge that with restaurants on restaurant_name.
The final dataset should have all customer, order, and restaurant info in one DataFrame.

## 3. Exploratory Data Analysis (EDA)

Perform at least 8 different EDA tasks, including:
Distribution of customers by city.
Top 5 restaurants by total revenue.
Average order value by cuisine type.
Payment method usage distribution.
Monthly order trends (line chart).
Age group analysis (e.g., <25, 25-40, 40+) vs average order amount.
Correlation between restaurant ratings and order amount.
Outlier detection in order_amount.

## 4. Visualization Requirements

Use Matplotlib/Seaborn.
Make at least 5 clear, well-labeled plots.
Use meaningful color palettes and titles (no “Plot 1” type titles 😜).

## 5. Insights & Reporting

Write 5–7 business insights from your analysis.
Suggest 2 actionable recommendations to improve revenue or customer satisfaction.
Keep the tone as if you’re presenting to management — clear, concise, and backed by data.

# Time Limit
You have 4 hours for the analysis (as if this was a real test),
but if you want to simulate real corporate chaos, pretend you have 2 hours.
