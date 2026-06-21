# 📊 Customer E-Commerce Sales Analytics

## 📌 Project Overview

This project analyzes the Brazilian Olist E-Commerce dataset to uncover actionable business insights related to customer behavior, sales performance, logistics operations, and customer satisfaction.

The objective is to transform raw transactional data into meaningful insights that can help businesses improve decision-making and operational efficiency.

---

## 🎯 Business Objectives

This analysis aims to answer the following business questions:

* Which customer regions generate the highest sales?
* Which product categories contribute the most revenue?
* How efficient is the delivery process?
* Do delivery delays impact customer satisfaction?
* What factors influence customer review scores?
* Can business assumptions be validated using statistical testing?

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## 📂 Repository Structure

```text
customer-ecommerce-sales-analytics/

├── datasets/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── order_payments.csv
│   ├── order_reviews.csv
│   ├── products.csv
│   └── sellers.csv
│
├── scripts/
│   └── customer_ecommerce_analysis.ipynb
│
├── business_report/
│   └── Customer_Ecommerce_Analytics_Report.pdf
│
└── README.md
```

---

## 🔍 Analysis Performed

### Data Cleaning & Preparation

* Missing value treatment
* Duplicate removal
* Datetime conversion
* Data quality checks

### Customer Analytics

* State-wise customer distribution
* City-wise customer distribution
* Customer purchase behavior analysis
* Order frequency analysis

### Sales Analytics

* Revenue analysis
* Product category performance
* Sales trend analysis
* Top-selling categories identification

### Logistics Analytics

* Delivery time analysis
* Late delivery identification
* Delivery performance measurement
* Logistics efficiency evaluation

### Customer Satisfaction Analytics

* Review score distribution
* Customer rating analysis
* Impact of delivery delays on customer reviews

### Statistical Hypothesis Testing

#### Hypothesis 1

**H₀:** Delivery delays do not impact customer review scores.

**H₁:** Delivery delays negatively impact customer review scores.

**Test Used:** Welch's T-Test

#### Hypothesis 2

**H₀:** High-order-volume cities generate the same sales as low-order-volume cities.

**H₁:** High-order-volume cities generate significantly higher sales.

**Test Used:** Z-Test

---

## 📈 Key Findings

### Customer Insights

* Customer orders are concentrated in a few major states.
* A small number of cities contribute a significant portion of total sales.

### Sales Insights

* Certain product categories consistently generate higher revenue.
* Sales performance varies significantly across product categories.

### Logistics Insights

* Delivery performance directly affects customer experience.
* Delayed orders are associated with lower customer ratings.

### Customer Satisfaction Insights

* Customers receiving orders on time are more likely to leave positive reviews.
* Delivery delays increase the likelihood of negative ratings.

### Statistical Findings

* Statistical testing confirms a significant relationship between delivery delays and customer review scores.
* High-order-volume cities contribute significantly more sales than lower-volume cities.

---

## 💼 Business Impact

The insights generated from this analysis can help businesses:

* Improve customer retention
* Enhance delivery performance
* Increase customer satisfaction
* Optimize product strategies
* Support data-driven decision making

---

## 📚 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Hypothesis Testing
* Customer Analytics
* Sales Analytics
* Business Analytics
* Python Programming
---

## 👨‍💻 Author

**Himanshu Rawat**

Aspiring Data Analyst | SQL | Python | Statistics | Data Visualization

Passionate about transforming data into actionable business insights.
