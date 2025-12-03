# Supply-Chain-Dashboard-End-to-End-Logistics-Operations-Analytics
Python and Power BI Project on Supply Chain
Project Overview

This project presents an interactive Supply Chain Analytics dashboard built using Power BI, supported by Google Colab for data cleaning, preprocessing, and exploratory visualizations.
It provides clear insights into revenue, production volume, cost distribution, supplier performance, logistics efficiency, and transportation effectiveness.
The dashboard enables supply chain managers and decision-makers to identify bottlenecks, optimize processes, and improve overall operational efficiency.

Technology Stack
Google Colab
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)

Project Structure
Supply-Chain-Dashboard/
│
├─ Colab/
│   ├─ data_cleaning.ipynb         # Raw data import, cleaning, preprocessing, EDA
│   ├─ feature_engineering.ipynb   # Feature creation and transformation
│   └─ exploratory_visuals.ipynb   # Trend charts and initial insights
│
├─ PowerBI/
│   ├─ Dashboard.pbix               # Final interactive Power BI dashboard
│   ├─ PowerQuery_Transformations.pq # Additional data shaping scripts
│   └─ DAX_Measures.txt             # DAX formulas for KPIs and metrics
│
├─ Data/
│   ├─ raw_data.csv                 # Original supply chain dataset
│   └─ processed_data.csv           # Cleaned and transformed dataset
│
└─ README.md                        # Project documentation


Key Insights & Dashboard Highlights
1. Overall Supply Chain Performance

Total Revenue: 577.60K
Total Units Sold: 46K
Production Volume: 57K
Total Cost: 52.92K
Average Price: 49.46
Average Shipping Time: 5.75 days
Insight: Strong volume and revenue patterns indicate efficient production with controlled operational costs.

2. Product Type Analysis
Revenue and units sold vary significantly across product categories
Top-performing product types are easily identified
Insight: Supports production planning and inventory prioritization.

3. Supplier Performance
Supplier 1 handles the largest shipment volume
Supplier 3 offers the fastest shipping time
Insight: Optimizes supplier selection based on speed, cost, and reliability.

4. Manufacturing, Lead & Shipping Time Trends
Manufacturing time is consistent
Lead time and shipping time fluctuate
Insight: Opportunities exist to optimize logistics rather than production processes.

5. Quality Inspection Analysis
Most items pass QA checks
Pending and “Check” items indicate minor quality issues
Insight: Enables continuous improvement in QA processes.

6. City-Level Performance
Top locations by revenue and units sold: Mumbai & Nagpur
Highest average price: Bangalore
Insight: Helps refine supply chain routing and regional strategies.

7. Transportation Mode Efficiency
Air → Fastest
Sea → Slowest
Rail/Road → Moderate
Insight: Guides optimal transport mode selection based on urgency and cost.

