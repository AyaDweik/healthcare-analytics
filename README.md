 Healthcare Patient Analytics (Python – Pandas, NumPy, Seaborn)
# Project Overview

This project analyzes patient behavior and operational performance within a healthcare setting.
Using a small clinical dataset, the analysis focuses on:

Patient wait times

Triage level patterns

Satisfaction scores

No-show behavior

Age group segmentation

Operational risk (wait risk categories)

The project was fully developed in Google Colab and uses real-world data cleaning and healthcare analytics techniques.

# Project Files
File	Description
Healthcare_Analytics.ipynb	Main Google Colab notebook containing the full analysis
cleaned_healthcare_data.csv	Cleaned dataset with engineered features
visualizations/	Saved plots generated during the analysis

#Key Skills Demonstrated
 1. Data Cleaning (Healthcare-Specific)

Filling missing ages using mean imputation

Filling missing genders with “Unknown”

Filling missing triage levels with mode

Filling missing wait times & satisfaction scores using median (the correct choice for skewed healthcare data)

Handling duplicates and inconsistent values

 2. Feature Engineering

Created additional fields to enhance insights:

Feature	Meaning
no_show	Indicates if the appointment was missed
wait_risk	Categorizes patient wait time into Low / Medium / High
age_group	Groups patients into Child / Adult / Middle-Age / Senior

These are core steps used in real healthcare analytics pipelines.

# Data Analysis
- Average wait time per triage level

Understand operational pressure based on severity.

- No-show rate

Important for scheduling efficiency and hospital resource planning.

- Satisfaction score patterns

Explore how satisfaction varies by:

Wait risk

Triage severity

Age group

- Wait time impact on satisfaction

A key KPI for hospitals and clinics.

# Visualizations Included

Scatterplot: Wait Time vs Satisfaction

Bar Chart: Average Wait Time per Triage Level

Bar Chart: No-Show Rate by Age Group

These visuals are commonly used in healthcare reporting and patient experience dashboards.

#Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

# How to Run This Project

To replicate the analysis:

Download or clone the repository

Open Healthcare_Analytics.ipynb in Google Colab or Jupyter Notebook

Run all cells from top to bottom

Visualizations will be generated automatically

Cleaned data will be exported as cleaned_healthcare_data.csv

# Sample Insights (From the Analysis)

Higher triage levels wait less, as expected in emergency care

Longer wait times strongly reduce satisfaction

No-show behavior varies across age groups

Wait risk categories reveal operational bottlenecks

These insights help clinics and hospitals improve:

Patient flow

Staff allocation

Appointment scheduling

Fulfillment of patient expectations
