# Olist Business Discovery & Data Analysis

## Project Overview

This project presents a business-focused analysis of the Olist Brazilian e-commerce platform using the public Olist e-commerce dataset.

The objective was to transform raw transactional data into actionable business insights across financial performance, customer experience, logistics, product performance, payment behavior, and seller risk.

The project was completed as a Business Discovery & Data Analysis task during my experience with HVIA.

---

## Business Objectives

The analysis focused on answering key business questions:

- How is the business performing financially?
- Which product categories and payment methods are most important?
- What factors are associated with delivery delays?
- How does delivery performance relate to customer satisfaction?
- Which geographic areas show higher operational risk?
- Can high-volume sellers create disproportionate customer-experience risk?
- How can data and AI be used to address these challenges?

---

## Dataset

The analysis uses the public Olist Brazilian e-commerce dataset.

The dataset contains information related to:

- Orders
- Customers
- Sellers
- Products
- Payments
- Reviews
- Geolocation

Multiple datasets were integrated to create an order-level analytical view and support business-level analysis.

---

## Methodology

The analysis included:

1. Data understanding and quality checks
2. Data cleaning and preprocessing
3. Order-level data modeling
4. Exploratory data analysis
5. Financial analysis
6. Product and category analysis
7. Payment behavior analysis
8. Geographic and logistics analysis
9. Customer satisfaction analysis
10. Seller risk analysis
11. Customer complaint analysis
12. Business recommendations and AI solution proposals

---

## Key Business Findings

### Financial Performance

- Total sales: **BRL 15.42M**
- Average Order Value: **BRL 159.86**

### Delivery Performance

- Average delivery time: **12.56 days**
- Overall delivery delay rate: **8.11%**

### Customer Satisfaction

- Average rating for on-time orders: **4.29/5**
- Average rating for delayed orders: **2.57/5**

This indicates a strong relationship between delivery performance and customer satisfaction.

### Intrastate vs Interstate Shipping

- Intrastate shipments: **7.92 days** average delivery time
- Interstate shipments: **15.09 days**
- Intrastate delay rate: **5.99%**
- Interstate delay rate: **9.16%**

Interstate shipments therefore represent a more significant logistics challenge.

### Seller Risk

One high-volume seller meeting the defined risk criteria handled:

- **973 orders**
- Approximately **BRL 237.8K** in revenue
- **10.07%** delay rate
- **3.50/5** average rating

This highlights the importance of monitoring seller performance alongside sales volume.

---

## Proposed AI Solutions

Based on the analysis, three potential solutions were proposed:

### 1. Predictive ETA & Delivery Delay Early-Warning System

Predict delivery times and identify orders with a high probability of delay early enough to allow intervention.

### 2. Predictive Seller Risk Scoring

Build a seller-level risk score using factors such as order volume, delivery performance, revenue, and customer ratings.

### 3. NLP-Based Customer Feedback Analysis

Automatically classify customer reviews into complaint themes and sentiment categories to help identify recurring customer-experience issues.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Exploratory Data Analysis
- Business Analytics
- Text / Keyword Analysis

---

## Project Structure

```text
Olist-Business-Discovery-Data-Analysis/
│
├── README.md
├── notebooks/
│   └── Olist_Business_Discovery.ipynb
│
├── report/
│   └── Olist_Business_Discovery_Report.pdf
│
└── requirements.txt
