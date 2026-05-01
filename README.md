This repository contains two key projects: 
Project 1: Monthly Sales Trends and Analysis ,
Project 2: Exploratory Data Analysis (EDA) on Titanic Dataset  and
Project 3: Sales Predictions Using Basic Models


*** Project 1: Monthly Sales Trends and Analysis

## Project Overview 
In this project, we take a closer look at an online retail dataset to understand the sales trends over time, customer behavior, and product performance. 
The goal is to help businesses understand how their products are doing and how customers interact with them. By analyzing key data such as product prices,
ratings, and discount percentages,we can identify what drives sales and revenue. We use Python for data cleaning, analysis, 
and visualizations to uncover patterns.
## Business Objectives 
- Track sales performance over time: Identify months with high or low sales and detect seasonal trends.
- Examine customer purchasing behavior: Analyze which products are more popular and how customer reviews and ratings impact sales.
- Highlight top-performing products and sellers: Find out which products and sellers contribute the most to sales.
- Measure revenue from different payment methods: See how installment payments or other payment types influence total revenue.
- Generate actionable insights: Offer strategies for businesses to increase sales, improve customer loyalty, and boost revenue.
## Dataset Information 
The dataset used in this project includes the following columns:
product_id: A unique identifier for each product.
product_name: The name of the product.
category: The category the product belongs to (e.g., Electronics, Clothing, etc.).
discounted_price: The price after a discount has been applied.
actual_price: The original price before any discounts.
discount_percentage: The percentage of the discount applied.
rating: Customer rating of the product.
rating_count: The number of reviews or ratings for the product.
about_product: A brief description of the product.
user_id: The ID of the customer who provided a review.
user_name: The name of the customer who provided a review.
review_id: Unique ID for the review.
review_title: The title of the review.
## Tools & Technologies 
Python:
- **Pandas**: Used for data manipulation and cleaning.
- **Matplotlib and Seaborn**: For visualizing trends, correlations, and distributions.
- **Jupyter Notebooks**: Used to run all analyses interactively.
## Key Insights 
- High-performing categories: Categories like Health & Beauty and Watches generate the most revenue.
- Customer retention: Around 30-35% of customers return, showing there’s room for loyalty programs to improve engagement.
- Installment payments: Nearly 49% of customers prefer installment payment options, indicating flexibility is key.
- Product price & purchase frequency: Interestingly, price has a very weak correlation with how often customers purchase, suggesting that price
isn’t always the main factor driving frequency.
- Revenue contribution from top sellers: A small number of sellers contribute the most to overall revenue, highlighting the importance of key sellers.
## Business Impact 
- Helps identify the top-performing products and best-selling sellers, allowing businesses to focus on them for future growth.
- Provides insights to help businesses optimize pricing strategies, considering the impact of discounts and installment options.
- Helps businesses focus on improving customer retention and loyalty programs by targeting the 30-35% of repeat customers.
- Helps with inventory management, ensuring that high-performing products and categories are prioritized.
## Conclusion 
This project shows how using data analysis and visualization can help businesses understand their product performance, customer purchasing habits, 
and payment preferences. With this information, companies can make informed decisions to improve sales,
customer satisfaction, and revenue.


*** Project 2: Exploratory Data Analysis (EDA) on Titanic Dataset

## Project Overview 
This project explores the Titanic dataset, focusing on factors that may have influenced a passenger's survival rate. We perform Exploratory 
Data Analysis (EDA) to identify patterns and relationships in the data, like how age, class, gender, and family size affected survival. The goal
is to understand these relationships and generate insights for predictive modeling.
## Business Objectives 
- Understand survival rates by different features: Find out how Pclass, Age, Sex, and FamilySize affected survival.
- Handle missing data: Address missing values in the data and clean it for analysis.
- Visualize relationships: Create charts to better understand how different features are related to survival.
- Identify key features: Identify which features are most important in predicting survival chances.
## Dataset Information 
The Titanic dataset includes the following columns:
PassengerId: Unique ID for each passenger.
Survived: 1 if the passenger survived, 0 if not.
Pclass: Passenger class (1st, 2nd, 3rd).
Name: Name of the passenger.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard.
Parch: Number of parents/children aboard.
Ticket: Ticket number.
Fare: Fare paid by the passenger.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
## Tools & Technologies 
- **Python** (Pandas, Matplotlib, Seaborn) for data analysis and visualization.
- **Jupyter Notebooks** for performing the analysis and generating insights interactively.
## Key Insights 
- Females had a significantly higher survival rate compared to males.
- First Class passengers had the highest survival rate.
- Younger passengers and children were more likely to survive.
- Higher fare passengers, especially in First Class, had better survival chances.
- Cherbourg passengers had a higher survival rate compared to other embarkation points.
- Family size (based on SibSp and Parch) had an impact on survival chances.
## Business Impact 
- Helps businesses understand how features like gender, class, and family size might influence survival or customer outcomes.
- Provides insights for predictive models to estimate survival based on passenger characteristics.
- Useful for designing customer segmentation strategies or even emergency response plans based on historical data.
## Conclusion 
This project demonstrates how EDA on the Titanic dataset can provide insights into the factors influencing survival. By analyzing 
relationships between features and using visualizations, we can identify key factors that affected survival, which can be applied to
predictive modeling or other 
data-driven initiatives.


*** Project3: Sales Predictions Using Basic Models

## Project Overview 
This project predicts future sales for a company using historical data and trends. The goal is to forecast sales for the next months (September to December) based on the existing sales data and trends observed in the first 8 months of 2024.
## Tools Used
- **Excel** for data analysis and chart creation
- **TREND Function** for sales prediction
- **Pivot Table** for aggregating sales data
- **Line Chart** with Trendline for visualizing trends
## Dataset
The dataset consists of historical sales data for **2024**. It includes:
- **Month**: The month number (1-8 for actual, 9-12 for predicted sales)
- **Total Sales**: The total sales value for each month.
## Key Insights
- **Sales trend** is declining, as shown by the downward slope of the trendline.
- **Predicted sales** for September to December are also showing a downward trend.
## Business Recommendations
- Increase **marketing efforts** and **promotions** during months with low sales predictions.
- Adjust **inventory levels** based on forecasted demand for the next months.
- Revisit **pricing strategies** to boost sales, especially in months with declining predictions.
  ## Conclusion
The sales trend analysis provides actionable insights for adjusting marketing, inventory, and pricing strategies to maximize sales and minimize loss in declining months.
