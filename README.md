Class Result Analysis using Python
Project Overview

Class Result Analysis is a data analysis project that explores the academic performance of students using Python. Instead of relying on publicly available datasets, this project uses an original dataset collected from my own class, making the analysis more relevant and meaningful.

The project analyzes the relationship between students' academic performance and factors such as attendance, gender, accommodation type, and semester-wise SPI progression. Using data visualization and statistical analysis, it uncovers trends that can help identify areas for academic improvement while maintaining student privacy.

Objectives:
1.Analyze students' academic performance across multiple semesters.
2.Study the relationship between attendance and academic results.
3.Compare CPI distribution across different genders.
4.Analyze semester-wise SPI trends.
5.Categorize students based on overall academic performance.
6.Generate actionable insights for academic mentoring.

Dataset:
The dataset was collected manually and contains anonymized records of students from five semesters.
Features Included:
Student ID (Anonymized)
Gender
State
Accommodation Type (Hosteller/Outsider)
Attendance Percentage
Semester I SPI
Semester II SPI
Semester III SPI
Semester IV SPI
Semester V SPI
CPI (Cumulative Performance Index)

Privacy Note: Personal identifiers have been removed or anonymized before analysis.

Technologies Used:
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
OpenPyXL (Excel Handling)

Data Preprocessing:

Before performing the analysis, the dataset was cleaned by:

1.Converting SPI, CPI, and attendance values into numeric data types
2.Handling missing or inconsistent values
3.Verifying data integrity
4.Preparing the dataset for visualization and statistical analysis

 Exploratory Data Analysis

The project includes various visualizations and statistical summaries to understand the dataset.

1. Gender Distribution
Number of male and female students
Comparative class composition
2. Attendance Analysis
Histogram of attendance percentages
Identification of attendance patterns across the class
3. CPI Distribution
Distribution of cumulative academic performance
Box plots for detecting variation and outliers
4. Semester-wise SPI Analysis
Average SPI across all five semesters
Semester performance trends
Identification of academically challenging semesters
5. CPI vs Attendance
Scatter plot showing the relationship between attendance and CPI
Correlation analysis between attendance and academic performance
6. Gender-wise Academic Performance
Box plots comparing CPI distributions
Analysis of performance differences between genders
7. State-wise Performance Analysis
Average CPI grouped by state
Gender-wise comparison within each state
8. Academic Performance Categories

Students were classified into performance groups such as:

1.Excellent
2.Very Good
3.Good
4.Needs Improvement

The distribution of these groups was visualized to understand the overall academic profile of the class.

 Key Insights
1.Attendance showed a modest positive correlation with CPI, indicating that students with higher attendance generally achieved better academic performance.
2.Most students belonged to the Good and Very Good performance categories.
3.A small percentage of students required academic intervention based on their overall CPI.
4.Semester-wise SPI analysis highlighted periods where overall class performance declined, suggesting relatively difficult semesters.
5.Individual SPI trends revealed that several students demonstrated consistent academic improvement over time.
6.Gender-based comparison showed variations in CPI distribution, providing additional insight into class performance patterns.

Recommendations

Based on the analysis, the following recommendations were identified:

1.Provide targeted mentoring for students with declining SPI trends.
2.Encourage higher attendance through awareness programs and academic engagement initiatives.
3.Monitor semester-wise performance to identify challenging academic periods.
4.Offer additional academic support to students in the Needs Improvement category.

Visualizations Included:
1.Histograms
2.Box Plots
3.Scatter Plots
4.Bar Charts
5.Distribution Plots
6.Semester-wise Performance Charts
7.Category-wise Performance Charts
8.State-wise Comparative Charts
