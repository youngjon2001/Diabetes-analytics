
# Diabetes Underdiagnosis Analysis

## Motivation and Scope

This repository presents an exploratory analysis of a diabetes health dataset with a specific focus on identifying patterns consistent with **underdiagnosis among high-risk individuals**. Despite well-established clinical markers for diabetes risk, a substantial proportion of individuals remain undiagnosed, limiting opportunities for early intervention and improved outcomes.

The analysis investigates demographic, lifestyle, anthropometric, and metabolic variables to understand how diagnosis status varies across populations and to highlight potential gaps in screening and detection. Emphasis is placed on uncovering individuals who exhibit elevated metabolic risk profiles but lack a formal diabetes diagnosis.

The project is implemented entirely in Jupyter Notebook and demonstrates an end-to-end analytical workflow, including data ingestion, cleaning, exploratory data analysis, subgroup stratification, and synthesis of actionable insights. The primary goal is to build analytical evidence that can inform future modeling efforts, public health strategies, and decision-support tools.

This work is intended for data scientists, researchers, and recruiters seeking a clear example of structured health data analysis, from raw data exploration to insight-driven conclusions.


## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#Objectives)
- [Dataset Description](#Dataset-Description)
- [Key Questions Explored](#Key-Questions-Explored)
- [Tools & Technologies](Tools-Technologies)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Limitations](#Limitations)
- [Data Source](#data-source)
- [ Next Steps](#Next-Steps)
- [ Data Source](#Data-Source)
- [Author](#Author)
- [License](#License)



## Project Overview
Diabetes is frequently underdiagnosed, particularly in populations with limited access to healthcare. This project explores demographic, lifestyle, anthropometric, and metabolic factors associated with diabetes diagnosis and disease stage, with the goal of identifying patterns that may contribute to underdiagnosis.

The project is intentionally focused on **exploratory data analysis (EDA)** to understand distributions, relationships, and data quality issues before any predictive modeling.

---

## Objectives
- Analyze how diabetes outcomes vary across **demographic groups**
- Examine **lifestyle and socioeconomic patterns** associated with diagnosis status
- Explore relationships between **clinical markers** and diabetes stage
- Identify potential **underdiagnosis signals** in high-risk populations
- Establish a clean analytical foundation for future modeling

---

## Dataset Description
The dataset contains individual-level health, lifestyle, and clinical variables, including:

- **Demographics:** age, gender, ethnicity, education level, income level, employment status
- **Lifestyle factors:** physical activity, diet score, sleep duration, screen time, smoking, alcohol consumption
- **Anthropometrics & vitals:** BMI, waist-to-hip ratio, blood pressure, heart rate
- **Metabolic & laboratory markers:** fasting glucose, postprandial glucose, HbA1c, insulin, lipid profile
- **Outcomes:** diabetes risk score, diabetes stage, diagnosed diabetes status

> The dataset is assumed to be anonymized and is used strictly for analytical and educational purposes.

---
## Key Questions Explored

- How does diabetes prevalence and severity vary by age, gender, ethnicity, and socioeconomic status?

- Are certain demographic groups at high metabolic risk but low diagnosis rates?

- How do lifestyle behaviors differ across diabetes stages?

- Which variables show strong associations with diabetes risk and diagnosis?

- Are there data quality or measurement issues that could bias downstream modeling?
---


## Tools & Technologies
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---
## Key Findings

After filtering for high-risk individuals and calculating undiagnosed proportions by demographic group:

- **Age is the strongest differentiator**  
  - Under 30 years old: **27.24%** undiagnosed  
  - 50–59 years: ~19.8%  
  - 60–69 years: lowest at ~19.4%  
  → Young adults with high risk are significantly more likely to go undiagnosed. Under-30s are undiagnosed at 27.24%—way higher than older groups (19-22%).

- **Other demographics show surprising consistency**  
  - Gender: ~21% across Male/Female/Other  
  - Ethnicity: 20.5%–22.1% (very narrow range)  
  - Education level: 19.7%–22.5%  
  - Income level: 19.7%–21.7%  
  → No major disparities by gender, ethnicity, education, or income among high-risk individuals.

### Bottom line: This highlights a gap in youth-focused diabetes awareness. Quantifiable wins: Targeting under-30s could prevent countless cases, saving healthcare costs and lives.
(For visuals, check the notebook—expandable with plots like age band bar charts.)
---
## Recommendations

Based directly on the analysis, here are the most important actionable recommendations:

- **Targeted Screening for Young Adults**  
  Prioritize diabetes screening and awareness campaigns specifically for high-risk individuals **under the age of 30**.  
  Channels could include universities, workplaces, social media, sports clubs, and primary care outreach.

- **Investigate Causes of Underdiagnosis in Younger Groups**  
  Conduct further qualitative and quantitative research to understand **why** younger high-risk individuals are more likely to remain undiagnosed.  
  Possible factors to explore:  
  - Lower healthcare utilization / fewer routine check-ups  
  - Lower risk perception among young people  
  - Limited screening guidelines for younger age groups  
  - Provider awareness gaps

These two recommendations represent the most significant opportunities for impact arising from this analysis.
---
### Limitations

- Cross-sectional data limits causal inference

- Lifestyle variables may be subject to self-report bias

- Diagnosis status may reflect access to care rather than true disease prevalence
---
### Next Steps

- Feature engineering and risk stratification

- Predictive modeling for underdiagnosis detection

- Sensitivity analysis across demographic subgroups

- External validation using independent datasets

----
## Data Source

- File: diabetes_dataset.csv
- Features: 31 columns (demographics, biometrics, lab results, lifestyle, risk scores)
- Target: diagnosed_diabetes (0/1)
Note: This is a synthetic/realistic dataset used for educational & demonstration purposes.
---
### Author

Joseph Innocent 
Data Analyst | Medical Laboratory Scientist. 
- Focused on applied health analytics and decision-support systems
--- 
### License

This project is for educational and analytical purposes only.
It should not be used to guide clinical decision-making.
