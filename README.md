# 📦 Amazon Supply Chain Operations & Automation Project

## 🚀 Overview

This project automates and analyzes Amazon-style supply chain operations by leveraging:

- **Supabase** (PostgreSQL backend)  
- **n8n.io** (Workflow automation)  
- **Quadratic** (Spreadsheet-like data analysis)  
- **Gmail API**, **CSV ingestion**, and **Python preprocessing**  

The pipeline helps monitor KPIs such as **OTIF %**, **Line Fill Rate**, **Volume Fill Rate**, and **Delivery Delays**, mimicking real-world warehouse and distribution metrics used at Amazon.

---

## 🧠 Key Features

✅ Automated Data Ingestion from different regions (US, Ahmedabad, Vadodara) via CSV files  
✅ AI Workflow Automation using n8n.io to parse and insert data into Supabase DB  
✅ Data Modeling with normalized tables for orders, products, and customers  
✅ Business Insights generation with Quadratic to uncover delivery bottlenecks and revenue loss  
✅ Supply Chain KPI Dashboards using industry-standard metrics  

---

## 🛠️ Technologies Used

| Tool        | Purpose                                           |
|-------------|---------------------------------------------------|
| **n8n.io**  | Automation of Gmail → CSV → Supabase flow         |
| **Supabase**| PostgreSQL-based backend                          |
| **Quadratic**| Spreadsheet + Code for insight generation        |
| **Gmail API**| Trigger for incoming order files                 |
| **Python**  | Data cleaning and transformation                  |

---

## 🖼️ Architecture Diagrams

### 🔄 End-to-End Supply Chain Automation Pipeline (CSV → n8n → Supabase → Quadratic)

![End-to-End Supply Chain Automation Pipeline](./assets/pipeline-overview.png)

> CSV files from multiple regions (US, Ahmedabad, Vadodara) are automatically ingested, processed using `n8n`, and pushed to **Supabase**. Final analysis is done in **Quadratic**.

---

### 🔁 n8n Supply Chain Automation Workflow

![n8n Supply Chain Automation Workflow](https://raw.githubusercontent.com/<YOUR-USERNAME>/<YOUR-REPO>/<BRANCH>/assets/n8n%20Supply%20Chain%20Automation%20Workflow.png)


> Workflow includes Gmail Trigger → CSV Extraction → Supabase Row Insertion. Data is routed dynamically based on file content.

---

## 📊 KPIs Tracked

- **On-Time Delivery % (OT)**  
- **In-Full % (IF)**  
- **OTIF %** (On-Time In-Full)  
- **Line Fill Rate**  
- **Volume Fill Rate**  
- **Average Delay in Delivery**  
- **Revenue Loss from Undelivered Orders** 

---
