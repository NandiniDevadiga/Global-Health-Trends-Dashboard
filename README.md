# 🌍 Global Health Trends Dashboard (1975–2016)

An interactive Power BI dashboard analyzing global health trends across **three major conditions** — Raised Blood Pressure, Diabetes, and Obesity (BMI ≥ 30) — spanning over four decades and covering countries worldwide.

---

## 📊 Dashboard Overview

This project consists of **two report pages**:

### Page 1: Global Health Trends
- **Global Prevalence Trends Over Time** — Line chart tracking average prevalence of all three health indicators from 1975 to 2016
- **Men vs Women: Health Condition Comparison** — Horizontal bar chart comparing average prevalence by sex across indicators
- **Share of Health Burden by Condition** — Donut chart showing the proportional burden of each health condition
- **World Health Distribution by Country** — Geographic map visual
- **KPI Cards** — Peak Prevalence (65.32%), Global Average (16.69%), and Lowest Prevalence (0.06%)
- **Interactive Filters** — Toggle between Men/Women, filter by health indicator, and adjust year range (1975–2016)

### Page 2: Country Deep Dive Analysis
- **Prevalence by Decade** — Grouped bar chart showing trends across 1970s–2010s
- **Health Burden by World Region** — Regional comparison across Pacific Islands, Middle East, Western Europe, South Asia, and more
- **Top 20 Countries by Average Obesity (Women, 2016)** — American Samoa and Nauru lead at 65%, with Cook Islands, Palau, and Marshall Islands close behind
- **Health Trends by Country Over Time** — Multi-line trend chart per country
- **Year-on-Year Change in Prevalence (%)** — YoY delta chart showing acceleration/deceleration in health conditions
- **Composite Health Risk Score** — Aggregated risk metric per country
- **Country Selector** — Dropdown slicer to drill into any specific country

---

## 🗂️ Repository Structure

```
Global-Health-Trends-Dashboard/
│
├── GlobalHealthTrends.pbix       # Main Power BI report file
├── README.md                     # Project documentation
└── screenshots/
    ├── global_health_trends.png  # Page 1 screenshot
    └── country_deep_dive.png     # Page 2 screenshot
```

---

## 📁 Data Sources

The dashboard is built on WHO-sourced global health data including:

| Table | Description |
|-------|-------------|
| `Diabetes` | Country-level diabetes prevalence by year and sex |
| `Raised Blood Pressure` | Hypertension prevalence by country, year, and sex |
| `Health_Data` | Aggregated metrics including Avg Prevalence, Max Prevalence, YoY Change, Health Risk Score |
| `YearTable` | Date/year dimension table |

---

## 🔍 Key Insights

- **Blood Pressure** accounts for the largest share of global health burden (~57%)
- **Obesity** prevalence has been rising consistently since the 1970s, while blood pressure shows a declining trend
- **Pacific Island nations** dominate the top obesity rankings — American Samoa and Nauru both at 65% average obesity among women (2016)
- **Men vs Women**: Men show higher blood pressure prevalence (30 vs 26), while obesity is higher in women (17 vs 10)
- **YoY growth** in diabetes and obesity is accelerating, while blood pressure is slowly declining globally

---

## 🛠️ Tools Used

- **Power BI Desktop** — Data modeling, DAX measures, and report design
- **DAX** — Calculated columns and measures (YoY Change, Composite Health Risk Score, Avg Prevalence)
- **Power Query (M)** — Data transformation and cleaning

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `GlobalHealthTrends.pbix` in **Power BI Desktop**
3. Explore Page 1 for global-level trends
4. Navigate to Page 2 for country-level deep dives
5. Use the **Men/Women toggle**, **indicator buttons**, and **year slider** to filter the data interactively
6. Use the **Country dropdown** on Page 2 to focus on a specific country


