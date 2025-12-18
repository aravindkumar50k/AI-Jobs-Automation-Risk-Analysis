# AI-Jobs-Automation-Risk-Analysis

# AI Impact on Jobs by 2030 - Data Analysis Portfolio Project

## Overview
This project analyzes a synthetic dataset of 3,000 job records to understand the potential impact of AI on various professions by 2030. Using **MySQL**, I performed exploratory data analysis (EDA) and advanced SQL techniques to uncover actionable insights about automation risk, salary, education, and skills.

This is a **portfolio project** built from scratch to demonstrate mid-level data analyst skills (equivalent to 3+ years experience):
- Logical problem breakdown
- Clean, efficient SQL queries
- Insight-driven storytelling

Dataset source: [AI Impact on Jobs 2030 - Kaggle](https://www.kaggle.com/datasets/khushikyad001/ai-impact-on-jobs-2030)

## Key Insights Discovered
- **Pareto Principle**: Just ~12 job titles account for ~78% of total automation risk — focus reskilling on these high-impact roles (Retail Worker, Construction Worker, etc.).
- **Education vs Risk**: High School + Low Risk jobs often pay more than PhD/Master's in Medium Risk categories — higher degrees don't always protect.
- **Protective Skills**: Certain unnamed skills show strong negative correlation with automation probability (potential indicators of creativity, complex reasoning).
- **Job Value Ranking**: Identified "best value" careers (high salary per unit of risk) — roles like Doctor, AI Engineer, and Nurse dominate.
- **Cohort & Hierarchical Analysis**: Drilled down into education-risk cohorts and variability within jobs.

## SQL Queries Included
- `pareto_automation_risk.sql` → 80/20 analysis of risk contribution
- `cohort_analysis_education_risk.sql` → Salary & skills by education + risk groups
- `protective_skills_analysis.sql` → Correlation of individual skills with risk
- `hierarchical_risk_drilldown.sql` → Top risky jobs within each education level
- `job_value_ranking.sql` → Salary-adjusted risk score for career recommendations
- Plus basic EDA and data quality checks

## Tools & Skills Demonstrated
- **MySQL**: CTEs, window functions (ROW_NUMBER, SUM OVER, PARTITION BY), correlations, aggregations
- Professional workflow: Data validation → EDA → Advanced insights → Business recommendations
- Insight communication for stakeholders

## Why This Project?
Built step-by-step with guidance to train logical thinking, query optimization, and insight generation — exactly how a 3+ year data analyst approaches real-world problems.

Feel free to fork, star, or use as inspiration for your own portfolio!

#DataAnalysis #SQL #DataAnalytics #PortfolioProject #AI #FutureOfWork
