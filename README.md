# Student-Performance-Analysis
Student Performance Analysis - EDA and Hypothesis Testing

🎯 Project Overview
This repository contains two data analytics projects completed as part of the coursework for the **Diploma in Computer Science with Artificial Intelligence** program at the **National Institute of Business Management (NIBM)** in collaboration with **Kandy Innovation Centre (KIC)**.
The projects focus on analyzing student performance data to derive meaningful insights about educational outcomes, study habits, and demographic factors affecting academic success.

**👥 Team Members**
Abhimani Konara - KIC-DCSAI-251-F-028 
Chethani Thakshila - KIC-DCSAI-251-F-048 
Isurika Bandara-KIC - DCSAI-251-F-029

📊  Exploratory Data Analysis (CW01)
**Objective**
Perform comprehensive exploratory data analysis on student performance data to identify patterns, distributions, and relationships among various academic and demographic factors.
**Dataset Overview**
Records:199 students
Features: 16 variables
Data Types: Numeric, categorical, and factor variables
**Key Variables Analyzed**
Demographics: age, gender, school type
Academic Factors: study hours, attendance percentage, study methods
Performance Metrics: math_score, science_score, english_score, overall_score
Socioeconomic: parent_education, internet_access, travel_time, extra_activities
***Visualizations Implemented**
Bar charts for categorical variables
Pie charts for demographic distribution
Histograms for age distribution
Bar plot for gender and school type
Scatter plots for relationship analysis
Box plots for age and gender comparisons


📈 Hypothesis Testing Results (CW02)
**Objective 1: One-Sample T-Test**
Null Hypothesis: Average overall score = 75
Result: t = -8.003, df = 198, p-value = 1.006e-13
Conclusion: Average overall score is significantly lower than 75
**Objective 2: Independent T-Test***
Comparison: Overall score by internet access
Result: t = -0.8787, df = 40.233, p-value = 0.3848
Conclusion: No significant difference in scores between students with/without internet access
**Objective 3: One-Way ANOVA**
Comparison: Overall score by stress level 
Result: F = 5.275, p-value = 0.00587
Conclusion: Significant difference in performance across different stress levels

🛠️ Technology Stack
**Data Analysis**
R - Primary analysis language
RStudio - Development environment
 **R Libraries Used*
 `dplyr` - Data manipulation
 `ggplot2` - Data visualization
**Visualization Techniques**
 Bar Charts
 Pie Charts
 Histograms
 Scatter Plots
 Bar Plot
 Box Plots
**Statistical Methods Applied**
 One-Sample T-Test
 Independent Two-Sample T-Test
 One-Way ANOVA
 Descriptive Statistics




