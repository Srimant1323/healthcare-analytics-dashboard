# 🏥 Healthcare Analytics Dashboard — Excel
![Dashboard Preview]()

> A clinical monitoring and operational analytics dashboard built entirely in Microsoft Excel,
> analysing **200 patient records** across diagnoses, wards, doctors, and outcomes for the year 2024.

---

## 📌 Project Overview

This project simulates a real-world **hospital data analytics system** of the kind used by clinical administrators, healthcare analysts, and public health teams to monitor day-to-day operational metrics.
The dataset includes patient demographics, diagnosis, treatment, clinical outcome, length of hospital stay, billing amount, and patient satisfaction score. All metrics on the dashboard update automatically from the raw data using Excel formulas.

---

## 📂 File Structure

\`\`\`
healthcare-analytics-dashboard/
└── Healthcare_Dashboard.xlsx      ← Single Excel workbook with 3 sheets
\`\`\`

### Sheet Breakdown

| Sheet | Purpose |
|---|---|
| 🏥 Patient Data | Raw database of 200 patient records — the single source of truth |
| 📊 Summary Metrics | Formula-driven analysis tables by diagnosis, doctor, ward, and outcome |
| 📈 Dashboard | 6 KPI cards + 6 charts for at-a-glance clinical monitoring |
---

## 🧮 Quick Formula Reference Summary

| Formula | Conditions | Used For | Example |
|---|---|---|---|
| `COUNTA` | None | Total patient count | 200 patients |
| `AVERAGE` | None | Overall avg LOS / bill / satisfaction | 7.3 days avg stay |
| `COUNTIF` | 1 condition | Patients per diagnosis / ward / outcome | 22 Diabetes patients |
| `COUNTIFS` | 2+ conditions | Recovered patients per diagnosis | 8 Diabetes + Recovered |
| `AVERAGEIF` | 1 condition | Avg LOS / bill / satisfaction per group | 6.4 days avg for Asthma |
| `AVERAGEIFS` | 2+ conditions | Avg bill for a specific ward + outcome combo | ₹45,200 for ICU + Recovered |
| `IFERROR` | Error handler | Prevent #DIV/0! errors showing in cells | Shows 0 instead of error |

> 💡 **Core logic in one sentence:**
> Filter the patient data by a condition, then count or average a specific column
> for those filtered rows only. That is the foundation of the entire project.

---

## 📈 Dashboard Charts

| Chart | Type | What it Shows |
|---|---|---|
| Patients by Diagnosis | Horizontal Bar | Which diseases have the highest patient volume |
| Patient Outcomes | Pie | Breakdown of Recovered / Improving / Stable / Worsening / Discharged |
| Admissions by Ward | Column | Patient volume across General, ICU, Cardiology, Pediatrics, Neurology |
| Length of Stay Distribution | Column | How many patients stayed 1-2 / 3-4 / 5-6 / 7-9 / 10+ days |
| Avg Satisfaction by Doctor | Horizontal Bar | Which doctor's patients give the highest satisfaction scores |
| Gender Split | Pie | Male vs Female patient distribution |

---


## 🚀 How to Use

1. Download `Healthcare_Dashboard.xlsx`
2. Open in **Microsoft Excel 2016 or later**
3. Start on **📈 Dashboard** tab for the summary view
4. Explore **📊 Summary Metrics** to see all formulas in action
5. All charts and KPIs update automatically if you add or edit records in **🏥 Patient Data**

---

## 👤 Author

**Srimant Bhardwaj**
M.Tech Bioinformatics — Delhi Technological University
GitHub: [github.com/Srimant1323](https://github.com/Srimant1323)
