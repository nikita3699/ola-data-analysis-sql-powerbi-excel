# 📊 OLA Data Analytics – July 2024 Operations

## 📌 Brief One-Line Summary
Analyzed 100K+ booking records using Excel, SQL Server, and Power BI to uncover insights on cancellations, revenue, ratings, and vehicle performance, driving operational efficiency and customer satisfaction.

---

## 📖 Overview
This project evaluated OLA’s July 2024 booking operations to identify inefficiencies in cancellations, incomplete rides, and vehicle performance. A complete analytics workflow was built using Excel for cleaning and validation, SQL Server for advanced queries and analysis, and Power BI for interactive dashboards and KPI visualization.

---

## ❗ Business Problem
Booking platforms face challenges in balancing customer satisfaction, driver performance, and operational efficiency. This project aimed to:
- Reduce high cancellation rates by identifying root causes.
- Improve visibility into vehicle-wise performance and revenue streams.
- Track incomplete rides and their reasons.
- Provide actionable insights into customer and driver ratings.
- Automate reporting to reduce manual effort.

---

## 📂 Dataset
- **Source**: Single CSV file (`ola_bookings.csv`) containing booking, ride, payment, and rating information.  

---

## 🛠️ Tools & Technologies
- **Excel** → Data cleaning, reconciliation, validation  
- **SQL Server** → Advanced queries, aggregations, trend analysis  
- **Power BI** → Interactive dashboards, DAX measures, KPI visualization  

---

## 🧹 Data Cleaning & Preparation
- Removed duplicates and standardized date/time formats  
- Applied Excel functions (`TRIM`, `CLEAN`, `SUBSTITUTE`) to sanitize text fields  
- Used reconciliation formulas (`IFERROR`, `INDEX-MATCH`, `XLOOKUP`) to validate IDs and totals  
- Ensured consistency in payment methods and cancellation reasons  

---

## ❓ Research Questions & Key Findings
- Which vehicle types generate the highest booking value? → Prime Sedan, Prime Plus, and Auto  
- What are the top cancellation drivers? → Driver-related personal issues and customer dissatisfaction with driver movement  
- How do payment methods impact revenue? → Heavy reliance on Cash and UPI  
- Are ratings consistent across vehicle types? → Yes, ~4.0 average, with minor variation  
- Which customers contribute most to revenue? → Top 5 customers accounted for ~32K in booking value  

---

## 📊 Dashboard
Power BI Dashboard shows:
- Booking Volume Over Time  
- Booking Status Breakdown  
- Vehicle Type Performance (distance, booking value, success rate)  
- Revenue by Payment Method  
- Cancellation Reasons (customer vs driver)  
- Ratings Distribution (driver vs customer)  
- Top 5 Customers by Booking Value  

---

## ▶️ How to Run This Project
1. Load raw booking and revenue data into Excel for cleaning  
2. Import cleaned data into SQL Server  
3. Run SQL scripts for analysis (successful bookings, cancellations, revenue, ratings)  
4. Connect Power BI to SQL Server and Excel outputs  
5. Open Power BI dashboard file:  
   - `dashboard/ola_analytics_dashboard.pbix`  
6. Schedule refreshes in Power BI for automated reporting  

---

## 📈 Results & Conclusion
- Reduced customer cancellations to **<7%**  
- Reduced driver cancellations to **<18%**  
- Lowered incomplete rides to **~5%**  
- Boosted weekend order volume and revenue by **15–20%**  
- Delivered actionable insights that improved operational efficiency, enhanced customer satisfaction, and identified top-performing vehicles  
