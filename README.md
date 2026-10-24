<h1 align="center">MSME Business Performance Analysis</h1>

<p align="center">
  <b>Business Analytics Project using Microsoft Excel and Power BI</b>
</p>

<p align="center">
  Business Performance • Revenue • Profitability • Growth • Employment • Government Scheme Applications
</p>

<hr>

## 📌 Table of Contents
- [Overview](#-overview)
- [Project Objectives](#-project-objectives)
- [Tools & Technologies](#-tools--technologies)
- [Skills Demonstrated](#-skills-demonstrated)
- [Project Structure](#-project-structure)
- [Power BI Dashboard](#-power-bi-dashboard)
- [Key Performance Indicators](#-key-performance-indicators)
- [Analysis Areas](#-analysis-areas)
- [Key Findings](#-key-findings)
- [Recommendations](#-recommendations)
- [Project Deliverables](#-project-deliverables)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

<hr>

## 📊 Overview

The **MSME Business Performance Analysis** project examines business performance across 300 registered businesses using an Excel workbook and an interactive Power BI dashboard. The analysis covers revenue, profit, employee count, year-over-year growth, and government scheme application outcomes.

The dataset represents 8 industries, 10 states, and 31 cities, with registration dates from January 2025 to October 2026. The dashboard includes filters for State, City, Industry, and Government Scheme.

> Financial values shown in crore are converted from lakh INR (100 lakh = 1 crore), as described in the project presentation.

<hr>

## 🎯 Project Objectives
- Review business revenue and profit performance.
- Compare profitability across industries and states.
- Understand employee counts and business distribution.
- Analyze year-over-year growth and identify businesses with negative growth.
- Review government scheme application outcomes.
- Identify pending and under-review applications.
- Build an interactive dashboard to support business reporting.

<hr>

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Dataset review, pivot analysis, and supporting calculations |
| Power BI Desktop | Interactive dashboard and visual analysis |
| Power Query | Data preparation and transformation, where used |
| DAX | KPI calculations and measures in Power BI |
| GitHub | Project portfolio and version control |

<hr>

## 💡 Skills Demonstrated
- Data preparation and review
- Excel analysis and Pivot Tables
- Power BI dashboard development
- KPI definition and reporting
- DAX measures
- Data visualization
- Revenue and profitability analysis
- Industry and state comparisons
- Growth analysis
- Government scheme application analysis
- Interactive filters and business reporting

<hr>

## 📁 Project Structure

```text
MSME-Business-Performance-Analysis/
├── Excel_Dashboard/
│   ├── MSME_Business_Performance_Analysis.xlsx
│   └── MSME_Business_Performance_Excel_Dashboard.png
├── PowerBI_Dashboard/
│   ├── MSME_Business_Performance_Analysis.pbix
│   └── MSME_Business_Performance_PowerBI_Dashboard.png
├── Presentation/
│   └── MSME Business Performance Analysis.pptx
├── Raw Data/
│   └── msme_business_data.csv
└── README.md
```

The Excel workbook, Power BI report, PowerPoint presentation, and dashboard screenshot images are organized in their matching folders. Add `msme_business_data.csv` to `Raw Data/` if you want to include the source dataset in the repository.

<hr>

## 📊 Power BI Dashboard

The dashboard presents KPI cards and visual breakdowns for business performance, including:
- Revenue by city
- Monthly revenue by registration month
- Revenue by industry
- Government scheme application status
- Slicers for State, City, Industry, and Government Scheme

The Power BI report is stored in `PowerBI_Dashboard/`. The screenshot below is the filtered view supplied for this project; its KPI values may change when the dashboard slicers are changed.

<p align="center">
  <img src="PowerBI_Dashboard/MSME_Business_Performance_PowerBI_Dashboard.png" alt="MSME Business Performance Power BI Dashboard" width="100%">
</p>

<hr>

## 📈 Excel Dashboard

The Excel dashboard includes KPI cards, revenue by industry and state, government scheme application status, and interactive slicers.

<p align="center">
  <img src="Excel_Dashboard/MSME_Business_Performance_Excel_Dashboard.png" alt="MSME Business Performance Excel Dashboard" width="100%">
</p>

<hr>

## 📌 Key Performance Indicators

The values below are the overall dataset figures reported in the project presentation. The screenshots included in this repository are filtered to Manipur, so their displayed KPI values are not overall totals.

| KPI | Value |
|---|---:|
| Total registered businesses | 300 |
| Total employees | 37,438 |
| Total annual revenue | ₹1,842 crore |
| Total profit | ₹513 crore |
| Profit margin | 27.8% |
| Average year-over-year growth | 12.1% |
| Approval rate | 53% |
| Undecided applications | 100 |
| Businesses with negative year-over-year growth | 69 |

**Definitions described in the project:** Profit margin = total profit ÷ total revenue. Approval rate = approved applications ÷ all applications. Undecided applications include pending and under-review applications.

<hr>

## 🔎 Analysis Areas

### 1. Revenue and Industry
- Compare revenue across 8 industries.
- Handicrafts is the highest-revenue industry at ₹322 crore.
- Logistics contributes ₹276 crore and Food Processing ₹273 crore.
- The top three industries contribute approximately 47% of total revenue.

### 2. Profitability and Growth by Industry
- Compare profit, profit margin, and average growth.
- Textiles has the highest reported margin at 34.5%.
- Logistics has the highest reported average growth at 13.5%.

### 3. State Performance — Overall Presentation Analysis
The project presentation reports the following state-level results for the overall dataset:
- **Highest revenue:** Manipur — ₹264 crore.
- **Second-highest revenue:** Karnataka — ₹261 crore.
- **Third-highest revenue:** Assam — ₹229 crore.
- **Highest average year-over-year growth:** Uttar Pradesh — 20.9%.
- **Lowest average year-over-year growth:** Odisha — 6.1%.
- **Lowest reported profit margin:** West Bengal — 23.8%.

The Power BI and Excel screenshots supplied with this README are filtered to **Manipur**. Their visible totals (31 businesses, ₹264.18 crore revenue, and ₹73.65 crore profit in Power BI) are for that selected view and should not be mistaken for all-state totals.

### 4. Government Scheme Applications
- Review approved, pending, under-review, and rejected applications.
- 159 applications are approved (53%).
- 100 applications are undecided: 53 pending and 47 under review.
- 41 applications are rejected (14%).
- Market Access has a reported approval rate of 61%; Technology Upgrade has 45%.

<hr>

## 🔍 Key Findings

- **Healthy overall margin:** The project reports a 27.8% overall profit margin.
- **Revenue concentration:** The top three industries account for about 47% of revenue; the top three states account for about 41%.
- **Uneven growth:** Average growth ranges from 20.9% in Uttar Pradesh to 6.1% in Odisha.
- **Application backlog:** One-third of scheme applications are pending or under review.
- **At-risk businesses:** 69 businesses have negative year-over-year growth, according to the presentation.

<hr>

## 💡 Recommendations

These are recommendations stated in the project presentation, not additional facts from the dataset:
1. Set a decision deadline for pending and under-review applications.
2. Review the Technology Upgrade scheme's lower approval rate and higher rejection count.
3. Study faster-growing states and consider targeted support for slower-growing segments.
4. Track businesses with negative growth and consider early support.

<hr>

## 📄 Project Deliverables

| Folder | File | Description |
|---|---|---|
| `Excel_Dashboard/` | `MSME_Business_Performance_Analysis.xlsx` | Excel workbook and analysis |
| `PowerBI_Dashboard/` | `MSME_Business_Performance_Analysis.pbix` | Interactive Power BI dashboard |
| `Presentation/` | `MSME_Business_Performance_Analysis.pptx` | Project presentation for explanation or interview |
| `Raw Data/` | `msme_business_data.csv` | Source CSV, to be added if available |

<hr>

## 🚀 Future Improvements
- Include the source CSV and document its origin.
- Add SQL scripts for reproducible analysis, if created.
- Add additional dashboard screenshot previews if more views are available.
- Document data cleaning steps and KPI formulas in more detail.
- Add further drill-through pages and time-based comparisons where supported by the data.
- Validate data definitions and dashboard calculations before using the results for business decisions.

<hr>

## 👨‍💻 Author

**Sourav Patra**  
Aspiring Data Analyst | Excel | SQL | Power BI | Data Visualization

This project demonstrates practical work in business analysis, KPI reporting, dashboard development, and data visualization.

<hr>

<p align="center">
  <b>MSME Business Performance Analysis</b><br>
  Turning business data into clear and actionable insights.
</p>