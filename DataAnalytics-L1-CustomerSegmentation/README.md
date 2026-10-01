# Customer Segmentation Analysis

## Project Overview

This project performs customer segmentation analysis using the Online Retail dataset. The analysis uses RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to identify groups of customers based on their purchasing behaviour.

## Business Objective

The objective is to segment customers into meaningful groups and identify suitable marketing and customer retention strategies for each segment.

## Dataset

Dataset: Online Retail Dataset

The dataset contains transaction-level retail information including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Methodology

The project follows these steps:

1. Dataset inspection
2. Data cleaning
3. Transaction amount calculation
4. RFM analysis
5. RFM descriptive statistics
6. Feature selection
7. Feature standardization using StandardScaler
8. Elbow Method for selecting the number of clusters
9. K-Means clustering
10. Cluster visualization
11. Customer segment profiling
12. Marketing recommendations

## Customer Segments

The analysis identified four customer segments:

- Regular Customers
- Inactive Low-Value Customers
- Very High-Value Customers
- High-Value Active Customers

## Key Business Insights

Customer behaviour varies significantly across the identified segments based on recency, purchase frequency, and monetary value.

The segmentation can help businesses develop targeted marketing strategies, improve customer retention, and provide personalized offers.

## Marketing Recommendations

### Regular Customers
- Personalized offers
- Related product recommendations
- Loyalty rewards

### Inactive Low-Value Customers
- Re-engagement campaigns
- Limited-time discounts
- Reminder emails

### Very High-Value Customers
- VIP benefits
- Exclusive promotions
- Customer retention strategies

### High-Value Active Customers
- Loyalty programs
- Personalized recommendations
- Targeted offers

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
DataAnalytics-L1-CustomerSegmentation/
│
├── README.md
├── Customer_Segmentation_Analysis.ipynb
└── Online Retail.xlsx
