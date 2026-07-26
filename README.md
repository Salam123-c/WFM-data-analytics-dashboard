# 📊 WFM Data Analytics & Executive Dashboard

## 🖼️ Dashboard Previews

![Monthly Call Volume: Forecast vs Actual](monthly_call_volume.png)

![Shrinkage % vs Service Level % by LOB](shrinkage_vs_service_level.png)

---

## 📌 Business Scenario & Objective

Operational analysis for a multi-client contact center facing **Service Level (SL) decline**, **high call volume variance**, and **elevated shrinkage**.

**Goal:** Clean multi-source data, calculate core operational KPIs, design an executive dashboard, and identify top operational risks.

---

## 📈 Key Company-Wide KPIs

| Metric | Overall Value | Key Impact / Observation |
| :--- | :--- | :--- |
| **Forecast Accuracy** | **41.39%** | Major mismatch between forecasted vs actual call volumes. |
| **Service Level %** | **77.32%** | Below industry standard target (80%). |
| **Total Shrinkage %** | **13.52%** | Combined planned and unplanned shrinkage across sites. |
| **Occupancy %** | **76.82%** | Agent utilization level across logged intervals. |
| **Avg CSAT / QA** | **3.74 / 82.26** | Quality audit score and customer satisfaction benchmarks. |

---

## 🚨 Top Operational Risks Identified

1. **Critical Forecast Accuracy Deficit (~41%):** Under/over-staffing spikes directly driving SL misses.
2. **Unstable Service Levels (~77.3%):** High daily variance risking SLA penalty exposure.
3. **Shrinkage Volatility:** High unplanned shrinkage causing interval-level staffing gaps.
4. **Site & LOB Disparities:** Banking LOB shows the lowest forecast accuracy (~33.1%).

---

## ⚙️ Project Implementation & Methodology

1. **Data Cleaning & QA:** Standardized LOB variants (e.g., `" Retail"`, `"banking"` to canonical categories) and deduplicated repeat agent logs.
2. **Dynamic Calculations:** Modeled KPIs using Excel formulas (`SUMIFS`, `AVERAGEIFS`) for dynamic filtering.
3. **Executive Dashboard:** Built interactive layout supporting LOB and Site slicer filters.

---

## 📁 Repository Files

* 📊 `WFM_Data_Analyst_Assessment.xlsx`: Complete workbook containing cleaned source data, pivot summaries, KPI models, and interactive dashboard layer.
* 🖼️ `assets/`: Contains dashboard previews and key analytical visual snapshots.
* 📝 `README.md`: Project overview, findings, and documentation.
