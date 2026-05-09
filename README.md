# Data_Analyst_Task_Artem_Healthtech

## 1. Data Cleaning & Standardization
- Removed duplicate records and handled missing/null values to improve data quality.
- Filtered dataset to retain only valid positive age values for accurate analysis.
- Standardized inconsistent gender entries into three unified categories: Male, Female, and Other.
- Cleaned categorical fields to ensure consistency across analysis and visualizations.

## 2. Appointment Attendance Overview
- The dataset contains a significantly higher number of successful appointments compared to missed appointments.
  
## Out of the total cleaned records:
- 49,894 patients attended appointments
- 19,934 patients missed appointments
  
## Overall appointment attendance distribution:
- 71.45% Showed Up
- 28.55% No-show
  
## Key Insight:
- The hospital maintains a relatively strong attendance rate; however, nearly one-third of appointments are still missed, which may impact operational efficiency and resource utilization.

------------------
## 3. Neighbourhood-wise Appointment Trends
## Highest Appointment Volume Areas
The following neighbourhoods recorded the highest number of appointments:
- Jardim Camburi
- Maria Ortiz
- Resistência
- Jardim Da Penha
- Itararé
## Highest No-show Rate Areas
Neighbourhoods with the highest missed appointment percentages include:
- Gurigica
- Jesus De Nazareth
- Itararé
- Santos Dumont
- Ilha Do Príncipe
## Key Insight:
- Certain neighbourhoods consistently demonstrate higher no-show behavior, suggesting possible accessibility, awareness, scheduling, or transportation-related challenges.

## 4. Gender-based Analysis
Gender	Showed Up	No-show
- Female	71.55%	28.45%
- Male	71.25%	28.75%
- 
## Key Insight:
- Attendance behavior remained relatively similar across male and female patients, indicating gender does not significantly influence appointment attendance patterns.

## 5. Age Group Analysis
Age Group	Showed Up	No-show
- Child	66.79%	33.21%
- Young Adult	65.78%	34.22%
- Adult	73.29%	26.71%
- Senior	79.54%	20.46%
## Key Insight:
- Younger patients demonstrated higher no-show rates, while senior patients showed the strongest appointment adherence.

## This may indicate:
- lower prioritization among younger age groups
- dependency factors
- scheduling conflicts

## 6. Waiting Time Analysis

Average waiting period:

- Patients who attended: 13.94 days
- Patients who missed: 16.17 days
- 
## Waiting Category Trend
Waiting Period	No-show Rate
- Same Day	21.38%
- 1–7 Days	24.97%
- 8–30 Days	32.11%
- 30+ Days	33.15%

## Key Insight:
- Longer waiting periods strongly correlate with increased no-show rates.
- Patients waiting more than 30 days were significantly more likely to miss appointments compared to same-day appointments.
- This indicates that reducing scheduling delays may improve attendance rates.

## 7. SMS Reminder Effectiveness
SMS Status	Showed Up	No-show
No SMS	70.59%	29.41%
Received SMS	72.33%	27.67%
## Key Insight:
- Patients receiving SMS reminders demonstrated slightly better attendance rates, indicating reminders have a positive but limited impact on reducing missed appointments.
- Additional engagement mechanisms may further improve attendance behavior.

## 8. Diabetes-based Attendance Analysis
Diabetes Status	Showed Up	No-show
Non-diabetic	71.15%	28.85%
Diabetic	75.04%	24.96%
## Key Insight:
- Patients with diabetes showed comparatively better appointment adherence, possibly due to the importance of regular medical monitoring and treatment continuity.
