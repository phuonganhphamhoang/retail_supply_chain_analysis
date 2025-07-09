# 🏬 Retail Smart Supply Chain Analysis & BI Dashboards

**Tagline:** A full-spectrum analytics project utilizing Power BI, Python, and Tableau to uncover operational inefficiencies, customer behavior patterns, and financial insights for a global retail enterprise.

---

## 📌 Project Overview

This project delivers deep insights into a multinational retail dataset by integrating data preprocessing, machine learning, and dynamic dashboards. It supports data-driven decisions in areas such as business strategy, logistics optimization, and customer loyalty management.

---

## 📊 Tools & Technologies

* 💻 **Power BI** – Used for cleaning, modeling, and crafting the main dashboards
* 🐍 **Python** – Leveraged for RFM metric calculations and customer clustering via KMeans
* 📊 **Tableau** – Designed interactive visuals focused on executive KPIs and delivery analytics

---

## 📀 Dataset

* Approx. 180,000 records × 52 attributes
* Rich transactional data including orders, customers, logistics, and financials
* Supports multidimensional analysis:

  * Revenue, cost, and margin evaluation
  * Delivery modes and punctuality
  * Customer purchasing trends and loyalty levels

**Source:** [Kaggle - DataCo Smart Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

<p align="center">
  <img src="images/dataco_rdm.png" width="750"/>
</p>
<p align="center"><em>DataCo Relational Data Model (RDM)</em></p>

---

## 📊 Dashboard Snapshots

* 1️⃣ Executive Overview
* 2️⃣ Shipping & Delivery Performance
* 3️⃣ Customer Segmentation with RFM + Clustering

<p align="center">
  <img src="images/dashboard_exec.png" width="750"/>
</p>
<p align="center"><em>Executive Performance Overview</em></p>

<p align="center">
  <img src="images/dashboard_delivery.png" width="750"/>
</p>
<p align="center"><em>Delivery Metrics & Fulfillment Patterns</em></p>

<p align="center">
  <img src="images/dashboard_rfm.png" width="750"/>
</p>
<p align="center"><em>Customer Segmentation via RFM + KMeans</em></p>

---

## 🚀 Dashboard Access

* 📈 **Tableau**: [Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/truonghuyphan.da/viz/TABLEAU-DataCoDashboard/EXCUTIVEdashboard)
* 📊 **Power BI**: `.pbix` file included in the project repository

---

## 🚀 Project Objectives

Develop three core dashboards covering:

### 📈 Executive Dashboard

* Visualize overall financial performance
* Spot top regions and product lines

### 🚚 Delivery Dashboard

* Track delay frequency and fulfillment by shipping class
* Detect underperforming zones

### 👥 RFM Segmentation Dashboard

* Analyze Recency, Frequency, Monetary behavior
* Cluster customers into actionable groups: Loyal, Potential, New, Churned

---

## 🗓 Project Workflow

### 🔧 Data Preparation (Power BI)

* Cleaned and standardized data
* Defined relationships to support accurate calculations

### 📊 RFM Segmentation (Python)

* Derived RFM scores using `pandas`
* Grouped customers using `KMeans` clustering

### 📊 Dashboard Development

* Power BI: Detailed performance analysis and customer behavior
* Tableau: Executive summaries and shipping KPIs

---

## 🔍 Key Insights

### 🏢 Financial Findings

* High costs: \~11% discounts, \~81% other expenses → \~8.3% profit margin
* Puerto Rico generates >38.5% revenue with fewer stores than the USA
* APAC and Europe dominate regional sales shares
* 2017 Q4: Sales rose but revenue fell due to lower AOV

### 🚚 Delivery Observations

* Completion is solid (95.65%) but timeliness lacking: \~55% late
* First/Second Class modes correlate with higher delay odds
* Same Day shipping also suffers from delays

### 🧑‍💼 Customer Behavior

* Retention drops steeply after initial engagement (\~33% repeat rate)
* Loyal + Potential = 47% of users but drive 80% revenue
* Newcomers large in number, low in value; churned users once high spenders

### 💳 Discount Evaluation

* Loyal users get fewer discounts yet spend more → prioritize service quality
* Churned users left despite incentives → product/service pain points
* Potential users over-targeted by ineffective promotions

---

## ✅ Recommendations

### 🚛 Fix Shipping Bottlenecks

* Audit First/Second Class operations
* Update ETA frameworks
* Optimize warehouse logistics

### 🌍 Address High-Delay Regions

* Prioritize East/North Africa
* Improve delivery for Health & Beauty items

### 🧠 Smarter Promotions

* Align offers with loyalty levels
* Shift focus from discounting to experience

---
