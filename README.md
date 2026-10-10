# Olist E-Commerce Data Analytics

An end-to-end data analytics project using the **Olist Brazilian E-Commerce dataset**, covering Big Data Analytics, Machine Learning, and Power BI.

## 🚀 Project Overview

The project consists of three main tasks:

- **Big Data Analytics** – Processed and analyzed Olist data using PySpark.
- **Machine Learning** – Built a Random Forest model to predict late deliveries.
- **Power BI Dashboard** – Developed interactive dashboards for sales, customer, product, payment, and delivery insights.

## 🛠️ Tech Stack

- Python
- PySpark / Apache Spark
- Pandas
- Scikit-learn
- Matplotlib
- Power BI
- DAX

## 📊 Key Analysis

- Revenue and monthly sales trends
- Top products and categories
- Revenue by state
- Payment method analysis
- Customer analysis
- Delivery performance
- Late-delivery prediction

## 🤖 Machine Learning

**Model:** Random Forest Classifier

**Target:** `LateDelivery`

- `0` → On-time
- `1` → Late

Features include:

`price`, `freight_value`, `payment_value`, `payment_installments`, `product_weight_g`, `ProductVolume`, `ApprovalTime`, `OrderMonth`, `OrderDay`, `customer_state`, `payment_type`, and product category.

Model evaluation includes:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## 📈 Power BI Dashboard

The dashboard contains two pages:

### Executive Sales Dashboard
- Total Revenue
- Total Orders
- Total Customers
- Products Sold
- Average Order Value
- Average Freight Cost
- Revenue trends
- Product and payment analysis
- State-wise revenue
- Order status

### Customer & Product Insights
- Sales per Customer
- Average Price
- On-Time Delivery %
- Average Delivery Time
- Top customers
- Freight vs Product Price
- Revenue by State and Month
- Product price distribution
- Category analysis 

## 📁 Suggested Repository Structure
Olist-Ecommerce-Analytics/
│
├── Datasets/
│   ├── olist_orders_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_products_dataset.csv
│   └── product_category_name_translation.csv
│
├── notebooks/
│   ├── 01_Big_Data_Analytics_PySpark.ipynb
│   └── 02_Late_Delivery_Random_Forest.ipynb
│
├── dashboard/
│   └── Olist_Ecommerce_Dashboard.pbix
│
├── outputs/
│   ├── olist_cleaned.csv
│   └── customer_predictions.csv
│
├── images/
│   ├── executive-sales-dashboard.png
│   └── customer-product-insight-dashboard.png
│
└── README.mdr-product-insight-dashboard.png
│
└── README.md
