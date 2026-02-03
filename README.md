# Revenue_and_customer_behviour_analytics


## 📌 Project Overview
This project analyzes revenue and customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  
The objective is to uncover insights related to **spending patterns, customer segmentation, product preferences, discounts, subscriptions, and shipping behavior** to support data-driven business decisions.

The analysis combines **Python (EDA & data preparation)**, **SQL (business querying)**, and **Power BI (interactive dashboarding)**.

---

## 📊 Dataset Summary
- **Total Records:** 3,900  
- **Total Features:** 18  
- **Data Types:**
  - Customer Demographics: Age, Gender, Location, Subscription Status
  - Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Behavioral Attributes: Discounts, Promo Codes, Previous Purchases, Purchase Frequency, Review Ratings, Shipping Type
- **Missing Values:**  
  - 37 missing values in `Review Rating` column

---

## 🧹 Data Preparation & Feature Engineering (Python)
The dataset was cleaned and prepared using **Python (pandas)** with the following steps:

- Imported and explored data using `df.info()` and `df.describe()`
- Handled missing values by **imputing median review ratings per product category**
- Standardized column names using **snake_case**
- Feature Engineering:
  - Created `age_group` by binning customer ages
  - Derived `purchase_frequency_days`
- Removed redundant columns (`promo_code_used`)
- Loaded cleaned data into **PostgreSQL** for SQL-based analysis

---

## 🧠 Business Analysis Using SQL
Structured SQL queries were used to answer key business questions:

1. **Revenue by Gender** – Compared total revenue across genders  
2. **High-Spending Discount Users** – Identified customers who used discounts but still spent above average  
3. **Top 5 Products by Rating** – Based on average review ratings  
4. **Shipping Type Comparison** – Average spend for Standard vs Express shipping  
5. **Subscribers vs Non-Subscribers** – Compared average spend and total revenue  
6. **Discount-Dependent Products** – Products with highest percentage of discounted purchases  
7. **Customer Segmentation** – Classified customers as New, Returning, or Loyal  
8. **Top Products per Category** – Most purchased items within each category  
9. **Repeat Buyers vs Subscriptions** – Analyzed subscription likelihood for repeat customers  
10. **Revenue by Age Group** – Identified highest revenue-contributing age segments  

---

## 📈 Power BI Dashboard
An interactive **Power BI dashboard** was created to visualize insights, including:

- Total customers and average purchase value
- Revenue and sales by product category
- Subscription distribution
- Revenue by age group
- Shipping type impact on spending
- Customer segmentation overview

The dashboard enables **dynamic filtering** and **business-friendly storytelling**.

---

## 💡 Key Insights
- Male customers generated higher total revenue than female customers
- Express shipping users showed higher average purchase values
- Subscribers contributed higher total revenue despite similar average spend
- Loyal customers formed the largest segment
- Certain products showed strong dependence on discounts
- Young adults contributed the highest overall revenue

---

## 📌 Business Recommendations
- **Boost subscriptions** by promoting exclusive subscriber benefits
- Introduce **customer loyalty programs** for repeat buyers
- Optimize **discount strategies** to protect margins
- Highlight **top-rated and best-selling products** in marketing campaigns
- Focus marketing efforts on **high-revenue age groups** and **express shipping users**

---

## 🛠 Tools & Technologies Used
- **Python:** pandas, numpy  
- **SQL:** PostgreSQL  
- **Data Visualization:** Power BI  
- **Database Integration:** Python → PostgreSQL  

---

## 🚀 How to Use This Project
1. Review Python scripts for data cleaning & feature engineering  
2. Explore SQL queries for business analysis  
3. Open the Power BI file to interact with the dashboard  
4. Use insights to support strategic business decisions  

---

## 📄 Author
**Pon Vishwesh**  
_Data Analytics | SQL | Python | Power BI_


