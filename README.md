# Majors Survey Analysis (2020–2024)

## Purpose of the Project

The primary goal of this project is to explore, clean, and analyze survey data from students enrolled in computing-related courses at the County College of Morris (CCM). This analysis spans five years (Fall 2020 to Fall 2024) and provides insights into student demographics, degree interests, and recruitment effectiveness.

By standardizing and merging individual yearly datasets, the project identifies trends in student motivations and factors influencing their decision to attend CCM.

## Research Questions

This project aims to answer the following questions:

- Which degree programs show the greatest increase or decrease in student interest over time based on survey responses?
- How has the percentage distribution of female students by degree program changed over time?
- How has the percentage distribution of male students by degree program changed over time?
- Which factors had the greatest impact on students' decision to attend CCM?
- How has the way students hear about CCM changed over time?

## Analysis and Code

- `majors_survey_data_analysis.ipynb`: Main Jupyter Notebook containing the full data cleaning and analysis workflow. It standardizes long survey questions into structured column names (e.g., `heard_from_*`, `decision_impact_*`), handles data types, and merges annual CSV files into a unified dataset for analysis.

## Dataset & Methodology

**Data Loading:**  
Five separate CSV files (Fall 2020–Fall 2024) were combined into a single dataset for longitudinal analysis.

**Data Cleaning:**  
- Removed irrelevant columns (e.g., race/ethnicity, extracurricular participation) to focus on key research areas  
- Standardized column names using snake_case and descriptive prefixes  
- Handled missing values by assigning meaningful labels such as "No Impact" or "No Response"

**Categorization:**  
Over 120 unique student-entered major descriptions were mapped into standardized categories (e.g., Computer Science / IT, Engineering, Business / Economics, Health / Nursing) using keyword-based classification logic.

## Key Findings

- **Growing Interest:** The "Other" category showed the largest increase in student interest over the period (+101.7%), while Computer Science / IT had the highest growth among defined academic programs (+9.2%).
- **Declining Interest:** The Health / Nursing category experienced the largest decline (−100% within this survey dataset context).
- **Decision Factors:** Practical considerations such as location, affordability, and transfer opportunities were the strongest influences on students’ decision to attend CCM.
- **Awareness Channels:** Personal networks and school-based guidance remained the most common ways students learned about CCM.

## Technologies Used

- Python 3
- Pandas (data manipulation and cleaning)
- Matplotlib (data visualization)
- Jupyter Notebook

## Author

Mustafa Erdem