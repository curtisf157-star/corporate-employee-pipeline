# HR Analytics Dashboard — Power BI + Python + SQL

An end-to-end HR analytics project: cleaning a messy 1,020-row employee
dataset, loading it into a database, and building an interactive Power BI
dashboard to answer real HR business questions.

## Business Questions Answered
- Which departments have the highest turnover?
- Is salary distributed fairly across regions?
- Does remote work correlate with performance?
- How has headcount grown over time?

## Tech Stack
- **Python (pandas)** — data cleaning, validation, quality reporting
- **SQL** — analytical queries for KPIs
- **Power BI** — interactive dashboard with DAX measures
- **Git** — version control

## The Data
Raw: 1,020 employee records with missing ages, missing salaries (N/A),
inconsistent formatting, and negative phone numbers.
Cleaned: standardized names, split department/region, converted types,
validated emails, imputed missing ages from department medians.

See [`insights.md`](insights.md) for full findings.

## Dashboard Preview
![Overview](powerbi/screenshots/overview.png)
![Salary](powerbi/screenshots/salary_analysis.png)

## Key Insights
1. **Attrition hotspots** — [fill in from your dashboard]
2. **Salary gaps** — [fill in]
3. **Remote work** — [fill in]

## How to Reproduce
1. `pip install pandas`
2. `python python/clean_employees.py`
3. Open `HR_Analytics_PowerBI.pbix` in Power BI Desktop
