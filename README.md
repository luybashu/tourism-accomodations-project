# Data-Driven Strategy for a Tourism Accommodation Company

## Overview

This project involved cross-functional data analysis to support operational, marketing, and customer experience decision-making for a company operating in the **short-term rental and tourist accommodation sector**. 

Organized by **IT Academy of Barcelona Activa**, the initiative ran from **March 17 to May 5, 2025**, simulating a real-world professional environment.

Our team worked in weekly Agile sprints, analyzing an evolving database of property listings to address business challenges, define KPIs, and deliver actionable insights.
> Example of our weekly task coordination using a shared Kanban board:
![Kanban Board](images/kanban-board.png)

## Objectives

- Monitor occupancy and availability trends across cities
- Identify pricing optimization opportunities across cities and property types
- Analyze customer satisfaction patterns and review dynamics
- Align product offerings with regional tourism demand and traveler profiles

---

## Repository Structure

```text
├── Data/ # Internal and external datasets (CSV)
├── Scripts/ # Python notebooks and scripts used for analysis in each area and KPI calculations
├── Results/ # Final KPI dashboards (PBIX, TWBX), summary table (XLSX) and presentations (PDF)
├── README.md # Project overview
```

---

## Team & Roles

| Name     | Role                          | Focus Area                          |
|----------|-------------------------------|-------------------------------------|
| [Rodrigo](https://github.com/ErrePad)  | Data Analyst – Marketing & business strategy | Pricing, demand patterns, market segmentation |
| [Natalia](https://github.com/NataliaBCN)  | Data Analyst – Customer Experience | Customer reviews, satisfaction, and quality metrics |
| [Luyba](https://github.com/luybashu)   | Data Analyst – Operations & Inventory Management | Availability, capacity management, booking logistics |
| Veronica | Team Lead                      | Coordination, quality assurance, sprint facilitation, QA |

Each team member’s contributions can be found in the `Scripts/` folder, with files named by week and area of analysis (e.g., 20250407_marketing.ipynb)

---

## Workflow & Collaboration

We followed an Agile methodology using Kanban boards to plan, assign, and track tasks each week.

![Kanban Board](Results⁩/kanban-screenshot.png)

The board helped us coordinate sprints, organize weekly business questions, and ensure smooth collaboration across departments.

---

## Technologies Used

- **SQL (MySQL)** for data extraction
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, SciPy, Statsmodels) for analysis, statistics, modeling and predictions
- **Power BI & Tableau** for visual dashboards and business reporting
- **Agile methodology** – weekly sprints, Kanban board collaboration
- **External data sources**: INE Hotel Occupancy Surveys

---

## Weekly Business Challenges & Analysis

### Week 1: Foundational KPIs & Benchmarks
- Analyze average availability across 30/60/90/365-day timeframes
- Breakdown average price by accommodation type and city
- Evaluate satisfaction scores and % of top-rated properties

### Week 2: Feature Impact & Booking Dynamics
- Identify which amenities and property characteristics influence pricing
- Assess impact of instant booking on availability
- Analyze variance between high- and low-rated properties across review categories

### Week 3: Operational Optimization
- Relationship between number of rooms, beds, and bathrooms and occupancy
- High-potential cities and neighborhoods
- Price vs. customer satisfaction correlation by city

### Week 4: Strategic Alignment with National Trends
- Compare demand trends using official national tourism data
- Adjust offer portfolio by region, season, and traveler origin
- Match business KPIs to market seasonality

---

## Key KPIs Tracked

- Occupancy Rate (Monthly)
- City with Highest Occupancy
- General Satisfaction Index
- Most Influential Satisfaction Metric



## Deliverables

- Weekly analysis reports with visuals and key findings
- Final dashboard (Power BI & Tableau)
- Presentation summaries with strategic recommendations

---

## Notes

- Data was updated weekly to simulate real-time decision-making
- All data used was either anonymized or publicly available
- This project reflects a cross-functional, Agile-based approach to real-world business analytics

## Credits & Acknowledgements

This simulation was created and facilitated by **IT Academy - Barcelona Activa**, with mentoring by industry professionals.
