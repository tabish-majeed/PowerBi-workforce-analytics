# Workforce Utilization — Power BI Analytics

![Dashboard cover](timesheet%20dashboard%20cover%20pic.png)

An end-to-end Power BI workforce analytics solution built on a fully synthetic timesheet dataset (**620 employees, 5 locations, Jan–May 2026**). The model turns raw daily time entries into a self-updating executive reporting layer with **100+ DAX measures** and full drill-down to the individual employee.

> **Note:** All data in this project is synthetic. No real company, employee, or client information is used.

---

## What it does

**📊 Self-updating monthly reporting**
Drop in the next month's data and every visual, KPI, and breakdown refreshes automatically — no manual rework.

**🔍 Answers what's wrong and why**
Utilization is broken down by grade, sector, location, and activity type, so you can see not just *that* a number moved but *what's driving it*.

**🎯 Click straight to the detail**
Every summary visual drills through to the underlying employee-level records, so a headline figure is always one click from its source.

---

## Dashboard pages

### Executive Summary
![Executive Summary](Executive%20Summary.png)
Top-line KPIs and the overall utilization picture at a glance.

### Grade-wise Analysis
![Grade wise](Grade%20wise.png)
Utilization and headcount distribution across seniority grades.

### Sector-wise Analysis
![Sector wise](Sector%20wise.png)
Performance split across the three business sectors.

### Onsite & Offsite
![Onsite and Offsite](Onsite%20%26%20Offsite.png)
Delivery location mix and its effect on utilization.

### Billable Segmentation
![Billable Segmentation](Billable%20Segmentation.png)
Breakdown of billable versus non-billable workdays.

### Non-Billable Activities
![Non Billable Activities](Non%20Billable%20Activities.png)
Where non-billable time is going, by activity category.

### Employee Categorization
![Employee Categorization](Employee%20Categorization.png)
Segmentation of the workforce by utilization profile.

### Employee Details — Drill Down
![Employee Details Drill Down](Employee%20Details%20-%20Drill%20Down.png)
Individual employee records — the lowest level of the drill-down path.

---

## Technical highlights

- **100+ DAX measures** including category-, grade-, sector-, and location-specific utilization metrics
- **Power Query (M)** transformation layer keeping raw source data untouched
- Self-updating model — new monthly data flows through automatically
- Full drill-down architecture from executive summary to employee detail

## Files

- `Workforce Utilization.pbix` — the complete Power BI model (open in Power BI Desktop)

---

*Built by Khawaja Tabish Majeed — ACA (ICAP), FP&A & Reporting.*
