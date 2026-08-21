# Student Academic Performance & Engagement Analysis

## Executive Overview 
This portfolio project provides an end-to-end evaluation of student academic performance, homework compliance, and communication touchpoints across primary grade levels using a cleansed dataset of **12,156 student records** spanning 6 core subjects and 5 grade levels.

---

## Data Engineering & Integrity Log
* **Anomaly Detection:** Identified structural column shifts and schema mismatches during dataset synthesis at row 12,158.
* **Resolution Strategy:** Isolated and standardized the **12,156-row dataset** to ensure 100% data integrity and prevent metric distortion across executive KPI dashboards and downstream DAX calculations.

---

## Key Performance Indicators & Insights
* **Core Metrics Equilibrium:** Overall exam scores average **74.2**, homework completion stands at **74.3%**, and present attendance status is recorded at **24.8%** (34.6% including excused instances).
* **Subject Performance Range:** English leads overall performance with an average exam score of **74.8** and homework rate of **74.7%**, while Arabic records the lowest average exam score at **73.4**.
* **Attendance Patterns:** Combined non-present attendance categories (Late: 25.4%, Absent: 25.3%, Excused/Left Early: 24.6%) account for over 75% of student status logs.
* **Balanced Touchpoints:** Communication touchpoints are evenly split across **Teacher to Parent (4,119)**, **Parent to Teacher (4,021)**, and **Automated Reminders (4,016)**.

---

## Tech Stack & Deliverables
* **Microsoft Excel:** Raw data auditing, row-level schema cleaning, and pivot table verification models.
* **Power BI:** Data modeling, dynamic DAX measures, global slicer synchronization, and a two-page interactive dashboard suite:


Page 1:Executive Summary 
<img width="1188" height="504" alt="Student_Academic_Performance_Dashboard" src="https://github.com/user-attachments/assets/a985108d-48f6-4169-85cf-d8d20de33f8f" />


Page 2:Grade Level & Communication Analysis 
<img width="1186" height="503" alt="Overview_Student_Academic_Performance_Dahboard" src="https://github.com/user-attachments/assets/87302573-3519-4232-90d1-a4b87cba26ac" />

