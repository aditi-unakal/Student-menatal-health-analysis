# Student Mental Health Analysis using R and Power BI

## Project Overview
This project focuses on exploratory data analysis (EDA) of student mental health data using R and Power BI. The motivation for this project was inspired by the EUROSTUDENT VIII report on student well-being in the European Higher Education Area, which highlights increasing mental health concerns among university students.

The aim of this project is to analyze patterns associated with depression, anxiety, and panic attacks among students and identify possible relationships between mental health indicators and demographic or academic factors such as gender, CGPA, course, marital status, and year of study.

 ---
# Objectives
- Perform data cleaning and preprocessing using R
- Conduct exploratory data analysis (EDA)
- Analyze relationships between mental health indicators and student attributes
- Apply statistical testing using Chi-square tests
- Create an interactive Power BI dashboard for visualization and insights

---

# Tools and Technologies Used
- R
- R Markdown
- Power BI
- ggplot2
- janitor

---

# Dataset Information
The dataset contains student responses related to:
- Gender
- Age
- Course
- Current year of study
- CGPA
- Marital status
- Depression
- Anxiety
- Panic attacks
- Specialist treatment seeking behavior

---

# Data Cleaning and Preprocessing
The following preprocessing steps were performed:
- Cleaned column names using `janitor`
- Handled missing values
- Grouped CGPA categories
- Created age groups
- Standardized categorical values
- Generated percentage-based summaries

---

# Exploratory Data Analysis
The analysis included:
- Frequency analysis
- Percentage analysis
- Gender vs Depression
- CGPA vs Depression
- Course vs Depression
- Anxiety vs Depression
- Panic Attack vs Depression
- Marital Status vs Depression

Statistical significance between variables was analyzed using Chi-square hypothesis testing.

---

# Key Findings
- Anxiety showed a strong association with depression.
- Students reporting panic attacks were more likely to also report depression.
- Marital status showed statistically significant association with depression, although the sample size for married participants was very small.
- Gender-based differences in depression were not statistically significant in this dataset.

---

# Power BI Dashboard
The Power BI dashboard includes:
- Student mental health KPI cards
- Course-wise depression analysis
- CGPA vs Depression visualization
- Gender distribution analysis
- Anxiety and Panic Attack heatmap
- Interactive slicers and filters

## Dashboard Screenshot
<img width="1054" height="594" alt="image" src="https://github.com/user-attachments/assets/708e7de0-037d-4c18-a00b-1065920d248c" />
The dashboard provides an interactive overview of student mental health patterns and demographic factors. It includes KPI indicators, course-wise depression analysis, CGPA-based comparisons, and visualizations highlighting relationships between anxiety, panic attacks, and depression. Interactive slicers allow dynamic filtering of the dataset based on gender, age group, and academic attributes.

## Filtered Dashboard view: Female Students
<img width="1056" height="594" alt="image" src="https://github.com/user-attachments/assets/b04d021b-7048-40b8-a371-c610ba954aa0" />
The dashboard was filtered to analyze mental health patterns specifically among female students. Female participants constituted a major proportion of the dataset, with 75 female students represented in this filtered view.
The analysis indicates that a considerable number of female students reported depression, anxiety, and panic attacks. The heatmap visualization also suggests a noticeable relationship between anxiety and panic attacks among female participants.
From the academic perspective, most female students belonged to the higher CGPA category (3.0–4.0). However, cases of depression were still observed within this group, suggesting that higher academic performance alone may not necessarily correspond to better mental well-being.
The course-wise analysis further highlights variations in depression prevalence across different academic disciplines, with Engineering and BCS showing comparatively larger student counts in the dataset.

## Filtered Dashboard view: Male Students
<img width="1055" height="594" alt="image" src="https://github.com/user-attachments/assets/13820c79-53c6-47ca-b665-f89276da3c44" />

The dashboard was filtered to analyze mental health trends among male students. Male participants represented a smaller proportion of the dataset, with 25 students included in this filtered view.
Compared to female students, a lower number of male students reported depression. However, cases of anxiety and panic attacks were still observed within the male student group. The heatmap analysis suggests that students reporting anxiety were also more likely to report panic attacks.
Most male students belonged to the higher CGPA category (3.0–4.0), indicating generally strong academic performance within the sample. Despite this, depression and anxiety cases were still present, suggesting that mental health concerns may exist independently of academic achievement.
The course-wise analysis shows that Engineering and BCS contributed the largest number of male students in the dataset, while several other courses had relatively smaller representation.


# Limitations
- Small dataset size
- Self-reported responses
- Limited demographic diversity
- Results cannot be generalized to all student populations

---

# Conclusion
This project demonstrates practical data science workflows involving data cleaning, exploratory data analysis, statistical testing, and dashboard visualization techniques using R and Power BI. The analysis highlights important patterns associated with student mental health and showcases healthcare-oriented analytical reporting.
