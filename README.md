# Student Dropout & Academic Success Analysis

### Higher Education Analytics | Tableau | Data Visualization

## Project Overview

This project explores the relationship between first-semester academic performance and student outcomes using a dataset of 4,424 students from a Portuguese higher education institution.

The analysis investigates whether students who graduate achieve higher first-semester grades than students who drop out, and examines how zero-grade records influence the results.

## Business Problem

A university's Student Success and Retention Office wants to identify academic patterns associated with student dropout and understand where additional student support may be needed.

### Key Research Questions

1. Do graduates have higher first-semester grades than dropouts?
2. How prevalent are zero grades among students who drop out?
3. How does removing zero-grade records change the comparison?

## Dataset

**Source:** UCI Machine Learning Repository

**Dataset:** Predict Students' Dropout and Academic Success

**Records:** 4,424 students

**Features:** 36

**Citation:** Realinho, V., Vieira Martins, M., Machado, J., & Baptista, L. (2021). Predict Students' Dropout and Academic Success. UCI Machine Learning Repository. https://doi.org/10.24432/C5MC89

## Tools & Technologies

- Tableau — Interactive dashboards and visualizations
- Excel / CSV — Dataset preparation and inspection
- Statistical Analysis — Group comparisons and sensitivity analysis

## My Analysis

I focused on comparing first-semester academic performance between graduates and students who dropped out.

The dashboard includes:

- Average first-semester grades by student outcome
- Zero-grade prevalence
- First-semester grade distributions
- Sensitivity analysis excluding zero-grade records

## Key Findings

### 1. Graduates had higher average grades

- Graduates: 12.64
- Dropouts: 7.26
- Difference: Approximately 5.39 points

### 2. Zero grades were concentrated among dropouts

- Approximately 40.1% of dropouts had zero first-semester grades.
- Approximately 3.5% of graduates had zero first-semester grades.

### 3. Zero grades influenced the comparison

Excluding zero-grade records reduced the difference between graduates and dropouts, demonstrating the importance of investigating data distributions before interpreting averages.

## Dashboard Preview

![Student Dropout Dashboard](images/student-dropout-dashboard.png)

## Interactive Dashboard

[[View on Tableau Public](https://public.tableau.com:9443/views/FinalStudentDropoutDashboard/StudentDropoutStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Business Recommendations

- Investigate students with no completed first-semester coursework.
- Monitor early academic performance to identify potential support needs.
- Distinguish between low academic achievement and students who may not have completed assessments.
- Explore additional academic and socioeconomic factors before drawing causal conclusions.

## Limitations

This is an observational analysis. The association between grades and student outcomes does not establish causation.

The dataset also includes academic results collected after enrollment, so these findings should not be interpreted as an enrollment-time prediction model.

## Team Acknowledgment

Developed as a group project for IS465 Advanced Information Systems at NJIT.

Team members:
- Daniel Kinatukara
- Feryal Alnairab
- Luis Gaspar
- Peter Ayansiji
- Arielis Canela

My primary contribution focused on first-semester academic performance, zero-grade prevalence, grade distributions, and sensitivity analysis.
