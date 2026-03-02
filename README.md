# 📊 Power BI – Business Insights 360

## 📌 Project Overview

AtliQ Hardware has grown rapidly in recent years and decided to implement Data Analytics using **Power BI** to outperform competitors and enable data-driven decision-making.

This project delivers insights across:

- 💰 Finance  
- 📈 Sales  
- 📢 Marketing  
- 🚚 Supply Chain  
- 👨‍💼 Executive  

The goal is to answer stakeholder questions and support strategic business decisions using data.

---

## 🛠 Tech Stack

- SQL (MySQL)
- Power BI Desktop
- Excel
- DAX
- DAX Studio (Performance Optimization)
- Power BI Service
- Project Charter Documentation

---

## 🎯 Project Kickoff – Key Questions

Before building the dashboard, the following were clarified:

- What is the objective of this dashboard?
- How will success be measured?
- What is the project timeline?
- Who are the end users?
- What business problems are we solving?
- What risks could arise?
- What data/resources are required?
- Are preview reviews expected before final release?
- Are there design preferences from stakeholders?

---

## 📚 Business Terminologies

- **Gross Price** – Initial listed product price  
- **Pre-Invoice Deductions** – Discounts before invoice generation  
- **Post-Invoice Deductions** – Discounts after invoice  
- **Net Invoice Sales** – Sales after deductions  
- **Gross Margin** – Revenue – COGS  
- **Net Sales** – Final sales after deductions  
- **Net Profit** – Profit after all expenses  
- **COGS** – Cost of Goods Sold  
- **YTD** – Year To Date  
- **YTG** – Year To Go  
- **Channels** – Retailer, Direct, Distributor  

---

## 🏢 Company Background

AtliQ Hardware sells computers and accessories globally through:

- 🏬 Retailers  
- 🖥 Direct Channel  
- 🚛 Distributors  

The company faced losses after expanding into the U.S. market based on intuition and limited Excel analysis. Meanwhile, competitors leveraged analytics teams for data-driven strategies.

As a result, AtliQ invested in building an analytics team to improve forecasting, optimize supply chain operations, and increase profitability.

---

# 📊 Dataset Understanding

Understanding available data is crucial before analysis.

---

## 📂 Database: gdb041

### Dimension Tables

**dim_customer**
- 27 Markets (India, USA, Spain, etc.)
- 75 Customers
- Platforms:
  - Brick & Mortar
  - E-commerce (Amazon, Flipkart)
- Channels:
  - Retailer
  - Direct
  - Distributor

**dim_market**
- 27 Markets
- 7 Sub-zones
- 4 Regions:
  - APAC
  - EU
  - NA
  - LATAM

**dim_product**
- Divisions:
  - P & A
  - Peripherals
  - Networking & Storage
- 14 Product Categories (Keyboard, Internal HDD, etc.)
- Multiple product variants

---

### Fact Tables

**fact_sales_monthly**
- Monthly sold quantity
- Month start date format
- Transaction-level sales data

**fact_forecast_monthly**
- Forecasted customer demand
- Helps improve:
  - Customer satisfaction
  - Warehouse cost optimization
- Denormalized for analytical usage
- Month start date format

---

## 📂 Database: gdb056

- **freight_cost** – Market-level logistics cost
- **gross_price** – Product gross price
- **manufacturing_cost** – Year-wise manufacturing cost
- **pre_invoice_deductions** – Customer discount %
- **post_invoice_deductions** – Additional deductions

---

# 🔄 Data Import

- Data imported from MySQL into Power BI
- Database credentials configured
- Data cleaned and validated before modeling

---

# 🧠 Data Modeling

Data modeling is the foundation of the report.

- Followed best practices
- Implemented Snowflake schema
- Created calculated columns
- Built DAX measures
- Created Date Table using M language
- Optimized performance using DAX Studio
- Applied KPI indicators and conditional formatting

Poor data modeling can significantly affect report performance, hence optimization was prioritized.

---

# 🎨 Dashboard Views

## 🏠 Home View
Landing page with navigation buttons to:

- Finance View  
- Sales View  
- Marketing View  
- Supply Chain View  
- Executive View  
- Info Page  

---

## 💰 Finance View
- Net Sales
- Gross Margin
- Net Profit
- YTD & YTG performance

## 📈 Sales View
- Revenue by Market
- Customer contribution
- Product performance

## 📢 Marketing View
- Channel performance
- Discount impact
- Campaign insights

## 🚚 Supply Chain View
- Forecast vs Actual
- Freight cost analysis
- Inventory optimization

## 👨‍💼 Executive View
- High-level KPIs
- Business health overview
- Strategic performance summary

---

# 🚀 Advanced Power BI Features Used

- Calculated Columns
- DAX Measures
- Bookmarks
- Page Navigation Buttons
- Dynamic Titles
- KPI Indicators
- Conditional Formatting
- Data Validation Techniques
- Publishing to Power BI Service
- Personal Gateway Setup (Auto Refresh)
- App Creation
- Workspace & Access Management

---

# 🗂 GitHub & Deployment

- Uploaded project files
- Used GitHub LFS for large files
- Tracked specific file extensions
- Maintained version control

---

# 🎯 Project Outcome

This dashboard enables:

- Data-driven decision-making  
- Faster business insights  
- Improved forecast accuracy  
- Reduced operational losses  
- Strategic growth planning  

It empowers stakeholders to answer multiple "Why" business questions with data-backed clarity.

---

⭐ If you found this project interesting, feel free to explore the repository and connect!
