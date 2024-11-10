# Amazon Delivery Insights Dashboard

This repository contains a Tableau dashboard designed to analyze Amazon-style delivery insights using the Northwind dataset adapted for MongoDB. The dataset has been formatted to help visualize order trends, delivery performance, customer insights, and product metrics.

## Dataset: Northwind@MongoDB

### Overview

The Northwind dataset provides a classic relational dataset representing a simplified version of an e-commerce system. Originally used in SQL, this dataset is adapted for MongoDB and structured for use in Tableau to create insightful visualizations similar to Amazon’s delivery analytics.

### What This Dataset Includes

- **CSV Data**: CSV files for entities such as orders, products, customers, and employees, to simulate Amazon-style analytics.
- **Import Script**: A MongoDB import script (`mongo-import.sh`) to load data directly into MongoDB.

## Requirements

1. **Tableau Desktop**: For creating and viewing the Tableau dashboard.
2. **MongoDB** (Optional): Required only if you plan to load and manipulate the data directly in MongoDB.
3. **MongoDB Data Connector for Tableau** (Optional): Allows direct connection to MongoDB for real-time analysis.

## Analysis and Dashboard Sections

The Amazon Delivery Insights Dashboard in Tableau provides a powerful view of key metrics across orders, deliveries, customers, and products. Here are the primary insights and visualizations included:

### Key Analysis Areas

1. **Order Processing & Delivery Metrics**
   - **Average Delivery Time**: Monitor delivery efficiency.
   - **Order Volumes Over Time**: Visualize daily, weekly, or monthly order patterns to identify peak times.
   - **On-Time Delivery Rate**: Track the percentage of deliveries completed on time to gauge logistical performance.

2. **Customer Insights**
   - **Top Customer Regions**: Identify regions with the highest number of orders.
   - **Customer Segmentation**: Segment customers by order frequency or total spending, helping to identify loyal or high-value customers.
   
3. **Product Performance**
   - **Top-Selling Products**: Determine the most popular products.
   - **Product Sales Trends**: Analyze product performance over time, identifying seasonal trends.
   - **Inventory Alerts**: Use stock levels to anticipate when to reorder high-demand products.

4. **Shipper Analysis**
   - **Shipper Efficiency**: Compare delivery times across different shippers.
   - **Cost per Delivery by Shipper**: Track shipping costs to optimize cost-effective delivery partners.

5. **Geographical Insights**
   - **Order Density Heatmap**: View order density by region.
   - **Delivery Time by Region**: Identify regions with delayed deliveries to improve specific regional logistics.

### Tableau Dashboard Sections

#### 1. **Executive Summary**
   - Overview metrics: Total Orders, Revenue, Customer Count, and On-Time Delivery Rate.
   - Snapshot of high-level KPIs for quick insight.

#### 2. **Order Insights**
   - Line/bar charts for **Order Volume Over Time** and **Average Delivery Time**.
   - **On-Time vs. Delayed Deliveries**: Highlight patterns in timely vs. late orders.

#### 3. **Customer Analytics**
   - **Top Regions by Order Volume**: Map view showing customer concentration.
   - **Customer Segmentation**: Filtered views based on spending or order frequency.

#### 4. **Product Insights**
   - Bar charts for **Top-Selling Products** and **Product Sales Trends**.
   - **Stock Levels**: Monitor inventory and get alerts for low-stock items.

#### 5. **Shipper Performance**
   - Shipper comparison chart displaying **Average Delivery Time** and **Delivery Cost** per shipper.
   - Filter to view specific shippers or time periods.

#### 6. **Geographical Analysis**
   - Heatmap for order density by region.
   - Regional delivery times to help with logistical planning.

