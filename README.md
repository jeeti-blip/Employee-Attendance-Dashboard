# Employee Attendance Dashboard — Power BI

An interactive Power BI dashboard that tracks employee attendance, work-from-home (WFH), and sick leave (SL) trends across a quarter, enabling HR and management to monitor attendance health against a defined target.

![Employee Attendance Dashboard](./Snapshot_Of_Dashboard.png)

## 📊 Overview

This dashboard consolidates daily attendance data for a multi-month period (April–June) into a single view, combining high-level KPIs, trend analysis, and employee-level drill-down in a dark-themed, presentation-ready layout.

## ✨ Key Features

- **KPI Summary Cards** — Overall Attendance %, Sick Leave (SI) %, WFH %, Total Working Days, and Total Days Worked at a glance.
- **Attendance Trend vs Target** — Area chart plotting daily Attendance % against a 95% target line, making shortfalls immediately visible.
- **WFH % Trend** — Tracks work-from-home patterns over time to understand hybrid work distribution.
- **SL % Trend** — Highlights sick leave spikes across the quarter.
- **Day-of-Week Breakdown** — Attendance %, WFH %, and SI % aggregated by weekday (Mon–Fri) to spot patterns like Friday attendance dips.
- **Employee-Level Table** — Sortable list of all employees with individual Attendance %, WFH %, and SI %, with conditional color formatting (green/red) for quick scanning.
- **Interactive Filters** — Slicer by employee name and month (Apr/May/Jun) buttons for focused analysis.

## 🧮 Metrics & Calculations

| Metric | Description |
|---|---|
| Attendance % | Days present / Total working days |
| WFH % | Days worked from home / Total working days |
| SI % | Sick leave days / Total working days |
| Working Days | Total scheduled working days in the selected period |
| Days Worked | Actual days logged as worked (in-office + WFH) |

All measures were built using **DAX**, including time intelligence and conditional aggregations (e.g., `CALCULATE`, `DIVIDE`, `FILTER`) to compute percentage-based KPIs dynamically as filters are applied.

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard design and DAX measures
- **Power Query** — Data cleaning and transformation
- **DAX** — Custom measures for attendance, WFH, and SL percentages
- **Data Modeling** — Star-schema style structure for efficient filtering across visuals

## 📁 Repository Contents

```
├── Employee_Attendance_Dashboard.pbix   # Power BI dashboard file
├── Snapshot_Of_Dashboard.png            # Dashboard preview image
└── README.md                            # Project documentation
```

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Employee_Attendance_Dashboard.pbix` in **Power BI Desktop**.
3. Use the **Name** slicer or **Apr/May/Jun** buttons to filter the view.
4. Hover over chart data points for exact daily/weekly values.

## 🎯 Business Use Case

This dashboard helps HR and operations teams:
- Monitor whether attendance is meeting the 95% target
- Identify weekday patterns in absenteeism or WFH usage
- Flag employees with low attendance or high sick leave for follow-up
- Support data-driven workforce planning decisions

## 📌 Skills Demonstrated

`Power BI` `DAX` `Power Query` `Data Modeling` `KPI Design` `Dashboard UX` `MIS Reporting`

---

**Author:** Jeet Kumar
📧 jeetiti14@gmail.com
