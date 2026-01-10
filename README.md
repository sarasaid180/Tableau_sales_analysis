# Tableau Sales Analysis
End-to-end Tableau project: Transforming raw sales data into actionable insights. Includes year-over-year KPI analysis, customer order distribution, and profit-based segmentation


> **[Click here to view the interactive dashboard on Tableau Public](https://public.tableau.com/views/SalesProject_17680787367270/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**



## 🌟 Executive Overview
This project delivers a dual-layered analytical experience designed for retail stakeholders. By bridging the gap between high-level financial KPIs and granular customer behavior, the suite enables data-driven decision-making.

Leveraging Advanced LOD Expressions, Dynamic Parameters, and UX-focused Container Design, I transformed complex sales metrics into an interactive storytelling tool that tracks Year-over-Year (YoY) growth and identifies high-value customer segments.

## 🛠 The Development Lifecycle
### 1. Requirement Analysis
Before touching the data, I defined the core business questions:

- How does our performance in the Selected Year (CY) compare to the Previous Year (PY)?

- Which sub-categories are driving profit versus those just driving volume?

- What is the "loyalty profile" of our customers (how many orders are they actually placing)?

### 2. Strategic Design (Mockups)
I followed a "Design First" approach to ensure a clean, intuitive user experience:

* Visual Mockup: Sketched the placement of KPIs and charts to ensure the most important information (Sales/Profit).

* Container Mockup: Planned the technical layout using tiled and floating containers. This included designing a hidden floating filter menu to maximize screen real estate while maintaining deep drill-down capabilities.

### 3. Visual Development
I built specialized charts focusing on clarity and context:

- KPI BANs: Created with custom CY/PY logic, including Min/Max indicators to show monthly volatility.

- Distribution Histograms: Used FIXED LODs to categorize customers by their order frequency.

-  Dual-Axis Trends: Combined Sales and Profit onto synchronized axes for better correlation analysis.

### 4. Dashboard Assembly & Interaction
The final phase involved bringing the visuals together into two cohesive dashboards:


1.  Dashboard 1: Sales Performance 📊
    - Yearly Comparison: Dynamic KPIs for Sales, Profit, and Quantity vs. the previous year.
    - Sub-Category Drill-down: A side-by-side comparison of sales volume vs. profit margin.
    - Weekly Trendlines: A temporal view with Average Reference Lines to identify weeks of over/under-performance.

2. Dashboard 2: Customer Insights 👥
    - Customer KPIs: Tracking the count of unique customers, Count of orders and average sales per customer.
    - Order Frequency Histogram: A behavioral breakdown showing the count of customers per "number of orders" bin.
    - Profit Leaders: A Top 10 ranking of customers by their net profit contribution.
  

### 🧠 Technical Skills Showcased
- Calculations: Level of Detail (LOD) Expressions, YoY Growth %, Date Functions.

- Interactivity: Parameter Actions, Show/Hide Container Buttons, Tooltip Viz.

- UI/UX: Floating menu design, color consistency, and white-space management.
  


