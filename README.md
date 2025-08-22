
# Supply Chain Operations & Automation Project | Amazon Operations Case Study

## 📌 Overview
This project replicates Amazon's supply chain operations using modern data tools. 
It integrates **Supabase (Postgres DB)**, **n8n.io (workflow automation)**, **Quadratic AI (analytics)**, and **APIs** to build an automated pipeline for supply chain insights.

## ⚙️ Tools & Technologies
- **Supabase (Postgres DB):** For structured data storage (orders, customers, products).  
- **n8n.io:** Workflow automation for alerts, notifications, and data pipelines.  
- **Gmail API OAuth:** Automated email notifications for supply chain exceptions.  
- **Quadratic AI:** Business insights and KPI analysis.  
- **Python & APIs:** Data cleaning, transformation, and exchange rate integration.  

## 🗂️ Data Pipeline Workflow
1. **Database Setup (Supabase):**  
   - Created schema with tables (`fact_order_line`, `dim_products`, `dim_customers`, etc.).  
   - Imported CSVs and updated datatypes for consistency.  

2. **Automation (n8n.io):**  
   - Integrated Gmail API with OAuth for automated email alerts.  
   - Automated workflows for supply chain exception handling (delays, undelivered orders).  

3. **Data Processing (Python + APIs):**  
   - Cleaned and merged datasets (orders, products, customers, exchange rates).  
   - Converted order values into INR using exchange rate API.  

4. **Analytics (Quadratic AI):**  
   - Revenue loss due to undelivered orders.  
   - On-Time, In-Full (OTIF) discrepancies by customer.  
   - Product categories with delivery bottlenecks.  
   - Average delay time for late deliveries.  

## 📊 Supply Chain KPIs
- **Line Fill Rate** = Fulfilled lines / Total lines.  
- **Volume Fill Rate** = Quantity shipped / Quantity ordered.  
- **On-Time Delivery %** = Orders delivered on/before promised date.  
- **In-Full Delivery %** = Orders delivered with full quantities.  
- **OTIF %** = Orders delivered both on-time and in-full.  

## 🚀 Business Impact
- Built a **data-driven operations dashboard** highlighting supply chain reliability.  
- Identified **top customers, order performance, and critical supply bottlenecks**.  
- Improved decision-making by automating insights and notifications for stakeholders.  

---
🔗 *Project inspired by Codebasics Supply Chain Resume Challenge.*
