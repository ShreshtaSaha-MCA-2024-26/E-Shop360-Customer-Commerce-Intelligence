# 📊 E-Shop360 – Customer & Commerce Intelligence

An end-to-end **Power BI Business Intelligence and Customer Analytics project** built using the **Brazilian E-commerce (Olist) Dataset**.

E-Shop360 transforms raw e-commerce transaction data into an interactive, decision-ready analytics solution covering **sales performance, customer value, product categories, payment behavior, delivery efficiency, and customer feedback**.

The project demonstrates a complete BI workflow — from **data preparation and transformation to data modeling, DAX-based KPI development, interactive visualization, and business storytelling**.

---

## 🚀 Project Overview

Modern e-commerce businesses generate large volumes of customer, transaction, payment, and delivery data. However, raw data alone does not provide meaningful business insights.

**E-Shop360** integrates and analyzes multiple business datasets to provide stakeholders with a centralized view of business performance.

The solution helps answer questions such as:

* How much revenue is the business generating?
* How many orders are being processed?
* Which product categories generate the most revenue?
* Which customers contribute the most business value?
* How concentrated is revenue among high-value customers?
* Are orders being delivered on time?
* How do delivery delays relate to customer review scores?
* How much payment value is failed or refunded?
* How effective are different payment methods and gateways?
* What is the impact of discounts and coupons on revenue and AOV?
* How many new customers are being acquired?

---

## 🎯 Business Objective

The primary objective is to develop an **interactive self-service Business Intelligence dashboard** that enables business users to monitor performance, identify operational issues, understand customer behavior, and support data-driven decision-making.

### Key Business Goals

* Monitor revenue and order performance
* Analyze customer purchasing behavior and value
* Identify high-performing product categories
* Evaluate payment performance and payment risks
* Monitor delivery efficiency and delays
* Analyze customer review scores
* Identify high-value customers
* Understand revenue concentration
* Evaluate discount and coupon impact
* Track new customer acquisition

---

## 📸 Dashboard Preview

### 📊 E-Shop360 – Customer & Commerce Intelligence

<img width="1166" height="657" alt="image" src="https://github.com/user-attachments/assets/9d0f9b89-04cb-48cb-8696-60a53d370a00" />

---

# 📈 Executive KPIs

The dashboard provides a high-level view of important business and operational indicators.

| KPI                                | Dashboard Value |
| ---------------------------------- | --------------: |
| 💰 Total Revenue                   |     **132.10K** |
| 🛒 Total Orders                    |         **501** |
| 📦 Average Order Value             |      **263.67** |
| 👥 New Customers                   |          **69** |
| ⭐ Average Review Score             |    **3.66 / 5** |
| 🚚 On-Time Delivery Rate           |         **61%** |
| 💳 Failed / Refunded Payment Value |      **13.88K** |
| ❌ Cancelled Order Rate             |        **4.6%** |
| 🎟️ Total Discount Given           |       **8.45K** |

> **Note:** KPI values represent the current dashboard view and may change when filters or slicers are applied.

---

# 🗂️ Dashboard Architecture

The Power BI solution is organized into dedicated analytical pages:

### 🏠 1. Home Page

Provides project navigation and introduces the E-Shop360 analytics solution.

### 📊 2. Executive Dashboard

Provides a consolidated business overview through:

* Revenue and order KPIs
* Average Order Value
* New Customer Count
* Payment Failed/Refunded Value
* Cancelled Order Rate
* Monthly revenue and order trends
* Customer revenue analysis
* Customer segment analysis
* State-level revenue analysis
* Payment type analysis
* Average review score
* On-time delivery performance

### 💰 3. Sales Analysis

Focuses on sales and commercial performance.

Key analysis includes:

* Total Revenue
* Total Orders
* Total Quantity
* Average Order Value
* Monthly Revenue Trends
* Product Category Revenue
* Top 5 Product Categories
* Customer Segment Revenue
* State-level Revenue
* Cancelled Order Rate

### 👥 4. Customer Analysis

Analyzes customer value, purchasing behavior, and customer segmentation.

Key analysis includes:

* Top 10 Customers by Revenue
* Customer Revenue Concentration
* VIP Revenue Share
* Recency Tier
* Monetary Tier
* Customer AOV
* Customer Orders
* Customer Revenue
* New Customer Count
* CLV Proxy
* Customer segment analysis

### 🚚 5. Delivery Analysis

Analyzes logistics performance and customer feedback.

Key analysis includes:

* On-Time Delivery %
* Average Delivery Days
* Average Delivery Delay
* Delivery Delay Buckets
* Delivery Status Distribution
* Delivery Performance by State
* Delivery Trends by Month
* Review Score by Delivery Status
* Total Delivery Delay Days
* Revenue at Risk

### 💳 6. Payment Analysis

Analyzes payment behavior and financial impact.

Key analysis includes:

* Payment Type Analysis
* Payment Gateway Analysis
* Payment Status
* Payment Failure Rate
* Failed/Refunded Payment Value
* Discount Analysis
* Net Revenue After Discount
* Coupon Usage
* Coupon Impact on AOV
* Payment trends

---

# 🧹 Data Preparation & Transformation

The project follows a structured **ETL (Extract, Transform, Load)** workflow using Power Query and Power BI.

The data preparation process includes:

* Importing source datasets
* Reviewing data structure and quality
* Cleaning and transforming source data
* Handling missing or inconsistent values where required
* Correcting data types
* Preparing date and categorical fields
* Creating analysis-ready columns
* Combining relevant business information
* Establishing relationships between datasets
* Validating data before visualization

The objective of the transformation stage is to convert raw transactional data into a reliable analytical dataset suitable for business reporting.

---

# 🧩 Dataset Structure

The project uses the **Brazilian E-commerce (Olist) Dataset** and organizes business information into analytical tables.

## Sales

Contains order and customer-related information such as:

* Order ID
* Customer Information
* Customer State
* Customer Segment
* Product Category
* Order Value
* Purchase Date

## Payments

Contains transaction and payment information such as:

* Payment Type
* Payment Gateway
* Payment Status
* Installments
* Discount Information
* Coupon Information

## Delivery

Contains logistics and customer feedback information such as:

* Delivery Status
* Estimated Delivery Date
* Actual Delivery Date
* Delivery Days
* Delivery Delay
* Review Score

---

# 🔗 Data Modeling

The project uses a relational data model to connect sales, payment, delivery, customer, and analytical information.

The data model enables:

* Cross-filtering between business dimensions
* Consistent KPI calculations
* Customer-level analysis
* Order-level analysis
* Time-based analysis
* State-level analysis
* Payment and delivery performance analysis

This modeling approach allows users to interact with the dashboard through slicers while dynamically updating related visualizations and KPIs.

---

# 📐 DAX Measures

Custom DAX measures were developed to convert raw data into meaningful business metrics.

### Sales & Revenue

* `Total Revenue`
* `Total Orders`
* `Total Quantity`
* `Average Order Value`
* `Net Revenue (After Discount)`
* `Total Discount Given`

### Customer Analytics

* `New Customer Count`
* `Top 10 Customers Revenue`
* `Revenue Concentration % (Top 10)`
* `VIP Revenue Share %`
* `CLV Proxy (Customer Lifetime Value)`
* Customer revenue and AOV analysis

### Delivery Analytics

* `On-Time Delivery %`
* `Average Delivery Delay (Days)`
* `Total Delivery Delay Days`
* `Revenue at Risk`
* `Avg Review Score`
* `Cancelled Order Rate`

### Payment Analytics

* `Payment Failed/Refunded Value`
* `Payment Failure Rate %`
* `Coupon Impact on AOV`

These measures allow the dashboard to provide dynamic calculations rather than relying only on static values.

---

# 📊 Interactive Dashboard Features

The dashboard includes interactive features designed for self-service business analysis.

### 🔎 Dynamic Slicers

Users can filter the analysis by dimensions such as:

* State
* Customer Segment
* Product Category
* Payment Type
* Payment Status
* Delivery/Order Status
* Month

### 📈 Interactive Visualizations

The project uses multiple Power BI visualization techniques, including:

* KPI Cards
* Line & Column Charts
* Donut Charts
* Pie Charts
* Ribbon Charts
* Treemaps
* Maps
* Gauges
* Scatter-style customer analysis
* Interactive slicers
* Cross-filtering

---

# 💡 Key Business Insights

The dashboard enables stakeholders to identify several important business patterns.

### 💰 Revenue Performance

The business generates approximately **132.10K in revenue from 501 orders**, with an average order value of approximately **263.67**.

Monthly revenue analysis can be used to identify changes in sales performance and periods of higher or lower business activity.

### 👥 Customer Value

The customer analysis identifies high-value customers and measures revenue concentration among the top customers.

The dashboard also uses **Recency and Monetary tiers**, VIP revenue contribution, and a **CLV Proxy** to provide a broader view of customer value.

### 🛍️ Product Performance

Product category analysis helps identify categories contributing significantly to revenue and supports category-level performance monitoring.

### 🚚 Delivery Performance

The dashboard reports an **On-Time Delivery Rate of approximately 61%**, allowing management to monitor delivery performance and identify potential logistics improvement areas.

Delivery analysis also connects delivery status with review scores, providing a way to examine the relationship between logistics performance and customer feedback.

### 💳 Payment Performance

The dashboard tracks failed/refunded payment value and payment failure rate.

Payment type and gateway analysis can help businesses understand payment behavior and identify areas requiring further investigation.

### 🎟️ Discount & Coupon Impact

Discount and coupon analysis allows stakeholders to evaluate how promotional activity affects:

* Revenue
* Net Revenue
* Average Order Value
* Customer purchasing behavior

---

# 🧠 Business Use Cases

E-Shop360 can support different business functions:

| Business Area                | Possible Use                                             |
| ---------------------------- | -------------------------------------------------------- |
| **Management**               | Monitor overall business performance                     |
| **Sales Team**               | Analyze revenue, orders, and product categories          |
| **Marketing Team**           | Understand customer segments and high-value customers    |
| **Finance Team**             | Monitor revenue, discounts, and failed/refunded payments |
| **Operations Team**          | Monitor delivery delays and logistics performance        |
| **Customer Experience Team** | Analyze review scores and delivery-related feedback      |
| **Business Analysts**        | Perform interactive exploratory analysis                 |

---

# 🚨 Decision-Support Opportunities

The dashboard can help stakeholders investigate areas such as:

### Delivery

The **61% on-time delivery rate** highlights the need to investigate delayed orders by state, month, and delivery status.

### Payment

The **13.88K failed/refunded payment value** can be analyzed further by payment type, gateway, and transaction characteristics.

### Customer Retention

High-value customers identified through revenue, recency, monetary tiers, and VIP revenue share can be analyzed for retention opportunities.

### Revenue Concentration

Top-customer revenue concentration helps management understand how much business revenue depends on a relatively small group of customers.

### Promotional Efficiency

Discount and coupon analysis can help evaluate whether promotional activity is contributing to higher order values and revenue.

> These are **decision-support areas**, not automated recommendations. Business teams can use the dashboard to investigate the underlying causes and determine appropriate actions.

---

# 🛠️ Technology Stack

| Technology              | Purpose                                |
| ----------------------- | -------------------------------------- |
| **Power BI Desktop**    | Dashboard and report development       |
| **Power Query**         | Data cleaning and transformation       |
| **DAX**                 | KPI and business metric development    |
| **Data Modeling**       | Relationships and analytical structure |
| **Interactive Slicers** | Dynamic filtering                      |
| **Microsoft Excel**     | Source data preparation/storage        |

---

# 🎓 Skills Demonstrated

## Data Analytics

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* KPI Development
* Trend Analysis
* Customer Analytics
* Revenue Analysis
* Operational Analytics

## Power BI

* Power Query
* DAX
* Data Modeling
* Interactive Dashboards
* Slicers
* Cross Filtering
* Data Visualization
* Business Reporting

## Business Intelligence

* Business KPI Monitoring
* Customer Segmentation
* Revenue Concentration Analysis
* Payment Performance Analysis
* Delivery Performance Analysis
* Data Storytelling
* Decision Support

---

# 📁 Repository Structure

```text
E-Shop360-Customer-Commerce-Intelligence/
│
├── E-Shop360 - Customer & Commerce Intelligence.pbix
│
├── data/
│   ├── Sales.xlsx
│   ├── Payments.xlsx
│   └── Delivery.xlsx
│
├── readme_assets/
│   └── dashboard-preview.png
│
└── README.md
```

> Update the filenames above if your GitHub repository uses different names.

---

# 🎯 Project Outcome

**E-Shop360** demonstrates a complete Business Intelligence workflow:

**Raw Data → Data Cleaning → Data Transformation → Data Modeling → DAX → Interactive Dashboard → Business Insights → Decision Support**

The project converts multi-dimensional e-commerce data into a centralized analytics solution that enables stakeholders to monitor **sales, customers, payments, delivery operations, and customer feedback** through interactive Power BI reports.

The project demonstrates practical knowledge of **Power BI, Power Query, DAX, data modeling, data visualization, customer analytics, and business intelligence**.

---

# 👨‍💻 Authors

**Shreshta Saha**
**Shreyasree Mete**

**Centre of Excellence for AI**

---

# 📚 Dataset

**Brazilian E-Commerce Public Dataset by Olist**

The dataset is used for educational, analytical, and portfolio purposes.

---

# 📜 License

This project is intended for **educational, academic, learning, and portfolio purposes**.

The underlying Brazilian E-commerce dataset is publicly available and remains subject to its respective terms and licensing conditions.

---

## ⭐ Project Focus

> **"Transforming E-commerce Data into Business Intelligence."**

---



