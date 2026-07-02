# DNA (Did Not Attend) Analysis


## Overview


Patient non-attendance represents a significant challenge for healthcare providers, affecting service efficiency, appointment availability, and resource utilisation. This project investigates patterns in missed appointments within NHS primary care services across Hertfordshire and West Essex.


The analysis focuses on identifying factors associated with higher DNA rates and understanding how appointment characteristics influence patient attendance behaviour.


## Dataset



Source: NHS England Appointments in General Practice



Key variables used:



* APPOINTMENT\_MONTH

* APPT\_STATUS

* APPT\_MODE

* TIME\_BETWEEN\_BOOK\_AND\_APPT

* HCP\_TYPE

* COUNT\_OF\_APPOINTMENTS



## Objectives



This project aimed to answer the following questions:



1\. What is the overall DNA rate?

2\. How do DNA rates vary by waiting time category?

3\. Do appointment modes influence DNA rates?

4\. Do DNA rates vary across workforce groups?

5\. How have DNA rates changed over time?



## Tools \& Libraries



* Python

* pandas

* matplotlib

* Jupyter Notebook



## Key Findings



* Overall DNA rates remained relatively low throughout the study period.

* Waiting time was strongly associated with non-attendance.

* Same-day appointments recorded the lowest DNA rates.

* DNA rates increased consistently as waiting times lengthened.

* Monthly DNA rates remained relatively stable over time.

* October recorded elevated DNA rates across multiple years, suggesting a recurring seasonal pattern.

* Differences associated with waiting times were more pronounced than differences associated with appointment modes.



## Key Skills Demonstrated



* Healthcare analytics

* Attendance behaviour analysis

* KPI development

* Comparative analysis

* Data visualisation

* Trend analysis

* Analytical storytelling


## Repository Structure

```text
project_02_dna_analysis
│
├── 02_dna_analysis.ipynb
└── README.md
```



## Conclusion


The analysis identified waiting time as one of the strongest factors associated with patient non-attendance. Patients offered appointments sooner were more likely to attend, while longer waiting periods were associated with higher DNA rates. These findings highlight the importance of timely access to care in reducing missed appointments and improving service efficiency.



