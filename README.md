# Internal Audit Dashboard – Defect Analysis using Excel

This project showcases a dynamic **Excel dashboard** that analyzes internal audit data. It focuses on identifying **task-level defects**, understanding **root causes**, and offering **KPI summaries** for key stakeholders to take action.


## Dataset Overview

The anonymized dataset contains internal audit entries across 6 weeks, including:

- **Task ID**
- **Week No**
- **Queue Type** (BAV, BOV, IDV, SU)
- **Primary Root Cause**
- **Investigator Login**
- **Dispute Status** (Accepted / Disputed)

All sensitive or confidential data has been anonymized for public presentation.


## Key Features

| Feature                          | Description |
|----------------------------------|-------------|
| **Weekly Defect Trend**         | Pivot-based column chart showing week-wise defect count with slicers to filter by queue. |
| **Disputes vs Acceptance**      | Stacked bar chart tracking acceptance vs disputes by investigator with slicers for queue and week. |
| **Root Cause Heatmap**          | Matrix view of defect drivers across task types and queues, color-coded using conditional formatting. |
| **SU Queue Deep Dive**          | Separate pivot and heatmap for high-volume SU queue root causes. |
| **KPI Summary Page**            | Displays metrics like: Most defected week, most disputed investigator, task with highest defects, etc. |
| **Dynamic Dashboard Page**      | All visualizations integrated into one clean, interactive dashboard using slicers and charts. |


## Tools & Concepts Used

- **Microsoft Excel 365**
- **Pivot Tables & Pivot Charts**
- **Slicers for Filtering**
- **Conditional Formatting (3-color heatmaps)**
- **COUNTIF, TEXT formulas**
- **Manual Sorting & KPI Derivation**
- **Dashboard Layout Design**


## Learning Outcomes

- Built an Excel dashboard from scratch using operational audit data
- Identified task-level root causes and dispute patterns
- Learned to apply conditional formatting and slicers for interactivity
- Designed polished visual reports aligned with audit KPIs
- Created a resume-worthy project aligned with data/operations analytics


## File Structure

├── Internal_Audit_Dashboard.xlsx # Main Excel project file with all dashboards, charts, and summaries
├── README.md # Documentation explaining project context, features, and learnings


## Signature & Ownership

> **Internal Quality Audit – July 2025**  
> *Created by Akshaya*
