# Data_Visualization_Tableau

CSU Recreation Center Data Visualization (Tableau)

Project Overview

This project is an introductory Tableau visualization exercise using real usage data from the Cleveland State University (CSU) Recreation Center. The goal is to become familiar with Tableau’s interface while building meaningful visualizations that provide insight into student recreation center usage patterns.
Using the provided dataset, the project walks through connecting data, preparing fields, creating visualizations, and exporting a packaged Tableau workbook. The analysis focuses on understanding visitor behavior across different student class standings, with an emphasis on interpretation rather than causal conclusions.

Dataset Description

Dataset Name: Rec Center.xlsx

Source: Cleveland State University – Institutional Research

Description:
The dataset contains records of CSU Recreation Center usage, including student identifiers, class standing, geographic information, and visit details. The data is used to explore how different student groups utilize the recreation center.

Objectives

The objectives of this project are to:

1. Learn how to connect Tableau to an Excel dataset
2. Review and validate imported data fields and data types
3. Correct data type issues, especially for geographic and identifier fields
4. Create a visualization showing recreation center visits by class standing
5. Explore Tableau’s charting capabilities by designing an additional custom visualization
6. Export a packaged Tableau workbook (.twbx) for sharing and peer review
7. Practice critical thinking by interpreting visualization results responsibly

Tools Used

1. Tableau Desktop
2. Microsoft Excel (data source)

Project Workflow
1. Data Connection

Connected Tableau to Rec Center.xlsx

Saved the Tableau workbook locally

2. Data Validation & Preparation

Verified all fields imported correctly

Corrected data types:

Converted Postal to ZIP Code (Geographic Role)

Converted Emplid1 (CUID) from numeric to string

3. Visualization 1: Visitors by Class Standing

Created a worksheet titled “Visitors x Class Standing”

Rows: Class Standing

Columns: Count of Emplid1

Visualization shows the number of recreation center visitors across student groups

4. Visualization 2: Exploratory Chart

Created an additional worksheet using a chart type of choice

Purpose: explore the data creatively and gain familiarity with Tableau’s interface

5. Export

Exported the final project as a Packaged Tableau Workbook (.twbx)

Prepared for peer review submission

Key Insight & Interpretation

The visualization shows that doctoral students visit the CSU Rec Center the least in terms of raw visit counts. However, this does not mean doctoral students are least likely to exercise.

Why this conclusion cannot be made:

The data shows visit counts, not exercise frequency or behavior

Doctoral students likely represent a much smaller population

External factors (age, work schedules, off-campus gyms, time constraints) are not captured

The dataset does not normalize visits by group size

This highlights the importance of context and population size when interpreting visual analytics.

Notes

This project is for educational purposes

Visualizations are exploratory and descriptive

Conclusions should be interpreted with appropriate analytical caution
