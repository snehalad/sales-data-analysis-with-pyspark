# 🛍️ Sales Data Analysis using PySpark

### 📁 Dataset Summary

  The dataset contains structured transactional data with the following columns:

- Region, Country

- Item Type, Sales Channel

- Order Priority, Order Date, Ship Date

- Units Sold, Unit Price, Unit Cost

- Total Revenue, Total Cost, Total Profit


### 🛣️ Project Workflow
#### 1. 📁 Data Collection & Understanding
  - Loaded sales data from CSV using PySpark.
  
  - Explored schema and data types for initial inspection.
  
  - Understood business context from fields like Region, Sales Channel, Order Priority, etc.

#### 2. 🧹 Data Cleaning & Preprocessing
- Converted Order Date and Ship Date to Spark DateType.

- Profit Margin = Total Profit / Total Revenue

- Handled missing values and standardized data types.

#### 3. 📊 Business Analysis & Insights

Performed various group-wise and time-based aggregations using PySpark DataFrame API and SQL:

- 🔝 Top 5 profitable products by region

- 💰 Online vs. Offline revenue and profit comparison

- 📦 Average shipping delay per country

- 📈 Monthly revenue and profit trend

- 🚚 Effect of order priority on shipping time

- 📉 High-selling, low-profit margin products
