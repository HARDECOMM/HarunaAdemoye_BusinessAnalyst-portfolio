# HarunaAdemoye_BusinessAnalyst-portfolio

Showcase of Business Analysis Core Responsibility

[View the Project on GitHub](https://github.com/HARDECOMM/HarunaAdemoye_BusinessAnalyst-portfolio)

---

# Business Analyst Portfolio Project – Prime Mart Lagos

⭐ End-to-end Business Analyst workflow demonstrating Excel-based data analysis, KPI development, and dashboard visualization for retail business performance.

---

## 📑 Table of Contents

1. [Analyst Information](#analyst-information)
2. [Executive Summary](#executive-summary)
3. [Business Problem](#business-problem)
4. [Business Objectives](#business-objectives)
5. [Key Business Questions](#key-business-questions)
6. [Dataset Description](#dataset-description)
7. [Data Structure and Mapping](#data-structure-and-mapping)
8. [Business Value of Data Model](#business-value-of-data-model)
9. [Data Preparation Process](#data-preparation-process)
10. [KPI Development](#kpi-development)
11. [KPI Results Summary](#kpi-results-summary)
12. [Data Analysis Method](#data-analysis-method)
13. [Key Insights](#key-insights)
14. [Business Recommendations](#business-recommendations)
15. [Dashboard](#dashboard)
16. [Project Files Structure](#project-files-structure)
17. [Business Analyst Skills Demonstrated](#business-analyst-skills-demonstrated)
18. [Business Value Delivered](#business-value-delivered)
19. [Project Outcome](#project-outcome)
20. [Portfolio Purpose](#portfolio-purpose)
21. [Contact Information](#contact-information)

---

## 👤 Analyst Information

- **Name:** Haruna Ademoye  
- **Role:** Business Analyst  
- **Project Type:** Retail Business Performance Analysis  
- **Tools Used:** Microsoft Excel, Power BI (Planned), SQL (Planned)  

---

## 📌 Executive Summary

Prime Mart Lagos operates three retail stores located in Ikeja, Lekki, and Yaba.  

Management has observed:
- Fluctuations in revenue
- Increasing operating expenses
- Inventory stockouts
- Uneven store performance

This project analyzes business operations, identifies performance issues, and provides data-driven recommendations to improve profitability and operational efficiency.

---

## 🧠 Business Problem

Management is facing the following key challenges:
- Inconsistent revenue across stores
- Increasing operating expenses
- Frequent stockouts of fast-moving products
- Uneven store performance

These issues limit informed decision-making and affect profitability.

---

## 🎯 Business Objectives

| Objective                                           | Business Purpose                                  |
|----------------------------------------------------|--------------------------------------------------|
| Analyze revenue and profit performance              | Identify best and worst performing stores        |
| Identify high and low performing products           | Improve product strategy                          |
| Evaluate customer segment contribution              | Improve customer targeting                        |
| Assess inventory efficiency                         | Reduce stockouts                                  |
| Analyze operating expenses                          | Improve cost control                              |
| Identify operational improvement opportunities       | Increase overall profitability                    |

---

## ❓ Key Business Questions

| Business Objective                              | Example Question                                                         |
|------------------------------------------------|-------------------------------------------------------------------------|
| Analyze revenue and profit performance          | Which store generates the highest revenue and profit?                   |
| Identify high and low performing products       | Which products generate the most profit? Which stock out most often?    |
| Evaluate customer segment contribution          | Which customer segments contribute the most to revenue?                  |
| Assess inventory efficiency                     | Which products are frequently out-of-stock?                              |
| Analyze operating expenses                      | How do expenses affect store profitability?                              |
| Identify operational improvement opportunities   | What processes or stores require operational improvement?                |

---

## 📊 Dataset Description

| Dataset          | Description                       | Business Purpose                    |
|------------------|-----------------------------------|-------------------------------------|
| Sales            | Transaction-level sales records    | Revenue and profit analysis         |
| Customers        | Customer segment information       | Customer contribution analysis       |
| Inventory        | Product stock levels              | Inventory efficiency and stock risk analysis |
| Operating Expenses| Store operating costs             | Cost and profitability analysis     |
| Date             | Transaction date information      | Time-based trend analysis           |

---

## ⛪ Data Structure and Mapping

### 🔗 Data Model Design

The project uses a **Star Schema Model**, standard in Business Intelligence analytics.

### ⭐ Fact Table

**Sales Table** – the central table containing measurable business events.  
**Key metrics:**
- Revenue
- Cost
- Profit
- Quantity Sold

### 📐 Dimension Tables

- **Customers**: Customer ID, Customer Segment
- **Inventory**: Product ID, Product Name, Category, Stock Level
- **Expenses**: Store ID, Operating Expenses
- **Date**: Date, Month, Quarter, Year

### 🔄 Table Relationships

| From   | To       | Relationship   |
|--------|----------|----------------|
| Sales  | Customers| customer_id    |
| Sales  | Inventory| product_id     |
| Sales  | Expenses | store_id       |
| Sales  | Date     | date           |

---

## 🎯 Business Value of Data Model

- Accurate KPI calculation
- Efficient dashboard development
- Scalable business analysis
- Clear performance tracking across stores, products, and customers

---

## 🔧 Data Preparation Process

Data cleaning and preparation were performed using Excel:
- Removed duplicates
- Handled missing values
- Standardized store names
- Verified data accuracy
- Created calculated columns:
  - Profit \(= \text{Revenue} − \text{Cost}\)
  - Profit Margin \(= \frac{\text{Profit}}{\text{Revenue}}\)

---

## 📈 KPI Development

KPIs created include:
- Total Revenue
- Total Profit
- Profit Margin
- Revenue & Profit by Store
- Revenue & Profit by Product
- Inventory Levels
- Operating Expense Ratio

---

## 📊 KPI Results Summary

| KPI              | Result |
|------------------|--------|
| Total Revenue     | ₦      |
| Total Profit      | ₦      |
| Profit Margin     | %      |
| Best Store        |        |
| Worst Store       |        |

---

## 📊 Data Analysis Method

Analysis performed using Excel:
- Pivot Tables
- Pivot Charts
- Dashboard

**Focus areas:**
- Store Performance
- Product Performance
- Customer Contribution
- Inventory Risk
- Cost Structure

*Power BI (planned) for interactive dashboards.*

---

## 📉 Key Insights

- Insight 1: …
- Insight 2: …
- Insight 3: …

---

## 💡 Business Recommendations

**Recommendation 1:** Improve Inventory Management
- Increase stock levels for fast-selling products
- *Expected impact:* Reduce stockouts, increase revenue

**Recommendation 2:** Reduce Operating Costs
- Review high-cost stores
- *Expected impact:* Improve profit margin

**Recommendation 3:** Promote High-Performing Products
- Focus marketing and stock on top products
- *Expected impact:* Increase overall profitability

**Recommendation 4:** Improve Underperforming Store Performance
- Investigate operational inefficiencies
- *Expected impact:* Improve store performance

---

## 📊 Dashboard

Excel dashboard includes:
- Revenue Overview
- Profit Overview
- Store Performance
- Product Performance
- Inventory Analysis

*File Location:* `/dashboard/dashboard.xlsx`

---

## 📁 Project Files Structure

``
Prime-Mart-Analysis/
├── README.md
├── data/
│ └── dataset.xlsx
├── dashboard/
│ ├── dashboard.xlsx
│ └── dashboard.png

``

---

## 🧠 Business Analyst Skills Demonstrated

- Problem Definition
- KPI Development
- Insight Generation
- Business Question Formulation
- Excel (Pivot Tables, Formulas, Dashboard)
- Data Cleaning & Preparation
- Power BI (Planned)
- Analytical Thinking & Problem Solving

---

## 💼 Business Value Delivered

- Visibility into revenue and profit performance across stores
- Identification of high-performing and underperforming areas
- Highlighted operational inefficiencies
- Provided actionable, data-driven recommendations

---

## 🎯 Project Outcome

- Analyze business data effectively
- Build dashboards
- Generate actionable insights
- Support informed decision-making

---

## 📌 Portfolio Purpose

Demonstrates readiness for Business Analyst roles with practical retail business scenario analysis.

---

## 📬 Contact Information

**Haruna Ademoye**  
- GitHub: [https://github.com/yourusername](https://github.com/yourusername)  
- LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  
- Email: your@email.com
