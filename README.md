
# Olist E-Commerce Sales & Customer Analytics

## Project Overview

This project focuses on analyzing the Brazilian Olist E-Commerce dataset to understand sales performance, customer behavior, product performance, payment patterns, and delivery operations.

The objective is to transform raw e-commerce data into meaningful business insights using Python and data visualization techniques.

This is an end-to-end Data Analytics project covering data exploration, data cleaning, data integration, exploratory data analysis (EDA), business KPI calculation, and business recommendations.

## Tools & Technologies

- **Python** – Programming language for data analysis
- **Pandas** – Data cleaning, manipulation, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive development environment
- **Git & GitHub** – Version control and project hosting

## Dataset Information

- **Dataset:** Brazilian E-Commerce Public Dataset by Olist
- **Source:** Kaggle
- **Dataset Size:** Approximately 100,000 orders
- **Format:** CSV files
- **Tables:** Customers, Orders, Order Items, Payments, Reviews, Products, Sellers, Geolocation, and Category Translation.

Dataset Link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Project Workflow

1. **Data Collection** – Loaded all 9 CSV datasets.
2. **Data Exploration** – Examined dataset structure, columns, data types, and missing values.
3. **Data Cleaning** – Handled missing values, duplicates, inconsistent data, and incorrect data types where appropriate.
4. **Data Integration** – Combined multiple datasets into a master dataset using Pandas merge and aggregation.
5. **Exploratory Data Analysis (EDA)** – Analyzed sales, customers, products, payments, reviews, sellers, and delivery performance.
6. **Business KPI Analysis** – Calculated important business metrics.
7. **Data Visualization** – Created charts using Matplotlib to identify trends and patterns.
8. **Business Recommendations** – Suggested improvements based on the analysis.

## Key Business KPIs

| KPI | Result |
|---|---:|
| Total Product Revenue | R$13.59 Million |
| Total Orders | 98,666 |
| Total Customers | 95,420 |
| Total Products Sold | 112,650 |
| Average Order Value (AOV) | R$137.75 |
| Total Freight Revenue | R$2.25 Million |
| Average Delivery Time | 12.01 Days |
| Cancellation Rate | 0.63% |
| Order Fulfillment Rate | 97.02% |
| Repeat Customer Rate | 3.05% |

## Key Business Insights

- **Revenue Performance:** November 2017 recorded the highest monthly product revenue.
- **Category Performance:** Health & Beauty generated the highest product category revenue.
- **Order Volume:** Bed Bath & Table was the most ordered product category.
- **Customer Retention:** Only 3.05% of customers made repeat purchases, indicating an opportunity to improve customer retention.
- **Payment Preferences:** Credit cards contributed the highest payment value.
- **Delivery Performance:** Late deliveries were associated with lower average customer review scores (2.27 compared with 4.29 for early deliveries).
- **Geographical Performance:** São Paulo (SP) generated the highest state-wise product revenue.

## Business Recommendations

1. **Improve Customer Retention:** Introduce loyalty programs, personalized offers, and repeat-purchase campaigns.
2. **Improve Delivery Performance:** Focus on reducing delivery delays to improve customer satisfaction.
3. **Strengthen Category Strategy:** Promote high-revenue categories while identifying opportunities in high-demand categories.
4. **Optimize Payment Experience:** Maintain a smooth and secure credit card payment experience while supporting other payment methods.

## Project Structure

```text
Olist_DatasetFolder/
│
├── Dataset_Exploration.ipynb
├── README.md
│
└── Olist_Dataset/
    ├── Original CSV datasets
    └── olist_master_dataset.csv
```

## Conclusion

This project provided hands-on experience in performing end-to-end data analysis on a real-world e-commerce dataset.

Through data cleaning, integration, exploratory analysis, KPI calculation, and visualization, meaningful insights were identified to understand business performance and customer behavior.

The project strengthened practical skills in Python, Pandas, NumPy, Matplotlib, and business-oriented data analysis.

## Author

Data Analytics Portfolio Project
