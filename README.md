# Data Analyst Task - Artem Healthtech

# Key Insights :

## 1. Data Cleaning & Standardization
- Removed duplicate records and handled missing/null values to improve data quality.
- Filtered dataset to retain only valid positive age values for accurate analysis.
- Standardized inconsistent gender entries into three unified categories: Male, Female, and Other.
- Cleaned categorical fields to ensure consistency across analysis and visualizations.

---------

## 2. Appointment Attendance Overview
- The dataset contains a significantly higher number of successful appointments compared to missed appointments.
  
### Out of the total cleaned records:
| Appointment Status | Count |
|---|---:|
| Showed Up | 49,894 |
| No-show | 19,934 |
  
### Overall appointment attendance distribution:
| Appointment Status | Percentage |
|---|---:|
| Showed Up | 71.45% |
| No-show | 28.55% |
  
## Key Insight:
- The hospital maintains a relatively strong attendance rate; however, nearly one-third of appointments are still missed, which may impact operational efficiency and resource utilization.

------------------
## 3. Neighbourhood-wise Appointment Trends
### Highest Appointment Volume Areas
### The following neighbourhoods recorded the highest number of appointments:
| Neighbourhood | Total Appointments |
|---|---:|
| Jardim Camburi | 5,129 |
| Maria Ortiz | 3,579 |
| Resistência | 2,687 |
| Jardim Da Penha | 2,638 |
| Itararé | 2,315 |
| Centro | 2,237 |
| Tabuazeiro | 1,865 |
| Jesus De Nazareth | 1,683 |
| Bonfim | 1,672 |
| Caratoíra | 1,658 |

## Highest No-show Rate Areas
### Neighbourhoods with the highest missed appointment percentages include:
| Neighbourhood | No-show Percentage |
|---|---:|
| Ilhas Oceânicas De Trindade | 100.00% |
| Gurigica | 38.38% |
| Jesus De Nazareth | 38.03% |
| Itararé | 36.54% |
| Horto | 35.19% |
| Santos Dumont | 35.04% |
| Santa Clara | 33.78% |
| Ariovaldo Favalessa | 33.53% |
| Santa Cecília | 33.04% |
| Ilha Do Príncipe | 32.50% |
## Key Insight:
- Certain neighbourhoods consistently demonstrate higher no-show behavior, suggesting possible accessibility, awareness, scheduling, or transportation-related challenges.

---------------

## 4. Gender-based Analysis
| Gender | Showed Up (%) | No-show (%) |
|---|---:|---:|
| Female | 71.55% | 28.45% |
| Male | 71.25% | 28.75% |
| Other | 100.00% | 0.00% |

## Key Insight:
- Attendance behavior remained relatively similar across male and female patients, indicating gender does not significantly influence appointment attendance patterns.

------------

## 5. Age Group Analysis
| Age Group | Showed Up (%) | No-show (%) |
|---|---:|---:|
| Child | 66.79% | 33.21% |
| Young Adult | 65.78% | 34.22% |
| Adult | 73.29% | 26.71% |
| Senior | 79.54% | 20.46% |
## Key Insight:
- Younger patients demonstrated higher no-show rates, while senior patients showed the strongest appointment adherence.

## This may indicate:
- lower prioritization among younger age groups
- dependency factors
- scheduling conflicts

---------------

## 6. Waiting Time Analysis

### Waiting Category Trend
Waiting Period	No-show Rate
| Waiting Period | Showed Up (%) | No-show (%) |
|---|---:|---:|
| Same Day | 78.62% | 21.38% |
| 1–7 Days | 75.03% | 24.97% |
| 8–30 Days | 67.89% | 32.11% |
| 30+ Days | 66.85% | 33.15% |

## Key Insight:
- Longer waiting periods strongly correlate with increased no-show rates.
- Patients waiting more than 30 days were significantly more likely to miss appointments compared to same-day appointments.
- This indicates that reducing scheduling delays may improve attendance rates.

------------

## 7. SMS Reminder Effectiveness

| SMS Status | Showed Up (%) | No-show (%) |
|---|---:|---:|
| No SMS | 70.59% | 29.41% |
| Received SMS | 72.33% | 27.67% |
## Key Insight:
- Patients receiving SMS reminders demonstrated slightly better attendance rates, indicating reminders have a positive but limited impact on reducing missed appointments.
- Additional engagement mechanisms may further improve attendance behavior.

----------------

## 8. Diabetes-based Attendance Analysis
| Diabetes Status | Showed Up (%) | No-show (%) |
|---|---:|---:|
| Non-diabetic | 71.15% | 28.85% |
| Diabetic | 75.04% | 24.96% |
## Key Insight:
- Patients with diabetes showed comparatively better appointment adherence, possibly due to the importance of regular medical monitoring and treatment continuity.

## 9. Scholarship Distribution

| Scholarship Status | Patient Count | Percentage |
|---|---:|---:|
| No | 63,184 | 90.49% |
| Yes | 6,644 | 9.51% |

----------

## 10.Hipertension Distribution

| Hipertension Status | Patient Count | Percentage |
|---|---:|---:|
| No | 54,796 | 78.47% |
| Yes | 15,032 | 21.53% |

-----------

## 11.Alcoholism Distribution

| Alcoholism Status | Patient Count | Percentage |
|---|---:|---:|
| No | 68,006 | 97.39% |
| Yes | 1,822 | 2.61% |

--------------

## 12. Handicap Distribution

| Handicap Level | Patient Count | Percentage |
|---|---:|---:|
| 0 | 68,521 | 98.13% |
| 1 | 1,185 | 1.70% |
| 2 | 112 | 0.16% |
| 3 | 8 | 0.01% |
| 4 | 2 | 0.00% |
