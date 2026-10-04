# hr-intelligence-dashboard
A 6-page Power BI dashboard analysing employee attrition, performance, compensation, engagement, and workforce trends across 1,470 employees, built on the IBM HR Analytics dataset.
📊 HR Intelligence Dashboard — Employee Attrition & Workforce Insights
> *Nearly 1 in 6 employees leave, and most exits happen within the first 5 years.*
A comprehensive 6-page Power BI dashboard built to help HR leaders identify retention risks, compensation gaps, and engagement patterns — enabling faster, data-driven workforce decisions.
Data Source: IBM HR Analytics Employee Attrition Dataset, Kaggle
Last Refreshed: 20th July, 2026
---
📌 Project Overview
This dashboard analyses employee attrition and workforce trends across 1,470 employees spanning three departments — Research & Development, Sales, and Human Resources. Using the IBM HR Analytics dataset, it uncovers the key drivers of attrition, highlights compensation and performance gaps, and maps engagement and development patterns across job roles and tenure cohorts.
---
🖼️ Dashboard Preview
Cover Page
![Cover Page](images/cover_page.png)
Page 1 — Overview
![Overview](images/overview.png)
Page 2 — Performance & Compensation
![Performance & Compensation](images/performance_compensation.png)
Page 3 — Engagement & Retention
![Engagement & Retention](images/engagement_retention.png)
Page 4 — Training & Growth
![Training & Growth](images/training_growth.png)
Page 5 — Attrition Deep Dive
![Attrition Deep Dive](images/attrition_deep_dive.png)
---
🔢 Key Metrics at a Glance
Metric	Value
Total Employees	1,470
Attrition Rate	16%
Average Age	37 years
Average Monthly Income	$6,500
Average Job Satisfaction	2.73 / 5
Gender Split	60% Male · 40% Female
---
📋 Dashboard Pages & Insights
Page 1 — Overview
A high-level snapshot of the entire workforce.
Department breakdown: Research & Development is the largest department with 961 employees, followed by Sales (446) and Human Resources (63)
Gender distribution: 60% Male (882), 40% Female (588)
Job involvement by age group: Young Adults (18–25) score highest at 2.80, followed by Middle-Aged (46–60) at 2.77 and Adults (26–45) at 2.71
Income by job role: Managers earn the highest average monthly income (~$17K), followed by Research Directors (~$16K). Sales Representatives and Laboratory Technicians sit at the lower end of the pay scale
Slicers: Department, Attrition, Gender, Education Field, and Job Role — all cross-filtering every visual on the page
---
Page 2 — Performance & Compensation
Explores the relationship between performance ratings, salary hikes, overtime, and compensation.
Performance ratings are tightly clustered: Managers lead at 3.20, followed by Manufacturing Directors (3.19) and Research Scientists (3.17). Sales Executives and Human Resources sit lowest at 3.13
Salary hike vs. performance: Average salary hikes range from 14.81% (Human Resources) to 15.67% (Sales Representatives) — suggesting hikes are not strongly differentiated by performance rating
Overtime is concentrated in frontline roles: Sales Executives carry the heaviest overtime burden, followed by Research Scientists and Laboratory Technicians
Income by role and department: Sales Executives generate the highest total monthly income, particularly within the Sales department. Research Directors and Managers follow closely in R&D
Key concern: Despite Managers having the highest performance rating (3.20), their average salary hike (15.14%) is mid-range — suggesting a potential disconnect between performance recognition and compensation
---
Page 3 — Engagement & Retention
Examines satisfaction scores, business travel impact, and tenure distribution.
Satisfaction across three dimensions: Relationship satisfaction, job satisfaction, and environment satisfaction are plotted by job role — Human Resources and Managers score highest across all three metrics; Sales Representatives and Research Directors score lowest
Business travel and satisfaction: Non-Travel and Travel_Frequently employees share an identical average job satisfaction of 2.79; Travel_Rarely employees score slightly lower at 2.70 — suggesting frequent travellers may be better supported or self-selected
Average tenure is consistent across departments: Sales, Human Resources, and Research & Development all average 7 years at company
Headcount by tenure (years at company): Employee count peaks sharply in the 0–5 year bracket and drops steeply beyond 10 years — indicating that most attrition occurs early in the employee lifecycle, consistent with the headline finding that most exits happen within the first 5 years
---
Page 4 — Training & Growth
Focuses on learning investment, education profile, and promotion patterns.
Training frequency by job role: Sales Representatives and Laboratory Technicians receive the most training sessions per year (averaging ~3), while Research Scientists receive the least (~2.7) — notable given their high performance ratings
Education field distribution: Life Sciences dominates at 41.22% (606 employees), followed by Medical at 31.56% (464), Marketing at 10.82% (159), Technical Degree at 8.98% (132), and Other at 5.58% (82)
Years in current role vs. years at company: Employees with longer tenure spend proportionally more years in the same role — pointing to a stagnation risk for long-tenured staff who are not being promoted or rotated
Years since last promotion by job role: Several roles show clusters of employees with 10–15 years since their last promotion — a significant red flag for flight risk and disengagement among experienced staff
---
Page 5 — Attrition Deep Dive
The most critical page — breaks down attrition by every available dimension.
Attrition rate by department:
Sales: 21% (highest)
Human Resources: 19%
Research & Development: 14% (lowest)
Attrition rate by job role:
Sales Representatives: 40% ⚠️ (critical)
Laboratory Technicians: 24%
Human Resources: 23%
Sales Executives: 17%
Research Scientists: 16%
Research Directors: 3% (lowest)
Managers: 5%
Attrition by marital status: Single employees leave at the highest rate (~27%), followed by Married (~13%) and Divorced (~10%) — suggesting single employees may have fewer anchoring factors to the organisation
Attrition by gender: Males account for 53.48% of attrition (rate: 0.17), Females 46.52% (rate: 0.15) — broadly proportional to the workforce gender split
Attrition by overtime: Employees working overtime leave at a rate of 31% vs. 10% for those who do not — making overtime the single strongest predictor of attrition in this dataset
---
💡 Key Findings & Recommendations
1. 🔴 Sales Representatives are a critical retention risk (40% attrition)
The highest attrition of any role. Combine this with heavy overtime exposure and below-average income relative to seniority, and this role needs immediate attention. Recommended action: structured career progression pathways, workload reviews, and targeted compensation adjustments.
2. 🔴 Overtime is the strongest attrition driver (31% vs. 10%)
Employees on overtime are three times more likely to leave. The overtime burden is concentrated in Sales Executives, Research Scientists, and Laboratory Technicians. Recommended action: headcount planning in these roles and workload redistribution.
3. 🟡 Most exits happen within the first 5 years
The tenure chart confirms the headline finding. Onboarding quality, early career development, and manager relationships in years 1–3 are likely the key levers to pull. Recommended action: structured 90-day, 6-month, and 1-year check-ins; mentoring programmes for early-tenure employees.
4. 🟡 Long-tenured employees face promotion stagnation
Employees with 10+ years at company show high years since last promotion, particularly in technical roles. Recommended action: introduce lateral movement, specialist career tracks, or formal promotion review cycles for employees in role for 3+ years.
5. 🟡 Single employees leave at the highest rate (27%)
While demographic factors are outside HR's direct control, this signals an opportunity to build stronger social and community connections at work — especially for younger, single employees in the 18–25 age bracket.
6. 🟢 Performance ratings are not driving compensation differentiation
Salary hikes range only from 14.81% to 15.67% across all job roles regardless of performance rating. A more differentiated performance-linked pay structure could improve both fairness and retention of top performers.
---
🛠️ Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard design, layout, and publishing
Power Query	Data cleaning, transformation, and shaping
DAX	Custom measures, KPIs, attrition rate calculations, and conditional formatting
IBM HR Dataset (Kaggle)	Source data (1,470 employee records)
---
📁 Project Structure
```
hr-intelligence-dashboard/
│
├── README.md
├── data/
│   ├── raw/
│   │   └── hr_data.csv                    # Original IBM HR dataset
│   └── cleaned/
│       └── hr_data_cleaned.csv            # Cleaned and transformed data
│
├── dashboard/
│   └── HR_INTELLIGENCE_DASHBOARD.pbix     # Power BI file
│
├── images/
│   ├── cover_page.png
│   ├── overview.png
│   ├── performance_compensation.png
│   ├── engagement_retention.png
│   ├── training_growth.png
│   └── attrition_deep_dive.png
│
└── docs/
    └── HR_INTELLIGENCE_DASHBOARD.pdf      # Exported PDF version
```
---
🚀 How to Use
Clone or download this repository
Open `dashboard/HR_INTELLIGENCE_DASHBOARD.pbix` in Power BI Desktop
If prompted, update the data source path to point to `data/cleaned/hr_data_cleaned.csv`
Use the dropdown slicers (Department, Attrition, Gender, Education Field, Job Role) to filter all visuals simultaneously
Navigate between the six pages using the left-hand navigation panel:
Cover Page → Overview → Performance & Compensation → Engagement & Retention → Training & Growth → Attrition Deep Dive
---
👤 Author
Mayowa Phillip — Data Analyst
📧 mayowaphillip@yahoo.com
💼 LinkedIn
🐙 GitHub
---
Built with Power BI · DAX · Power Query · IBM HR Analytics Dataset (Kaggle)
