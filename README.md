# 🛍️ Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview

Customer Shopping Behavior Analysis is an end-to-end data analytics project that explores customer purchasing patterns, shopping preferences, and sales performance using **Python, SQL, and Power BI**.

The project follows a complete analytics workflow:

- Business Problem Understanding
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Database Integration
- Interactive Power BI Dashboard
- Business Recommendations

The objective is to transform raw customer transaction data into meaningful business insights that support data-driven decision-making.

---

# 🎯 Business Problem

Retail businesses collect vast amounts of customer transaction data but often struggle to transform it into actionable insights.

This project aims to answer key business questions such as:

- Who are the highest-value customers?
- Which customer segment contributes the most revenue?
- Which product categories perform best?
- How do discounts affect purchasing behavior?
- Does subscription status influence customer spending?
- Which age groups generate the highest revenue?
- What business strategies can improve customer retention?

---

# 📊 Dataset Overview

| Feature | Value |
|----------|------:|
| Total Transactions | 3,900 |
| Features | 18 |
| Missing Values | 37 |
| Average Purchase Amount | **$59.76** |
| Average Review Rating | **3.75** |

### Dataset Features

- Customer ID
- Age
- Gender
- Location
- Subscription Status
- Product Category
- Item Purchased
- Purchase Amount
- Review Rating
- Shipping Type
- Discount Applied
- Promo Code
- Previous Purchases
- Payment Method
- Season
- Purchase Frequency
- Size
- Color

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

# 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── README.md
├── Business Problem Document.pdf
├── Customer_behavior.pdf
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── Customer-Shopping-Behavior-Analysis.pptx
└── dashboard.png
```

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas
- Explored the dataset using `.info()` and `.describe()`
- Checked missing values
- Filled missing Review Ratings using the median rating grouped by product category
- Renamed columns using snake_case naming convention
- Removed redundant columns
- Created new features such as:
  - Age Group
  - Purchase Frequency
- Exported the cleaned dataset for further analysis
- Loaded the cleaned data into PostgreSQL for SQL analysis

---

# 📈 Exploratory Data Analysis (EDA)

The dataset was analyzed to identify patterns and customer behavior through:

### Customer Analysis

- Customer Distribution
- Subscription Status
- Gender Analysis
- Age Group Analysis

### Sales Analysis

- Revenue by Gender
- Revenue by Category
- Sales by Category
- Average Purchase Amount

### Product Analysis

- Top Rated Products
- Most Purchased Products
- Discount Usage
- Product Categories

### Shopping Behavior

- Shipping Preferences
- Purchase Frequency
- Review Ratings
- Previous Purchases

---

# 📊 Dashboard Features

An interactive Power BI dashboard was developed to visualize customer behavior and business performance.

### KPI Cards

- 👥 Total Customers
- 💰 Average Purchase Amount
- ⭐ Average Review Rating

### Dashboard Visualizations

- Revenue by Category
- Sales by Category
- Subscription Status Distribution
- Revenue by Age Group
- Previous Purchases by Age Group
- Customer Count by Subscription Status

### Interactive Filters

- Subscription Status
- Gender
- Product Category
- Shipping Type

---

# 📌 Key Insights

## Customer Insights

- Total Customers: **3,900**
- Average Purchase Amount: **$59.76**
- Average Review Rating: **3.75**

---

## Revenue Analysis

- Male customers generated significantly higher revenue than female customers.
- Non-subscribers contributed approximately **73%** of total customers and generated the majority of revenue.
- Subscribers represented approximately **27%** of the customer base.

---

## Customer Segmentation

Three customer segments were identified:

| Segment | Customers |
|----------|----------:|
| Loyal | 3,116 |
| Returning | 701 |
| New | 83 |

Loyal customers contribute the highest share of revenue and should be retained through loyalty programs.

---

## Age Group Analysis

Young Adults generated the highest revenue followed by:

- Middle-aged
- Adults
- Seniors

Revenue distribution was relatively balanced across age groups.

---

## Product Insights

### Highest Rated Products

- Gloves
- Sandals
- Boots
- Hat
- Skirt

### Most Discount-Dependent Products

- Hat
- Sneakers
- Coat
- Sweater
- Pants

---

# 💼 Business Recommendations

Based on the analysis:

### 🔔 Increase Subscription Membership

Introduce exclusive benefits and personalized offers to increase subscriber growth.

### 🎁 Improve Customer Loyalty

Reward repeat customers with loyalty points and discounts.

### 💰 Optimize Discount Strategy

Review heavily discounted products to improve profitability.

### 🎯 Target Marketing Campaigns

Focus promotions on high-value customer segments and top-performing age groups.

### ⭐ Promote High-Rated Products

Highlight highly rated products in advertisements and promotional campaigns.

---

# 📷 Dashboard Preview

> **Replace this section with your Power BI dashboard screenshot**

```markdown
![Customer Behavioral Dashboard](dashboard.png)
```

---

# 🚀 Skills Demonstrated

### Python

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering

### SQL

- Database Integration
- Data Querying
- Business Analysis

### Power BI

- Dashboard Design
- Interactive Visualizations
- KPI Development
- Slicers & Filters

### Data Analytics

- Customer Segmentation
- Business Intelligence
- Data Visualization
- Business Recommendations

---

# 📚 Learning Outcomes

This project strengthened my practical knowledge in:

- Python for Data Analysis
- Data Cleaning Techniques
- Exploratory Data Analysis (EDA)
- SQL Database Management
- Power BI Dashboard Development
- Customer Segmentation
- Business Intelligence
- Data Storytelling
- Data Visualization

---

# 📌 Future Improvements

- Build a Machine Learning model to predict customer purchase behavior.
- Deploy the dashboard using Power BI Service.
- Create automated ETL pipelines.
- Develop a recommendation system for personalized shopping.
- Perform sentiment analysis on customer reviews.

---

# 👨‍💻 Author

## Santhose Arockiaraj J

🎓 B.Tech – Artificial Intelligence & Data Science  
🏫 Saveetha Engineering College

### Connect with Me

- **GitHub:** https://github.com/Santhose-DOC
- **LinkedIn:** https://www.linkedin.com/in/santhose-arockiaraj-j

---

# ⭐ Support

If you found this project useful or interesting, consider giving it a ⭐ on GitHub.

---

## 📬 Feedback

Suggestions, improvements, and contributions are always welcome.

Feel free to fork the repository, raise an issue, or submit a pull request.

---

## 📄 License

This project is created for educational and portfolio purposes.

---

> **"Turning raw customer data into actionable business insights through Python, SQL, and Power BI."**