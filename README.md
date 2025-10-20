# Business Insights 360: Retail and E-commerce Analytics for AtliQ Hardwares

***A Power BI project to unify sales, finance, supply chain, and marketing data for improved transparency, decision-making, and profitability at a fast-growing hardware company.***

Initial iteration of the dashboard, as part of Codebasics Bootcamp: [**BI 360 Version 1**](https://app.powerbi.com/view?r=eyJrIjoiNjcyMDk2ODUtZjBjMy00M2JhLTljNmEtYzVjZGI1YzAwYjEzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


Re-designed dashboard [**Live Dashboard - BI 360 Version 2**](https://app.powerbi.com/view?r=eyJrIjoiYTZmNWEyNGEtZTUzOS00MzhlLWI4ZDQtZTdjMzI4ZTU4YWIyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)



---

### ❗The Problem
- **AtliQ Hardwares**, a fast-growing electronics company (like HP or Dell), sells PCs, keyboards, and printers through both **brick-and-mortar** and **e-commerce** platforms.
- Rapid expansion led to challenges in **data transparency, stakeholder alignment, and profitability tracking**, particularly in the **Latin American market**.
- Competitor **Dell** leveraged advanced analytics for faster, smarter decisions — exposing AtliQ’s heavy reliance on Excel-based, siloed reporting.

To stay competitive and enable faster strategic decision-making, AtliQ decided to **centralize its reporting ecosystem using Power BI**.

---

## 💡 How to Explore this Project

Scroll through this README to explore insights, dashboard structure, and metrics.  


If you’d prefer to skip ahead and see a snapshot of the dashboard directly, jump down to the **Solution** section below. 

---

## 📝 Overview

**GOAL:** Unify data across business functions into an integrated Power BI dashboard that enables executives and department heads to make data-backed decisions for driving profitability and operational efficiency.

**Key Deliverables:**

- **Five function-specific dashboards:**
1.	Sales Analytics
2.	Finance Overview
3.	Marketing Insights
4.	Supply Chain Performance
5. 	Executive Summary

- **Core Outcomes:**

**Goal:** Design a ***self-explanatory dashboard*** for management and the product strategy team.

 - Improve decision transparency and reduce dependency on static Excel reports.
 - Track KPIs across markets, customers, and products.
 - Identify performance gaps and areas for cost optimization.


---

## 🔢 Data Sources

**Primary Source:** SQL Database containing both **dimensional** and **fact** tables.

### **Dimensional Tables**

| Table | Description |
|--------|-------------|
| `dim_customer` | 75 customers across 27 markets and 2 platforms (Brick & Mortar, E-commerce). |
| `dim_market` | 27 markets grouped under 7 sub-zones and 4 regions (APAC, EU, LATAM, etc.). |
| `dim_product` | Product hierarchy by division (P&A, N&S) and category (Internal HDD, Keyboard, etc.). |

### **Fact Tables**

| Table | Description |
|--------|-------------|
| `fact_sales_monthly` | Actual monthly sales transactions. |
| `fact_forecast_monthly` | Forecasted quantities to assess demand accuracy. |
| `freight_cost`, `gross_price`, `manufacturing_cost` | Cost components for margin and profitability analysis. |
| `pre_invoice_deductions`, `post_invoice_deductions` | Adjustments affecting gross-to-net calculations. |

### **Supplementary Excel Data**
- Competitor market share  
- Net sales, gross margin, and profit targets  
- Operating expenses  

---	

## ✅ Solution: Dashboard & Analytics
I developed a **Power BI dashboard suite** integrating SQL and Excel datasets to provide 360° visibility into AtliQ’s performance across all departments.

### **Tools & Techniques**
- Power BI  
- SQL  
- DAX  
- Excel  

### Dashboard

🚀 [**Live Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiYTZmNWEyNGEtZTUzOS00MzhlLWI4ZDQtZTdjMzI4ZTU4YWIyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


![BI 360 Dashboard](https://github.com/architkannan/BI360/blob/main/BI360.gif)



**Dashboard Highlights:**

| Report | Focus | Example KPIs |
|--------|--------|--------------|
| **Finance View** | P&L, key trends, top customers and products across parameters | Net Sales, Gross Margin %, Net Profit % against previous year benchmark |
| **Sales View** | Product & customer-level sales and profitability analysis | Gross Margin vs Total COGS and Gross Margin Variance % against previous year benchmark|
| **Marketing View** | Opex efficiency against Net Profit | Net Profit Variance % against previous year benchmark |
| **Supply Chain View** | Forecast accuracy and error magnitude of inventory | Forecast accuracy, Net error |
| **Executive View** | Consolidated performance summary | Overall sales, profit %, top markets, top products, AtliQ's market share |

---

## 🌟 Impact: Business Outcomes

- Enabled **cross-functional transparency** with unified, interactive dashboards.  
- Improved **forecast accuracy** and **profit tracking** across global markets.  
- Enhanced **executive decision-making** with real-time insights on performance gaps.  
- Created a **data-driven foundation** to compete with Dell’s analytics maturity.

## 📌 Deliverables

- **Power BI Dashboard Suite:** 5 role-based views  
- **Data Model Design:** SQL + Excel integration for centralized reporting  
- **Executive Summary Report:** Profitability & operational KPIs  



## Acknowledgements
[Codebasics](https://codebasics.io/)



---

## Conclusion

This project demonstrates:

1. The ability to integrate multiple datasets for business-wide analytics.  
2. Designing self-service Power BI dashboards for decision-makers.  
3. Driving business value through data visualization and storytelling.    

### **Contact**
If you’d like to discuss this project or collaborate, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/architkannan/) or [email](mailto:architkannan@zohomail.in).


