# Data Science Job Trends

## Project Overview

This project analyzes **global job trends in the data science domain** using publicly available datasets. The primary goal is to uncover patterns in salaries, job categories, work settings, and other key factors influencing compensation in the data science job market. 

The project is particularly relevant for aspiring data professionals and researchers to gain insights into job roles, salary trends, and the dynamics of remote work.


## Introduction
With the rapid growth of data-driven decision-making, data science has emerged as a critical field with diverse job opportunities. This project focuses on analyzing:
- Salary trends across different job categories (e.g., Data Scientists, Data Engineers, ML Engineers).
- Geographic variations in compensation.
- How factors like work settings (remote/hybrid), experience, and company size influence salaries.
- Purchasing power of employees in different regions.

By answering these questions, we aim to help data professionals make informed career decisions and identify high-potential job opportunities.

## Dataset Information
- **Source**: Kaggle (https://ai-jobs.net/)
- **Format**: CSV file with 12 columns and 9,355 rows.
- **Time Period**: 2020 to 2023

### Columns in the Dataset:

| Column Name          | Description                                                                |
|----------------------|----------------------------------------------------------------------------|
| **work_year**        | Year the data was recorded                                                 |
| **job_title**        | Job role title (e.g., Data Scientist, ML Engineer)                         |
| **job_category**     | Broader category for easier analysis (e.g., Data Science, ML/AI)           |
| **salary_currency**  | Currency in which salary is reported                                       |
| **salary**           | Annual gross salary in local currency                                      |
| **salary_in_usd**    | Salary converted to USD for comparison                                     |
| **employee_residence** | Country where the employee resides                                       |
| **experience_level** | Experience level (Entry, Mid, Senior, Executive)                           |
| **employment_type**  | Type of employment (Full-time, Part-time, Contract)                        |
| **work_setting**     | Work environment (Remote, In-person, Hybrid)                               |
| **company_location** | Country where the company is located                                       |
| **company_size**     | Size of the company (Small, Medium, Large)                                 |


## Key Analyses and Guiding Questions
The project addresses the following key questions:

1. **What are the trends for Data Science jobs year-over-year?**
2. **How do job categories compare in terms of salaries?**
3. **What are the key factors that affect job salaries in data science roles?**
4. **Has there been an increase in remote work opportunities in recent years?**
5. **How does the purchasing power of data science employees vary across countries?**

Each question is explored using visualizations, statistical analyses, and geographic mapping.


## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Libraries**:
    - pandas (data manipulation)
    - numpy (numerical operations)
    - matplotlib & seaborn (data visualization)
    - plotly (interactive visualizations)
    - geopandas & folium (geographic mapping)


## Results and Insights
The following are some key insights obtained from the analysis:

1. **Yearly Salary Trends**: Salaries in data science have shown consistent growth, particularly in roles like Data Engineer and ML Engineer.
2. **Remote Work Growth**: There has been a significant increase in remote work opportunities post-2020.
3. **Geographic Differences**: Salaries vary widely across countries, and purchasing power can differ significantly based on local economic conditions.
4. **Job Categories**: ML and AI roles tend to offer higher compensation compared to traditional data analysis roles.
5. **Experience Impact**: Senior-level positions command significantly higher salaries than entry-level roles.

## Future Scope
- Expanding the analysis to include job satisfaction surveys.
- Incorporating additional datasets to analyze job postings and demand.
- Using machine learning to predict future salary trends based on current data.
