# 📊 AtliQ Mart - Power BI Supply Chain OTIF Analytics Project

🚀 Welcome to my Power BI-based analytics project!

This project dives into AtliQ Mart’s supply chain performance across key service metrics—**On Time**, **In Full**, and **OTIF** delivery levels. It leverages powerful visuals and interactivity to uncover gaps and opportunities for enhancing customer satisfaction. The goal is to enable timely decisions to retain and grow AtliQ’s customer base before expanding into new cities.

---

## 🧩 Project Context

AtliQ Mart, a growing FMCG company headquartered in Gujarat, is facing a critical challenge in customer retention. Several key customers did not renew their annual contracts due to repeated service failures—primarily delayed or incomplete deliveries. Before expanding into Tier-1 cities, the leadership wants to closely track delivery performance and fix root causes affecting customer satisfaction.

---

## ❓ Problem Statement

Due to delivery service issues—delays and incomplete shipments—AtliQ Mart has lost key customer contracts. The company’s management seeks daily visibility into delivery KPIs: **On Time (OT) %**, **In Full (IF) %**, and **On Time In Full (OTIF) %**, to identify gaps quickly and take corrective actions.

---

## 🗃️ Database Overview

The dataset comprises multiple structured tables:

- **dim_customers**: Contains unique customer IDs, names, and their respective cities.  
- **dim_products**: Includes product IDs, names, and their categories.  
- **dim_date**: Stores daily, weekly, and monthly date information.  
- **dim_targets_orders**: Provides customer-level targets for OT%, IF%, and OTIF%.  
- **fact_order_lines**: Holds detailed information about each line item in customer orders, including product, quantity ordered, and delivery timelines.  
- **fact_orders_aggregate**: Aggregated at the order level, indicating whether an order was delivered on time, in full, or both (OTIF).  

---

## 🛠️ Tools Used

- Power Query (for Data Transformation) 
- CSV Files (as source data)  
- Power BI (for modeling and dashboard development)  

---

## 🔧 What I Did

- Extracted and loaded CSV data into Power BI  
- Transformed data like Column splitting, Dividing columns, etc. 
- **Data Modeling**: Established relationships between fact and dimension tables using keys  
- **DAX Measures**: Created KPIs for On Time %, In Full %, OTIF %, VOFR %, LFR %, etc.  
- **Visualizations**:
  - Built dynamic visuals with slicers for city, customer, and product-level drilldowns  
  - Used KPIs,Bookmarks, Selection Pane, Buttons, and Sparklines for advanced interactivity and clean navigation  

---

## 🌟 Key Highlights

- **Ahmedabad** reported the highest number of deliveries  
- **Surat** achieved the highest OTIF%  
- Ahmedabad also performed well in both **On Time** and **In Full** metrics  
- **Vijay Stores** had the highest order count  
- **Propel Mart** showed best OTIF performance  
- **AM Milk** had the highest demand—evidenced by large order volumes,also high in on-time deliveries and delayed deliveries. 
- **AM Butter** appeared in the most order lines, indicating strong customer preference  
- **AM Curd** achieved high Line Fill Rate, often delivered fully regardless of timing  
- **VOFR %** was consistent across all 6 product categories  
- Root cause of poor OTIF: **stock unavailability**, especially for high-demand SKUs like AM Milk  

---

## 📘 Learnings & Skills Demonstrated

- Created **KPI Cards** to show top-level performance  
- Used **Sparklines** in matrix visuals to show trends over time  
- Leveraged **Bookmarks** ,**Advanced visual formatting**,  **Buttons** to create a clean, interactive navigation experience  
- Gained practical knowledge of **Supply Chain KPIs** and their impact on customer satisfaction  
- Designed advanced **Power BI dashboard** that align with real business requirements  

---

## 💼 Use Case

- Ideal for **beginners and intermediates** looking to practice real-world analytics scenarios using **Power BI**
- Demonstrates how to transform **raw CSV data** into valuable insights for business decision-making  
- Helps in showcasing **data storytelling**, **visual design**, and **interactive dashboarding** skills  
- Applies real supply chain domain logic to solve customer retention challenges with daily performance tracking  

---

## 📁 Repository Contents

- `README.md`: Project overview (this file)  
- `Dashboard.pbix`: Power BI dashboard file  
- `Data/`: Folder containing source CSV files  
- `Screenshots/`: Contains visuals of the dashboard  
- `Insights.txt`: Additional insights and interpretations extracted from the data  

---

## 📬 Connect

I’m always open to learning, exchanging ideas, and growing together with fellow data enthusiasts. Whether it’s feedback, a question, or just a hello—don’t hesitate to reach out!

_"Behind every dataset is a business decision waiting to be made—insight begins when we ask why."_
