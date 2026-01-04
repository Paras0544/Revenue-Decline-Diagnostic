# 📉 Revenue Decline Diagnostic  
### E-commerce Analytics & Business Diagnostics Project

---

## 📌 Project Overview

This project performs a **diagnostic analysis** to identify the **root causes of revenue decline** in a simulated e-commerce business using **Python, SQL, and Power BI**.

The analysis follows a **consulting-style problem-solving framework**, moving systematically from  
**symptom → diagnosis → insight → recommendation**, similar to real-world analytics and strategy engagements.

---

## 🎯 Business Problem

An e-commerce company observed a **sharp decline in revenue during the latter half of 2023**, despite relatively stable order volumes.

The objective of this project was to determine whether the revenue decline was driven by:

- Demand reduction  
- Pricing or discount strategy  
- Customer behavior (new vs repeat customers)  
- Operational issues (returns, cancellations, delivery delays)  
- Geographic or category-level performance  

---

## 🧠 Diagnostic Framework

The analysis was conducted using a structured diagnostic approach:

1. **Trend Analysis**  
   Revenue and order volume trends over time  

2. **Customer Segmentation**  
   Contribution of new vs repeat customers  

3. **Operational Leakage Analysis**  
   Revenue loss due to returns and cancellations  

4. **Category Performance**  
   Revenue distribution across product categories  

5. **Geographic Analysis**  
   City-wise revenue and order concentration  

6. **Operational Efficiency**  
   Impact of delivery time on order outcomes  

---

## 🛠️ Tech Stack

- **Python** – Data generation and preprocessing  
- **Pandas / NumPy** – Data manipulation and analysis  
- **SQL** – Diagnostic queries and aggregations  
- **Power BI** – Interactive dashboards and storytelling  
- **Git & GitHub** – Version control and documentation  

---

## 📂 Project Structure
Revenue-Decline-Diagnostic/
│
├── data/
│   ├── raw/                # Empty (data generated via notebook)
│   └── processed/          # Generated CSV (ignored in Git)
│
├── notebooks/
│   └── 01_revenue_decline_diagnostic.ipynb
│
├── sql/
│   └── 01_revenue_diagnostic_queries.sql
│
├── dashboard/
│   └── revenue-decline-diagnostic-dashboard.pbix
│
├── .gitignore
└── README.md


---

## 📊 Power BI Dashboard Preview

The Power BI dashboard presents a **structured, diagnostic view** of revenue decline across time, customers, operations, and geography.

---

### Page 1 – Executive Overview

**Purpose:**  
Provide leadership with a high-level snapshot of the revenue decline.

**Key Metrics & Insights:**
- Total Revenue  
- Total Orders  
- Average Order Value (AOV)  
- Revenue Loss % (Returns & Cancellations)  
- Monthly Revenue Trend (Jul–Dec 2023)

![Executive Overview](dashboard/images/page1_executive_overview.png)

---

### Page 2 – Revenue Leakage & Customer Behavior

**Purpose:**  
Identify where revenue is being lost and assess demand-side risks.

**Key Metrics & Insights:**
- Revenue by Order Status (Delivered, Returned, Cancelled)  
- Revenue Contribution: New vs Repeat Customers  
- Monthly Repeat Orders Trend  

![Revenue Leakage & Customer Behavior](dashboard/images/page2_revenue_leakage.png)

---

### Page 3 – Operational & Geographic Analysis

**Purpose:**  
Diagnose operational inefficiencies and regional concentration risks.

**Key Metrics & Insights:**
- Average Delivery Time by Order Status  
- Revenue by City  
- Orders by City  
- Revenue Concentration Across Top Cities  

![Operational & Geographic Analysis](dashboard/images/page3_operations_geography.png)

---

## 🔍 Key Insights

- Revenue decline post-September is **not demand-driven**; order volumes remain relatively stable  
- **Returns and cancellations increased**, causing significant revenue leakage  
- **Repeat customer contribution remains strong**, indicating retained customer trust  
- Revenue is **highly concentrated in the top 3 cities**, increasing geographic risk  
- **Longer delivery times correlate with non-delivered orders**, highlighting operational inefficiencies  

---

## 💡 Business Recommendations

- Improve delivery SLAs to reduce returns and cancellations  
- Audit operational bottlenecks introduced after September  
- Diversify revenue sources beyond top-performing cities  
- Review discounting strategies impacting margins  
- Strengthen retention initiatives focused on repeat customers  

---

## 🚀 How to Run the Project

1. Run the Jupyter notebook to generate and analyze the data:

2. Open the Power BI dashboard:

---

## 📈 Skills Demonstrated

- Business problem structuring  
- Diagnostic analytics mindset  
- SQL-based insight generation  
- Power BI dashboard storytelling  
- End-to-end analytics workflow  

---

## 📬 Author

**Paras Miglani**  

