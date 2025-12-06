# Maven-Market-Analysis 

This project is a complete end-to-end Business Intelligence (BI) solution built in Power BI to analyze sales, profit, customer behavior, store performance, and product insights for the fictional Maven Market company.

The goal of this dashboard is to help stakeholders track KPIs, identify trends, and make data-driven decisions across multiple business areas such as Products, Stores, Revenue, Transactions, and Returns.

## 🧭 Project Overview
<p>This Power BI report contains multiple interactive pages, including:</p>

<ul>
  <li>Sales Overview Report</li>
  <li>Product Performance Report</li>
  <li>Store Performance Report</li>
</ul>

## 🛠️ Tools & Technologies Used
<ul>
  <li>Power BI Desktop</li>
  <li>Power Query (ETL: cleaning, shaping, merging)</li>
  <li>Power BI Data Modeling</li>
  <li>DAX (Measures for KPIs & calculations)</li>
  <li>Microsoft SQL Server</li>
</ul>

## 📄 Dashboard Pages

### 🟢 1. Sales Overview Report
<p>This page serves as the executive summary of Maven Market’s performance.</p>

![Dashboard Preview](https://github.com/rakeshjetty2000/Maven-Market-Analysis/blob/main/Sales%20Overview%20Report%20.png)

<strong>Key Highlights</strong>
<ul>
  <li>Current Month Transactions: 18,325 (+5.69% YoY Goal)</li>
  <li>Current Month Profit: $71,682 (+5.61% Goal)</li>
  <li>Current Month Returns: 496 (-2.9% from Goal)</li>
  <li>Clear growth in revenue & profitability</li>
  <li>Return rate remains low (~0.99%)</li>
</ul>

### 🟢 2. Product Performance Report

![Dashboard Preview](https://github.com/rakeshjetty2000/Maven-Market-Analysis/blob/main/Maven%20Market-%20Products.png)

<ul>
  <li>Deep dive into individual product-level metrics</li>
  <li>Identifies best-selling & low-performing products</li>
</ul>

### 🟢 3. Store Performance Report

![Dashboard Preview](https://github.com/rakeshjetty2000/Maven-Market-Analysis/blob/main/Maven%20Market-%20Store%20.png)

<ul>
  <li>Analyzes performance across stores in USA, Canada, and Mexico</li>
  <li>Identifies top-performing stores and supports expansion decisions</li>
  <li>This report identifies top-performing stores and supports expansion decisions./li>
 </ul>

## 🔍 4. Insights Page (Interactive Summary)

![Dashboard Preview](https://github.com/rakeshjetty2000/Maven-Market-Analysis/blob/main/Maven%20Market-%20Insights%20.png)

<p>
This page provides a high-level summary of the most important insights discovered across the entire Power BI report.
It is designed as an interactive insights hub — each insight card acts as a navigation button, taking the user directly
to the relevant report page (Sales Overview, Product Report, Store Report).
</p>

<p>
This improves report usability and allows users to quickly jump to the underlying visualization behind each finding.
</p>

<strong>🌟 Key Insights Displayed</strong>

<ul>
  <li>
    <strong>📌 Portland hits 1000 Sales in December</strong><br>
    A significant seasonal demand spike was identified for Portland, showing strong year-end performance.
  </li>

  <li>
    <strong>📌 Sales increased by 70% from 1997 to 1998</strong><br>
    Strong year-over-year sales growth indicates improved operational performance and market expansion.
  </li>

  <li>
    <strong>📌 Mexico has the highest average revenue per customer</strong><br>
    Mexico’s average revenue per customer is <strong>$433</strong>, higher than both USA & Canada — suggesting stronger value per transaction.
  </li>

  <li>
    <strong>📌 Store 13 leads across all key metrics</strong><br>
    Highest Quantity Sold, Transactions, Profit, and Revenue — achieved with only <strong>472 customers</strong>, indicating exceptional efficiency.
  </li>

  <li>
    <strong>📌 Customer preferences differ by country</strong><br>
    USA: Customers prefer Supermarkets over Deluxe Supermarkets<br>
    Mexico: Deluxe Supermarkets attract more customers
  </li>

  <li>
    <strong>📌 Deluxe Supermarkets are nearly as profitable as Supermarkets</strong><br>
    With ~50% fewer customers, Deluxe Supermarkets generate similar transactions, similar quantity sold, and ~90% of Supermarket profit.
  </li>
</ul>
