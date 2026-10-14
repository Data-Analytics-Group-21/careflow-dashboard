# CareFlow - Clinical Pathway Process Mining 🏥

**Oncology Patient Journey Analysis using Process Mining + Power BI**

## 📋 Project Overview
Analyzed clinical event logs of oncology patients to discover actual care pathways, identify bottlenecks, and check conformance with ideal pathway.

## 📁 Repository Structure
- `clinical_event_log.csv` - Raw event log (50+ cases)
- `clinical_event_log_cleaned.csv` - Cleaned data
- `data_cleaning.py` - #2 Data cleaning
- `process_discovery.py` - #3 Patient journey map (Alpha Miner)
- `bottleneck_analysis.py` - #4 Bottleneck detection
- `conformance_checking.py` - #5 Conformance vs ideal
- `variant_analysis.py` - #6 Top 5 variations
- `power_bi_dashboard.py` - #8 KPI + Process Map data
- `power_bi_theme.json` - #9 Dark theme
- `kpi_cards.csv`, `process_map_for_powerbi.csv` - Power BI inputs

## 🔍 Key Findings
- **Total Cases:** 50, **Ideal Conformance:** 85%
- **Bottleneck:** Lab Test -> Treatment Planning (Avg 18 hours delay)
- **Top Variant:** Admission->Diagnosis->Lab->Planning->Therapy->Discharge (60%)
- **Avg Length of Stay:** 5.8 days

## 📊 Power BI Dashboard
- **Page 1:** 4 KPI Cards + Sankey Process Map (Dark Theme)
- **Page 2:** Bottleneck Analysis (Bar chart)
- **Page 3:** Variant & Conformance Analysis
- Theme: Dark #121212, Oncology Blue #0078D4

## 🛠️ Tech Stack
Python, PM4Py, Pandas, Matplotlib, Power BI, GitHub Projects

## 🚀 How to Run
1. `pip install pm4py pandas matplotlib`
2. `python data_cleaning.py`
3. `python power_bi_dashboard.py`
4. Import CSVs into Power BI + apply theme

## 📌 GitHub Project Board
All 10 tasks tracked: Todo -> In Progress -> Done (100% Complete)

**Developed by:** poojithapoojj314-ai | 2024
