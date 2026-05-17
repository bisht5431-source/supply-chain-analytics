# supply-chain-analytics

# 📦 Supply Chain Management Dashboard — Power BI

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Supply%20Chain-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Currency-INR%20₹-orange?style=for-the-badge" />
</p>

---

## 📌 Project Overview

This **Supply Chain Management Dashboard** is an interactive Power BI report designed to give end-to-end visibility into supplier performance, product costs, quality inspection outcomes, and revenue distribution across multiple locations in India. It empowers supply chain managers and business analysts to make **data-driven decisions** through dynamic filtering and rich visual storytelling.

The dashboard covers three major product categories — **Cosmetics**, **Haircare**, and **Skincare** — and tracks KPIs from five suppliers (**S1 through S5**) across cities including **Bangalore, Chennai, Mumbai, Delhi, and Kolkata**.

---

## 🖥️ Dashboard Preview

<img width="1305" height="727" alt="Screenshot 2026-05-17 125613" src="https://github.com/user-attachments/assets/93e04115-a1fc-4caa-80f8-86ec30cee9fc" />


---

## 🎯 Key Performance Indicators (KPIs)

| 📊 Metric | 💡 Value | 📝 Description |
|---|---|---|
| 💰 **Total Cost** | ₹1.73M | Overall procurement cost across all suppliers and locations |
| 📅 **Avg Monthly Orders** | 28.57 | Average number of orders placed per month |
| 📦 **Ordered Quantity** | 10K | Total quantity of products ordered |
| 🗓️ **Daily Orders** | 1.00 | Average number of orders placed per day |

---

## 🔍 Dashboard Features & Visualizations

### 1️⃣ Product Category Filter (Slicer)
- **Options:** Cosmetics | Haircare | Skincare
- Allows users to dynamically filter all visuals based on the selected product category for focused analysis.

---

### 2️⃣ SKU Count by Supplier 📊

> *"What's the SKU count from each supplier?"*

| 🏭 Supplier | 🔢 SKU Count |
|---|---|
| S1 | 56.00 |
| S5 | 42.00 |
| S2 | 40.00 |
| S4 | 36.00 |
| S3 | 26.00 |

- **Insight:** Supplier **S1 leads** with the highest number of SKUs (56), indicating the widest product catalog, while **S3 has the lowest** footprint at 26 SKUs.

---

### 3️⃣ Best Lead Time by Supplier ⏱️

> *"Which supplier has the best lead time (days)?"*

| 🏭 Supplier | ⏳ Lead Time (Days) |
|---|---|
| S3 | 26.8 ✅ *(Fastest)* |
| S2 | 28.6 |
| S1 | 28.7 |
| S5 | 29.2 |
| S4 | 29.6 *(Slowest)* |

- **Insight:** **S3 delivers the fastest** with an average lead time of just 26.8 days. **S4 has the longest** lead time at 29.6 days, which may require buffer stock planning.

---

### 4️⃣ Products Supplied by Supplier 🏷️

> *"Which Supplier supplied the most products?"*

| 🏭 Supplier | 📦 Products Supplied |
|---|---|
| S1 | 2.46K ✅ *(Highest)* |
| S5 | 2.15K |
| S2 | 2.11K |
| S4 | 1.78K |
| S3 | 1.26K *(Lowest)* |

- **Insight:** **S1 is the highest volume supplier**, contributing ~19.4% of total product supply. S3, despite being the fastest in lead time, supplies the fewest products.

---

### 5️⃣ Defect Rate by Inspection Result 🔍

A **donut chart** breaking down quality inspection outcomes:

| 🔎 Inspection Status | 📉 Defect Rate | 📊 Share |
|---|---|---|
| ❌ Fail | 2.95 | 32.11% |
| ✅ Pass | 3.24 | 35.28% |
| ⏳ Pending | 2.99 | 32.6% |

- **Insight:** With **35.28% passing** and **32.11% failing**, quality control is a critical area. Nearly **one-third of inspections are still pending**, suggesting a need to accelerate the inspection pipeline.

---

### 6️⃣ Revenue by Supplier 💵

| 🏭 Supplier | 💰 Revenue |
|---|---|
| S1 | ₹0.19M ✅ *(Top Earner)* |
| S2 | ₹0.15M |
| S5 | ₹0.12M |
| S4 | ₹0.11M |
| S3 | ₹0.09M *(Lowest)* |

- **Insight:** **S1 not only supplies the most SKUs** but also generates the **highest revenue**, making it the most strategically important supplier. **S3 contributes the least revenue** despite having the best lead time.

---

### 7️⃣ Total Cost & Unit Cost by Supplier Across Locations 🗺️

A detailed **cross-tab matrix** showing supplier costs broken down by city:

| 🏭 Supplier | 📍 Bangalore Total Cost | 📍 Bangalore Unit Cost | 📍 Chennai Total Cost | 📍 Chennai Unit Cost |
|---|---|---|---|---|
| S1 | ₹97,316.71 | ₹2,454.81 | ₹1,02,698.77 | ₹2,725.07 |
| S2 | ₹26,973.50 | ₹820.77 | ₹62,131.20 | ₹1,475.04 |
| S3 | ₹11,178.00 | ₹372.60 | ₹65,807.18 | ₹1,374.58 |
| S4 | ₹78,936.87 | ₹1,408.22 | ₹37,771.56 | ₹639.20 |
| S5 | ₹59,127.51 | ₹1,605.99 | ₹77,903.83 | ₹1,826.33 |
| **Total** | **₹2,73,532.59** | **₹6,662.39** | **₹3,46,312.54** | **₹8,040.22** |

- **Insight:** **Chennai has a higher total cost** than Bangalore across all suppliers. **S2 and S3 maintain lower unit costs**, making them cost-efficient options for specific locations.

---

### 8️⃣ Revenue by Location and Product Type 🌍

A **stacked area / flow chart** visualizing revenue contributions across five cities:

| 📍 City | 🏆 Highlights |
|---|---|
| Kolkata | Comparable revenue across all 3 product types |
| Chennai | Significant Haircare and Skincare contribution |
| Mumbai | Well-distributed revenue mix |
| Delhi | Strong presence of all product types |
| Bangalore | Balanced across Cosmetics, Haircare, Skincare |

- 🔵 Cosmetics &nbsp; 🔷 Haircare &nbsp; 🟠 Skincare

---

### 9️⃣ Average Unit Cost by Supplier & Product Type 📦

A **grouped bar chart** comparing average unit cost across suppliers for each product type:

| 🏭 Supplier | 🧴 Cosmetics | 💆 Haircare | 🌿 Skincare |
|---|---|---|---|
| S5 | ~200 | ~170 | ~190 |
| S3 | ~200 | ~160 | ~185 |
| S1 | ~180 | ~175 | ~190 |
| S2 | ~185 | ~165 | ~180 |
| S4 | ~175 | ~155 | ~170 |

- **Insight:** **Cosmetics consistently commands the highest unit cost** across all suppliers. **S4 offers the lowest average unit cost**, making it attractive for bulk procurement in cost-sensitive categories.

---

## 🗂️ Data Model Summary

| 🗃️ Field | 📋 Description |
|---|---|
| `Supplier` | Supplier identifier (S1–S5) |
| `Location` | City of operation (Bangalore, Chennai, Mumbai, Delhi, Kolkata) |
| `Product_Type` | Category — Cosmetics, Haircare, Skincare |
| `Total_Cost` | Total procurement cost per transaction |
| `Unit_Cost` | Cost per unit of product |
| `SKU` | Stock Keeping Unit count |
| `Lead_Time` | Days taken for delivery |
| `Ordered_Quantity` | Total units ordered |
| `Revenue` | Revenue generated per supplier |
| `Inspection_Result` | Quality check outcome — Pass / Fail / Pending |
| `Defect_Rate` | Rate of product defects identified during inspection |

---

## 🛠️ Tools & Technologies

| 🔧 Tool | 💡 Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard design, data modeling, and publishing |
| **DAX (Data Analysis Expressions)** | Custom measures and calculated columns |
| **Power Query (M Language)** | Data transformation and ETL |
| **Excel / CSV** | Source data format |

---

## 📁 File Structure

```
📂 Supply-Chain-Management/
│
├── 📊 supply_chain.pbix          # Main Power BI report file
├── 🖼️  dashboard_preview.png     # Dashboard screenshot
└── 📄 README.md                  # Project documentation (this file)
```

---

## 🔑 Key Business Insights

> A summary of the most critical findings from this dashboard:

1. 🥇 **S1 is the most valuable supplier** — highest SKU count, most products supplied, and highest revenue generated.
2. ⚡ **S3 offers the fastest delivery** but contributes the least revenue, suggesting a niche or limited product catalog.
3. ⚠️ **Quality is a concern** — over 32% of inspections result in failure, and another ~32.6% are still pending.
4. 💸 **Chennai is the highest-cost location** for procurement, while unit costs vary significantly by supplier.
5. 📊 **Cosmetics has the highest average unit cost** across all suppliers and locations.
6. 🏙️ **Mumbai and Delhi** show strong revenue performance across all three product categories.
7. 🔄 **S4 has the longest lead time** — inventory planning should account for this delay.

---

## 🚀 How to Use This Dashboard

1. **Download** the `supply_chain.pbix` file from this repository.
2. **Open** it with [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download).
3. Use the **Product Category slicer** (Cosmetics / Haircare / Skincare) at the top to filter all visuals simultaneously.
4. **Hover** over any chart element for detailed tooltips.
5. **Click** on any bar, segment, or data point to cross-filter related visuals.

---

## 📈 Future Enhancements

- [ ] 🔗 Connect to a **live database** or **SharePoint** for real-time data refresh
- [ ] 📧 Set up **Power BI scheduled refresh** and automated email alerts
- [ ] 🌐 Publish to **Power BI Service** for online collaboration
- [ ] 📱 Build a **mobile-optimized layout** for field teams
- [ ] 🤖 Integrate **AI-powered Q&A** feature using Power BI's natural language query
- [ ] 🗺️ Add **geographic map visuals** to better represent city-level distribution
- [ ] 📉 Include **trend analysis** with time-series forecasting for demand planning

---

## 👤 Author

**Manish Bisht**
📧 bisht5431@gmail.com
🔗 [LinkedIn Profile](https://linkedin.com/in/dataanalyst-manish)
🐙 [GitHub Profile](https://github.com/bisht5431-source)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

<p align="center">
  ⭐ If you found this project helpful, please consider giving it a star on GitHub! ⭐
</p>
