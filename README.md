
# Diabetes Underdiagnosis Analysis

Hey there! 👋  
I'm Apostle Crypto (@innocentjoe13 on X), and this repo is my deep dive into a diabetes dataset to uncover patterns of **underdiagnosis** among high-risk individuals.

As someone passionate about using data to drive real-world health improvements, I wanted to understand why some people at clear risk of diabetes remain undiagnosed — especially since early detection can dramatically change outcomes.

This Jupyter notebook walks through data loading, exploratory analysis, demographic breakdowns, and clear, actionable insights.

If you're a recruiter or fellow data scientist checking out my work — this project shows my end-to-end approach: from raw data → insight → recommendations.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Technologies Used](#technologies-used)
- [How to Run This Project](#how-to-run-this-project)
- [Data Source](#data-source)
- [Why This Project Stands Out](#why-this-project-stands-out)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

Diabetes underdiagnosis is a major public health challenge.  
Many individuals with high risk scores (based on clinical & lifestyle factors) are not yet diagnosed — meaning they miss the window for early intervention.

This project uses a comprehensive dataset containing:

- Demographics (age, gender, ethnicity, education, income)
- Clinical measurements (glucose levels, HbA1c, cholesterol, BMI, blood pressure)
- Lifestyle factors (smoking, alcohol, physical activity, diet, sleep)

to identify **which high-risk groups are most likely to remain undiagnosed**.

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

**Bottom line**: This highlights a gap in youth-focused diabetes awareness. Quantifiable wins: Targeting under-30s could prevent countless cases, saving healthcare costs and lives.
(For visuals, check the notebook—expandable with plots like age band bar charts.)

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

## Technologies Used

- Python 3  
- Pandas – data manipulation & analysis  
- NumPy – numerical operations  
- Matplotlib + Seaborn – visualization potential  
- Jupyter Notebook – interactive exploration & storytelling

## How to Run This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/diabetes-underdiagnosis-analysis.git
2. Install dependencies
   pip install pandas numpy matplotlib seaborn jupyter
