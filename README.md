# AtliQ_Hardware_Sales_Analysis
This Power BI project provides business performance insights for AtliQ Hardware — an India-based company supplying computer hardware across multiple regions.  The project helps stakeholders identify sales trends, regional performance, and profit analysis using clean, interactive dashboards.


markdown
Copy
Edit
# 📊 Sales Analysis Dashboard (Power BI Project)

A comprehensive Power BI project focused on uncovering actionable insights from sales data. This analysis supports business decision-making, highlights underperformance, and identifies growth opportunities.

---

##  Problem Statement

The company was growing dynamically but faced a decline in sales. The goal was to build an automated dashboard to:
- Discover hidden sales trends
- Support faster decision-making
- Reduce time spent on manual data gathering

---

##  Tools & Technologies
- **Power BI** (DAX, Power Query, Visuals)
- **MySQL** (ETL & validation)
- **Star Schema** Data Modeling
- Manual ETL pipeline for data cleaning, transformation, and loading

---

##  Workflow Summary

### 1. Data Preparation
- MySQL used for querying raw transactional data
- Data cleaned and normalized (e.g., currency conversion from USD to INR)
- Duplicates and invalid values filtered (e.g., `sales_amount <= 0`)
- Used Power Query for final transformation steps

### 2. Data Modeling
- Star Schema: 1 fact table (`sales_transactions`) and multiple dimension tables
- Relationships created in Power BI for accurate filtering

### 3. DAX Measures
- `Revenue`, `Sales Qty`, `Profit Margin %`, `Profit Margin Contribution %`
- Custom profit margin goal comparisons using dynamic input (slider)

---

## Dashboard Features

- Interactive year filter (e.g., 2020)
- Market-level analysis with bookmarks for region-specific views
- Top 5 customers and products
- Revenue and profit trends by month/year
- Target profit margin simulation
- Visual insight into profit contribution by customer and market

---

##  2020 Key Insights

- **Top Customer**: Electricalsara Stores (46.1% of revenue, 50.6% of profit)
- **Profit Drop**: Margin declined from 4% (Jan) to 0.9% (Apr) despite steady revenue
- **Loss-making Markets**: Lucknow and Bengaluru consistently underperformed
- **Emerging Markets**: Bhubaneshwar (+0.09), Hyderabad (+0.06) exceeded targets
- **Balanced Performance**: Mumbai (14.1% revenue, 12.1% profit)
- **Client Efficiency**: Atlas Stores had better margins than higher-volume clients
- **Low-Profit Customer**: Electricalssale Stores – zero profit despite revenue

---

## 🗃️ Project Structure

Sales-Analysis-Dashboard │ ├── /Reports │ ├── sales_analysis.pbix # Power BI report file with all visuals and measures │ ├── sales_queries_and_dax.pbix # Power BI file containing queries and DAX measures │ └── /Screenshots # Folder containing screenshots of the Power BI dashboard │ ├── screenshot1.png │ ├── screenshot2.png │ └── screenshot3.png │ ├── /Insights │ ├── insights_folder1 # Folder containing insight files │ │ ├── insight1.pbix │ │ ├── insight2.pbix │ │ └── insight3.pbix │ ├── insights_folder2 # Folder containing another set of insights │ │ ├── insight1.pbix │ │ ├── insight2.pbix │ │ └── insight3.pbix │ └── insights_folder3 # Folder containing the third set of insights │ ├── insight1.pbix │ ├── insight2.pbix │ └── insight3.pbix │ ├── /Data │ └── sales_data.csv # Raw transactional data (single dataset) │ └── README.md # Main README file for the project

### Explanation of Folders and Files:

- **/Reports**: Contains the main Power BI report file, along with queries and DAX measures, and screenshots of the dashboard.
- **/Insights**: Includes multiple folders, each containing Power BI files for different sets of insights.
- **/Data**: Holds the single dataset used for analysis (raw data).


---


