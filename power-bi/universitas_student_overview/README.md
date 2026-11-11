# Student Overview Dashboard

## Project Overview

The **Student Overview Dashboard** is a data analytics project designed to provide insights into university student demographics and academic distribution.

This dashboard presents key information about student populations, including student enrollment, active student status, faculty distribution, study programs, enrollment cohorts, and gender distribution.

The project aims to transform structured university data into meaningful visual insights that support institutional monitoring and data-driven decision-making.

## Objectives

- Analyze the total number of university students.
- Identify active student populations.
- Explore student distribution across faculties and study programs.
- Analyze student enrollment trends by cohort.
- Understand student demographics based on gender.
- Provide an interactive dashboard for exploring student data.

## Dashboard Preview

![Student Overview Dashboard](Dashboard Student Ovreview.png)

## Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

| KPI | Description |
|---|---|
| Total Students | Total number of students in the dataset |
| Active Students | Number of students with active status |
| Total Study Programs | Number of distinct study programs |
| Total Faculties | Number of distinct faculties |

## Data Analysis & Visualizations

The dashboard provides several visualizations:

1. **Student Distribution by Faculty**  
   Shows the distribution of students across faculties.

2. **Students by Enrollment Year**  
   Displays student enrollment distribution by cohort.

3. **Gender Distribution**  
   Presents the composition of students based on gender.

4. **Student Distribution by Study Program**  
   Highlights the top 10 study programs based on student population.

## Tools & Technologies

- **Python** – Data preparation and transformation.
- **Pandas** – Data cleaning and manipulation.
- **Microsoft Power BI** – Dashboard development and visualization.
- **GitHub** – Project documentation and version control.

## Data Preparation

The dataset was prepared using Python and Pandas.

The preparation process included:

1. Loading the synthetic student and study program datasets.
2. Selecting relevant attributes for analysis.
3. Joining student data with study program information.
4. Aggregating the number of courses by study program, where applicable.
5. Preparing the final dataset for dashboard development.

The analysis uses synthetic data structured to represent a university academic information system. It does not contain actual student personal information.

## Project Structure

```text
universitas_student_overview/
├── README.md
├── dashboard_preview.png
└── student_overview.pbix
```

## Key Insights

This dashboard is designed to help identify:

- Faculties with the largest student populations.
- Study programs with the highest student enrollment.
- Student enrollment patterns across cohorts.
- Gender composition across the university.
- The proportion of active students.

*Detailed findings will be added after the dashboard analysis is completed.*

## Project Deliverables

- Power BI Report (`.pbix`)
- Dashboard preview (`.png`)
- Data preparation notebook (`.ipynb`)

---

**Project Category:** Data Analytics & Data Visualization  
**Status:** Completed / In Progress
