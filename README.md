# Alumni-Tracer-Study-and-Career-Analysis-of-FST-UIN-Jakarta
## Project Overview

This project analyzes **Alumni Tracer Study data from the Faculty of Science and Technology (FST), UIN Jakarta** to understand alumni profiles, educational backgrounds, career outcomes, study duration, and curriculum relevance.

The analysis combines data preprocessing, exploratory data analysis, visualization, and alumni segmentation to identify meaningful patterns and generate data-driven insights that can support career development and curriculum evaluation.

## Objectives

* Analyze the educational and demographic profiles of FST UIN Jakarta alumni.
* Examine alumni employment status and time taken to obtain employment.
* Analyze study duration and its relationship with employment outcomes.
* Evaluate alumni perceptions of curriculum and field-of-study relevance.
* Identify distinct alumni profiles based on education and career characteristics.
* Provide data-driven recommendations for academic and career development programs.

## Data Preparation

The original dataset contained **435 alumni records and 23 variables**.

Several preprocessing steps were performed, including:

* Removing irrelevant variables such as phone numbers, email addresses, and unused employment-location information.
* Converting variables into appropriate data types.
* Standardizing inconsistent values in graduation year and income.
* Identifying and handling unrealistic income values.
* Removing records that could not be reliably interpreted.
* Creating derived variables such as **employment status**, **study duration**, and **submission month**.
* Preparing numerical and categorical variables for segmentation analysis.

After the cleaning process, **432 alumni records** were retained for the main analysis.

## Exploratory Data Analysis

The cleaned dataset was explored using descriptive statistics and visualizations to identify patterns across:

* Graduation year and graduation month.
* Time taken to obtain employment.
* Current employment status.
* Study duration.
* Employment outcomes across study programs.
* Income distribution.
* Curriculum relevance.
* Field-of-study relevance.
* Alumni form submission patterns.

### Key Findings

The analysis revealed several notable patterns:

* The dataset initially contained **435 alumni records**, with **432 records** retained after data cleaning.
* Alumni employment status varied across the dataset, with many alumni classified as currently working, while others were still seeking employment or continuing their studies.
* **46 alumni** reported having entrepreneurial experience through the tracer study data.
* Study duration was calculated from the difference between admission year and graduation year, allowing the analysis to examine the relationship between study duration and career outcomes.
* Alumni generally rated **curriculum relevance and field-of-study relevance between 3 and 5**, indicating relatively positive perceptions of how their education relates to employment needs.
* Employment outcomes differed across study programs, with **Information Technology, Biology, and Mathematics** appearing prominently among alumni who obtained employment within three months.
* **Agribusiness** appeared prominently among alumni who had not yet obtained employment.

## Alumni Segmentation

A clustering analysis was conducted to identify groups of alumni with similar educational and career characteristics.

The analysis resulted in **three alumni segments**:

### 1. Balanced

This segment contained alumni with mixed employment outcomes. It included a substantial number of recent graduates, particularly from the **2024 cohort**.

Within this group:

* **73 alumni** were classified as currently working.
* **34 alumni** were classified as not yet working.
* **30 alumni** obtained employment in less than three months.
* **41 alumni** had not yet obtained employment.
* **46 alumni** were from the Agribusiness program.
* Curriculum relevance ratings were concentrated around scores **3–5**.

### 2. Fast Employment

This segment was characterized by alumni who obtained employment relatively quickly.

Key characteristics included:

* **71 alumni** obtained employment in less than three months.
* **125 alumni** were classified as currently working.
* **63 alumni** graduated in 2023.
* Information Technology, Biology, and Mathematics were among the prominent study programs in this segment.
* Field-of-study relevance ratings were concentrated around scores **3–5**.

### 3. Not Yet Employed

This segment was dominated by recent graduates who had not yet obtained employment.

Key characteristics included:

* **104 alumni** reported that they had not yet obtained employment.
* **99 alumni** were classified as not yet working.
* **99 alumni** graduated in 2024.
* **49 alumni** were from the Agribusiness program.
* **46 alumni** obtained employment in less than three months, indicating that this segment also contained alumni with mixed career outcomes.
* Curriculum relevance ratings were particularly concentrated at **score 4**, with **103 alumni** giving this rating.

## Key Insights

The analysis indicates that alumni career outcomes are not determined by a single factor. Different combinations of **graduation year, study duration, study program, employment status, time to employment, and perceived curriculum relevance** form distinct alumni profiles.

The segmentation also highlights that recent graduates require different types of support depending on their career situation. Alumni who have already entered the workforce can provide potential networking and mentoring opportunities, while alumni who are still seeking employment may benefit from stronger career preparation and industry exposure.

## Recommendations

Based on the analysis, several recommendations were proposed:

* Strengthen career preparation through interview training, CV workshops, and job-search guidance.
* Expand internship and industry partnership opportunities.
* Develop alumni networking and mentoring programs.
* Monitor industry trends to ensure curriculum remains relevant.
* Provide additional support for students with longer study durations.
* Strengthen entrepreneurship programs as an alternative career pathway.
* Conduct further analysis to understand the factors associated with delayed employment.

## Tools & Skills

**Tools:** Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

**Skills:** Data Cleaning, Data Preprocessing, Exploratory Data Analysis, Data Visualization, Feature Engineering, Clustering, Data Interpretation, and Insight Generation.

## Project Outcome

The project transformed **435 raw tracer study records into 432 cleaned records** and generated structured insights into alumni education and career outcomes.

Through exploratory analysis and segmentation, the project identified **three distinct alumni profiles** and highlighted important patterns in employment status, time to employment, study programs, study duration, and curriculum relevance.

The findings were then translated into **actionable recommendations for career support, industry collaboration, curriculum evaluation, alumni engagement, and entrepreneurship development**.
