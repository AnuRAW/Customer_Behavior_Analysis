# 🛒 Customer Shopping Behavior Analysis – Data Analytics Project
## 📌 Project Description
This project analyzes customer shopping behavior using a transactional dataset of 3,900 purchases across multiple product categories.
The dataset includes customer demographics, purchase details, discount usage, subscription status, and shipping preferences.

The goal of this project is to uncover spending patterns, customer segments, product preferences, and subscription trends to support data-driven business decisions.
Analysis was performed using Python, SQL (PostgreSQL), and Power BI.

---

#📊 Key Insights & Analysis
###🔹 Customer Performance

-📊 Revenue distribution by Gender
-🧑‍🤝‍🧑 Customer segmentation into New, Returning, and Loyal
-📈 Revenue contribution by Age Group

#🔹 Product & Category Analytics
-⭐ Top 5 products by average review rating
-🛍️ Top 3 most purchased products per category
-🎯 Identification of discount-dependent products

#🔹 Discounts & Subscription Behavior
-💸 High-spending customers who still used discounts
-🔄 Comparison of Subscribers vs Non-Subscribers
-📉 Impact of discounts on purchase behavior

#🔹 Shipping & Purchase Trends
-🚚 Average purchase value comparison between Standard vs Express shipping
-🔁 Relationship between repeat purchases and subscription likelihood
-📦 Purchase frequency patterns

---

##📁 Dataset Features
**Total Records: 3,900
Total Columns: 18**
- Key Columns:
- Customer Age, Gender, Location
- Subscription Status
- Item Purchased, Category
- Purchase Amount, Season, Size, Color
- Discount Applied
- Previous Purchases, Purchase Frequency
- Review Rating
- Shipping Type

---

##📌 Data Quality & Constraints
 -⚠️ 37 missing values in the Review Rating column
 -✅ Missing values imputed using median rating per product category
 -🔍 Redundant column (promo_code_used) identified and removed
 -📐 Column names standardized using snake_case
 -🐍 Exploratory Data Analysis (Python)
 -Data loading and exploration using pandas
 -Summary statistics using df.describe()

**Feature engineering:
 -age_group
 -purchase_frequency_days
 -Data validation and consistency checks
 -Cleaned dataset loaded into PostgreSQL for SQL analysis
**
---

##🗄️ SQL Analysis (PostgreSQL)
  -SQL queries were used to answer business-focused questions such as:
  -Revenue by customer gender
  -Spending behavior of discount users
  -Subscription impact on total revenue
  -Product-level performance and ratings
  -Repeat buyers vs subscription adoption

---

##📈 Power BI Dashboard
  -An interactive Power BI dashboard was created to visualize:
  -Revenue trends
  -Customer segmentation
  -Product performance
  -Discount usage
  -Subscription impact
  -The dashboard enables stakeholders to quickly identify patterns and actionable insights.

---

##💡 Business Recommendations
#📢 Boost Subscriptions
    -Promote exclusive offers and benefits for subscribers
#🎁 Customer Loyalty Programs
    -Reward repeat buyers to move them into the Loyal segment
#💰 Review Discount Strategy
    -Balance discount usage with profit margins
#🛍️ Product Positioning
    -Highlight top-rated and best-selling products
#🎯 Targeted Marketing
    -Focus on high-revenue age groups and express-shipping customers

---

##🛠 Tools Used
  -Python (Pandas, NumPy)
  -PostgreSQL
  -SQL
  -Power BI

---

##📂 Files Included 
  -dataset.csv – Cleaned customer shopping dataset
  -sql_queries.sql – Business analysis queries
  -PowerBI_Dashboard.pbix – Interactive dashboard
  -README.md – Project documentation

---

##✅ Key Learnings
  -End-to-end data analytics workflow
  -Data cleaning and feature engineering
  -Writing business-focused SQL queries
  -Building interactive Power BI dashboards
  -Translating data insights into business recommendations

---

##🙋‍♂️ Credits
 --Data analysis, dashboard, and insights by Anurag Rawat

##📬 Connect with Me
--LinkedIn: (https://www.linkedin.com/in/anurag-rawat-b78399208)

---

⭐ If you like this project, give it a star!
