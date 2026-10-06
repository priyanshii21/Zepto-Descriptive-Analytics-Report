# 🛒 Zepto Sales Data Analysis

## 📌 Project Overview

This project performs **Descriptive Data Analytics on Zepto sales data** to understand product demand, revenue performance, category contribution, city-wise performance, discount impact, pricing, Average Order Value (AOV), and influencer-marketing activity.

The analysis is based on **300 product-city records**, covering **10 products, 6 categories, and 6 Indian metro cities**. Since the dataset does not contain a date/time field, the analysis focuses on cross-sectional comparisons rather than time-based trends.

## 🎯 Business Questions

* Which products generate the highest number of orders?
* Which products generate the highest revenue?
* Which categories contribute the most revenue?
* Which cities are performing the best?
* How does category demand differ across cities?
* Does discounting increase orders or revenue?
* Is influencer marketing associated with higher sales?
* Which categories have the highest Average Order Value (AOV)?
* Which product-city combinations perform best and worst?

## 🗂️ Dataset

The dataset contains sales information for:

* **300 product-city records**
* **10 SKUs**
* **6 categories**

  * Snacks
  * Grocery
  * Beverages
  * Dairy
  * Instant Food
  * Confectionery
* **6 cities**

  * Delhi
  * Mumbai
  * Bangalore
  * Chennai
  * Hyderabad
  * Pune

## 🛠️ Tools & Technologies

* **Microsoft Excel** – Data analysis and calculations
* **SQL** – Data querying and analysis
* **Power BI** – Data visualization and dashboarding
* **Python** – Potential future predictive analysis
* **GitHub** – Project documentation and portfolio

## 📊 Key KPIs

| Metric                |         Result |
| --------------------- | -------------: |
| Total Orders          |         50,446 |
| Total Revenue         |    ₹57.83 Lakh |
| Blended AOV           |        ₹114.64 |
| Average Discount      |          4.92% |
| Top Category          |         Snacks |
| Top City              |      Hyderabad |
| Top Product by Orders |   Coca Cola 1L |
| Influencer Activity   | 30% of records |

## 🔍 Key Insights

### 🥤 Product Performance

**Coca Cola 1L** was the highest-performing product by order volume with **6,175 orders**.

It was also the highest revenue-generating product, contributing approximately **₹7.15 lakh**.

### 🍿 Category Performance

**Snacks** was the leading revenue category, contributing approximately **29.6%** of total revenue.

The top three categories — **Snacks, Beverages, and Grocery** — together contributed around **67.3%** of total revenue.

### 📍 City Performance

**Hyderabad** was the strongest city by both orders and revenue.

* Revenue: approximately **₹12.51 lakh**
* Orders: **10,132**

Bangalore and Pune were the next strongest markets.

### 💰 Discount Analysis

The analysis showed that higher discounts were **not associated with higher orders or revenue** in this dataset.

Average revenue:

* **0% discount:** ₹21,477
* **5% discount:** ₹18,634
* **10% discount:** ₹17,545

However, this is a **descriptive relationship, not proof of causation**.

### 📱 Influencer Marketing

Only **30% of records** had influencer activity.

Interestingly, records without influencer activity had higher average orders and revenue. This does not prove that influencer marketing is ineffective because campaign targeting and other factors may influence the results.

### 🧾 AOV Analysis

**Confectionery** had the highest AOV at approximately **₹123**, while **Grocery** had the lowest at approximately **₹101**.

This suggests opportunities for cross-selling and bundling higher-AOV categories with high-frequency products.

## 📈 Important Correlations

| Relationship                   | Correlation |
| ------------------------------ | ----------: |
| Discount ↔ Orders              |     ≈ -0.03 |
| Price ↔ Orders                 |      ≈ 0.01 |
| Current Price ↔ Revenue        |      ≈ 0.67 |
| Current Price ↔ Original Price |      ≈ 0.99 |

The results indicate that **price alone does not strongly determine order volume** in this dataset.

## 📊 Analysis Areas

The project covers:

1. Product Ranking by Orders
2. Product Ranking by Revenue
3. Category-Wise Revenue Analysis
4. City-Wise Revenue Analysis
5. City-Wise Order Analysis
6. City × Category Analysis
7. Discount Impact Analysis
8. Influencer-Marketing Analysis
9. Pricing & AOV Analysis
10. Top & Bottom Product-City Pairs

## ⚠️ Data Limitations

* No date/time column, so time-series and growth analysis cannot be performed.
* The dataset is aggregated rather than raw order-level data.
* Product and city record counts are not perfectly balanced.
* There is no customer-level information for retention or repeat-purchase analysis.
* Discount and influencer findings represent correlations and should not be interpreted as causal effects.

## 🚀 Future Scope

The descriptive analysis can be extended into predictive analytics using:

* Sales Forecasting
* Product Demand Prediction
* City-Wise Demand Forecasting
* Inventory Optimization
* Discount Optimization
* Influencer Campaign Prediction
* AOV Prediction
* Customer Segmentation

Potential techniques include:

**Regression | Random Forest | XGBoost | ARIMA/Prophet | K-Means Clustering**

## 💡 Business Recommendations

* Maintain sufficient inventory for high-demand products such as **Coca Cola 1L, Parle-G, and Maggi Noodles**.
* Prioritize strong markets such as **Hyderabad, Bangalore, and Pune**.
* Develop city-specific strategies based on category preferences.
* Carefully evaluate discounts instead of assuming higher discounts create higher sales.
* Investigate low-performing product-city combinations.
* Use bundling and cross-selling to improve AOV.
* Collect time-series and customer-level data for deeper predictive analysis.

## 📁 Project Structure

```text
Zepto-Sales-Analytics/
│
├── Dataset/
│   └── zepto_sales_dataset.csv
│
├── Analysis/
│   └── Excel Analysis
│
├── Dashboard/
│   └── Power BI Dashboard
│
├── Report/
│   └── Zepto_Descriptive_Analytics_Report.pdf
│
└── README.md
```

## 👩‍💻 Author

**Priyanshi Gupta**

BCA Data Science & Artificial Intelligence Student

Interested in **Data Analytics, Business Intelligence, SQL, Excel, Power BI and AI**.

---

⭐ If you found this project useful, feel free to star the repository!

