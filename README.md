# Power-BI-Customer-Buying-Habits-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.customer-buying-habits?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/-tZwalVAdAs/0.jpg)](https://youtu.be/-tZwalVAdAs?si=7S-avQH2fLWPF7V8)  

---

## Overview  

In today’s competitive sales landscape, understanding how and when customers make purchasing decisions is essential to driving revenue growth and retention. The **Customer Buying Habits Dashboard** provides sales teams and leadership with a clear view of customer purchasing trends—such as frequency, deal size, quoting behavior, and sales cycle length—helping prioritize high-value accounts and refine engagement strategies.  

This Power BI app transforms raw sales and quotation logs into actionable intelligence to boost sales timing, segment customers effectively, and reduce churn risk.  

---

## Technical Framework  

The dashboard is powered by a single structured table titled **Customer Habits**, capturing customer-level sales and quoting metrics.  

**Key components:**  
- **Data Source:** Excel sheet or system-exported table with customer sales behavior and quoting records  
- **Data Preparation (Power Query):**  
  - Clean dates, text, and numeric fields  
  - Calculate average sales cycle time  
  - Categorize deal sizes and purchase frequency  
  - Enable segment-level aggregations  
- **Data Model Dimensions:**  
  - Customer ID  
  - Deal Size Category (Small, Medium, Large)  
  - Purchase Frequency (Monthly, Quarterly, Annually)  
  - Last Purchase Date  
  - Average Sales Cycle (Days)  
  - Open Quote Value  
  - Average Deal Size  
  - Previous Orders  

This model supports segmentation, customer targeting, and CRM integration.  

---

## Interactive Filters  

The dashboard includes intuitive slicers to support strategic analysis:  
- **Purchase Frequency Filter:** Identify customers with recurring, seasonal, or one-off purchase behavior  
- **Deal Size Filter:** Focus on high-value or high-volume segments  

Filters dynamically update all visuals, enabling smarter sales prioritization and outreach planning.  

---

## Dashboard Highlights  

**KPI Tiles – Buying Behavior Summary**  
Top-level metrics to assess customer engagement across the base:  
- “How Many Customers Prioritize Quality?” – (Logic customizable via behavioral thresholds)  
- Average Sales Cycle Days – Mean time from quote to deal closure  
- Total Value of Open Quotes – Quoting pipeline value  

**Customer Behavior Table**  
Detailed view of each customer’s buying pattern, including:  
- Deal Size and Frequency  
- Last Purchase Date  
- Sales Cycle Length  
- Open Quote Value  
- Average Deal Size  
- Previous Orders  

Used to identify churn risks, cross-sell opportunities, or high-priority follow-ups.  

This dashboard empowers sales organizations to act on real customer behavior—driving better segmentation, engagement timing, and revenue forecasting through data-backed insights.  

---

## Screenshots  

### Dashboard Overview 
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Customer-Buying-Habits-App/blob/main/docs/dashboard_overview.png?raw=true)   

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.customer-buying-habits?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

Understanding customer buying habits enables smarter segmentation, precise engagement timing, and optimized sales strategies. This dashboard empowers sales teams to reduce churn, strengthen relationships, and boost revenue by acting on real behavioral insights.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
