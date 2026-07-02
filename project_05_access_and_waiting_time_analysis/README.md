# Project 5: Access and Waiting Time Analysis



## Overview



This project explores patient access to primary care services across Hertfordshire and West Essex using NHS England's Appointments in General Practice dataset.



Building on findings from previous projects, the analysis focuses on appointment waiting times, rapid-access appointments, appointment modes, and healthcare professional groups to understand how quickly patients can access care and which factors are associated with timely appointments.



---



## Objective



The objective of this project is to evaluate patient access to care by analysing appointment waiting times within primary care services.



The analysis examines how quickly patients are seen, how access varies across appointment modes and healthcare professional groups, and which service delivery methods contribute most to rapid-access care.



---



## Questions



1\. How has rapid access to primary care changed over time?



2\. How do waiting-time distributions vary across appointment modes?



3\. Which appointment modes contribute most to rapid-access care?



4\. Do rapid-access rates differ between healthcare professional groups?



5\. Which appointment mode provides the highest level of rapid access?



---



## Dataset



Source:



*\*NHS England – Appointments in General Practice\*\*



Region:



*\*Hertfordshire and West Essex\*\*



Key variables used:



* APPOINTMENT\_MONTH

* TIME\_BETWEEN\_BOOK\_AND\_APPT

* APPT\_MODE

* HCP\_TYPE

* COUNT\_OF\_APPOINTMENTS



---



## Methods Used



### Data Preparation



* Data cleaning

* Data aggregation

* Percentage calculations

* Rapid-access KPI creation



### Analysis



* Waiting-time analysis

* Appointment mode comparison

* Workforce comparison

* Trend analysis

* Access performance measurement



### Visualisation



* Line charts

* Bar charts

* Stacked bar charts



---



## Key Findings



* Most appointments were delivered quickly, with same-day appointments representing the largest waiting-time category.



* Rapid-access levels remained relatively stable throughout the study period.



* Waiting times varied across appointment modes, with Video/Online appointments achieving the highest same-day access rates.



* Face-to-Face appointments delivered the majority of rapid-access appointments due to their substantially higher appointment volumes.



* GPs recorded higher rapid-access rates than Other Practice Staff, highlighting their important role in delivering timely access to care.



* Video/Online appointments achieved the highest rapid-access rate overall, suggesting that remote consultations provide the fastest route to care.



---



## Skills Demonstrated



### Healthcare Analytics



* Access analysis

* Waiting-time analysis

* Healthcare performance measurement

* Workforce analysis

* Service delivery evaluation



### Data Analysis



* Data cleaning

* Grouping and aggregation

* KPI development

* Percentage calculations

* Comparative analysis



### Python



* pandas

* matplotlib

* groupby()

* filtering

* pivot tables

* visualisation



---



## Technologies Used



* Python

* pandas

* matplotlib

* Jupyter Notebook

* Git

* GitHub



\---



## Portfolio Progression



This project builds directly upon findings from Project 2 (DNA Analysis) and Project 3 (Workforce Utilisation Analysis).



Project 2 identified waiting time as one of the strongest factors associated with non-attendance, while Project 3 explored how different workforce groups contribute to service delivery.



This project extends those findings by examining patient access to care and identifying the appointment modes and workforce groups most closely associated with rapid access.



---



## Repository Structure



```text

project_05_access_waiting_time_analysis

│

├── 05_access_waiting_time_analysis.ipynb

└── README.md

```



## Next Project



**Project 6: Primary Care Performance Dashboard (Capstone Project)**



The final project will bring together insights from demand, attendance, workforce utilisation, and patient access analyses into a consolidated healthcare performance dashboard designed to support operational decision-making.



