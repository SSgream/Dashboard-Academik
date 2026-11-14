# Attendance Analytics Dashboard – Power BI

An interactive university attendance analytics dashboard developed using **Microsoft Power BI** to analyze student attendance patterns, attendance rates, and participation trends across faculties, study programs, and academic periods.

## Dashboard Preview

![Attendance Analytics Dashboard](Dashboard_Preview.png)

**Dashboard File:**  
Download the Power BI report: `attendance_analytics.pbix`

## Project Overview

The Attendance Analytics Dashboard provides insights into student attendance patterns across different faculties and study programs.

The dashboard focuses on analyzing attendance distribution, comparing attendance rates, identifying differences in attendance patterns, and monitoring attendance trends across academic semesters and student enrollment cohorts.

This project demonstrates how attendance data can be transformed into meaningful visual insights to support academic monitoring and data-driven decision-making in higher education.

## Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard includes four main indicators:

- **Total Attendance Records** – Total number of recorded student attendance entries.
- **Present Rate (%)** – Percentage of attendance records categorized as present.
- **Absent Rate (%)** – Percentage of attendance records categorized as absent.
- **Total Students** – Number of distinct students included in the attendance analysis.

### 2. Data Visualizations

| Visualization | Description |
|---|---|
| Attendance Distribution | Shows the distribution of student attendance categories. |
| Attendance Rate by Faculty | Compares attendance rates across different faculties. |
| Top 10 Study Programs by Attendance Rate | Highlights study programs with the highest attendance rates. |
| Attendance Trend by Semester | Tracks changes in attendance rates across academic semesters. |
| Attendance Rate by Enrollment Cohort | Compares attendance rates based on student enrollment years. |
| Attendance Status by Faculty | Shows attendance category distribution across faculties. |

### 3. Interactive Filters

Users can explore the dashboard through the following slicers:

- Faculty
- Study Program
- Enrollment Year
- Academic Year
- Semester
- Attendance Type

All slicers interact with relevant report visualizations, allowing users to explore attendance patterns from different academic perspectives.

## Key Insights

The dashboard helps users explore several aspects of student attendance:

- Overall student attendance distribution.
- Attendance rate comparisons across faculties.
- Study programs with relatively higher attendance rates.
- Attendance patterns across different student enrollment cohorts.
- Changes in attendance rates over academic semesters.
- Differences in attendance categories across faculties.

## Tools & Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization.
- **DAX (Data Analysis Expressions)** – KPI calculations and attendance measures.
- **Power Query** – Data cleaning and transformation.
- **Python (Pandas)** – Data preparation and transformation.
- **CSV** – Data storage and input format.

## Dataset

This project uses a synthetic university attendance dataset structured around academic and student attendance information.

The dataset is designed for analytical and visualization purposes and does not expose actual student personal information.

## Project Structure

```text
attendance_analytics/
│
├── README.md
├── dashboard_preview.png
└── attendance
