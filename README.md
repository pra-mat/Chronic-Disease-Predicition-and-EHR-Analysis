# Chronic Disease Prediction & EHR Analysis

> **Healthcare Analytics Project using Advanced Excel, Python, and Power BI**

## Project Overview

This project analyzes **Electronic Health Records (EHR)** to identify chronic disease patterns, blood pressure trends, cholesterol distribution, and patient risk profiles. The objective was to transform raw healthcare data into meaningful insights that can support **clinical decision-making, patient monitoring, and healthcare reporting**.

The project was completed using **Advanced Excel, Python, and Power BI**, following an end-to-end analytics workflow that included **data preparation, data transformation, exploratory data analysis (EDA), visualization, and dashboard development**. The dataset contains **100,000 patient records** with demographic and health-related attributes such as **Age, Sex, Systolic Blood Pressure, Diastolic Blood Pressure, Blood Pressure Category, and Cholesterol Level**.

---

## Business Objective

Healthcare organizations need analytical reporting to identify high-risk patients, monitor chronic disease indicators, and improve preventive healthcare strategies. This project was designed to answer key questions such as:

* How does blood pressure vary across different age groups?
* How does cholesterol level change with age?
* Which patients fall into high-risk blood pressure categories?
* What are the readmission and ICU admission trends?
* How can patient risk profiles be visualized through an interactive dashboard?

---

## Tools & Technologies

| Tool                             | Purpose                                                                             |
| -------------------------------- | ----------------------------------------------------------------------------------- |
| **Advanced Excel**               | Data transformation, categorization, Pivot Tables, Pivot Charts, dashboard creation |
| **Python (Pandas & Matplotlib)** | Data cleaning, exploratory data analysis, and patient risk visualization            |
| **Power BI**                     | Interactive dashboard development, DAX calculations, and patient risk reporting     |
| **Power Query**                  | Data preparation and transformation                                                 |

---

# Project Workflow

```text
Raw EHR Data (Excel)
          |
          v
Advanced Excel
(Data Cleaning & Categorization)
          |
          v
Python (Pandas + Matplotlib)
Exploratory Data Analysis
          |
          v
Power BI
(DAX + Interactive Dashboard)
          |
          v
Patient Risk Profile Reporting
```

---

# Advanced Excel Analysis

Advanced Excel was used extensively to prepare and categorize patient health data before visualization.

## Data Preparation

* Combined **Systolic Blood Pressure** and **Diastolic Blood Pressure** using the **CONCATENATE()** function to create a unified blood pressure field.
* Applied the **IFS()** function to classify patients into:

  * **Low**
  * **Normal**
  * **Moderate**
  * **High**
  * **Very High**

This categorization enabled easier analysis of patient health conditions across age groups.

## Dashboard Created in Excel

An interactive dashboard was built using **Pivot Tables, Pivot Charts, and Slicers**.

### Analysis Performed

#### Age vs Blood Pressure

* Compared blood pressure categories across different age groups.
* Used **Age** and **Sex** slicers for interactive filtering.
* Identified the age groups with a higher concentration of elevated blood pressure.

#### Age vs Cholesterol

* Analyzed cholesterol levels across age groups.
* Compared cholesterol patterns between male and female patients.
* Supported early identification of potential cardiovascular risk trends.

---

# Python Analysis

Python was used to make the raw healthcare data **readable, structured, and suitable for exploratory analysis**.

## Libraries Used

* **Pandas**
* **Matplotlib**

## Exploratory Data Analysis (EDA)

Using Pandas, the dataset was cleaned and transformed into an analysis-ready format.

Matplotlib visualizations and **scatter plots** were created to identify **patient risk patterns**, including relationships between:

* Age and Blood Pressure
* Age and Cholesterol
* Patient distribution across risk categories

This analysis helped uncover clusters of high-risk patients and supported healthcare risk assessment.

---

# Power BI Dashboard

Power BI was used to build an **interactive Patient Risk Profile dashboard** for healthcare reporting and decision-making.

## Power Query Transformations

* Data type conversion
* Null value handling
* Date and categorical transformation
* Preparation of an optimized data model

## DAX Measures Used

The dashboard includes custom DAX calculations such as:

* **Readmission Rate**
* **ICU Admissions**
* **Average BMI**
* **Disease Prevalence**
* **Patient Risk Profile**
* **MAX()**
* **MIN()**
* Other aggregation and KPI measures

These measures provide a comprehensive view of patient health outcomes and hospital performance metrics.

## Dashboard Features

The Power BI dashboard enables analysis of:

* Patient Risk Profile
* Readmission Rates
* ICU Admissions
* Blood Pressure Distribution
* Cholesterol Trends
* Average BMI
* Disease Prevalence
* Demographic Health Insights

Interactive filters allow users to explore healthcare metrics by **Age, Sex, and Risk Category**.

---

# Dashboard Preview

## Excel Dashboard

* Age vs Blood Pressure
* Age vs Cholesterol
* Interactive Age and Sex Slicers

## Power BI Dashboard

* Patient Risk Profile
* Readmission Rate
* ICU Admissions
* Disease Prevalence
* Average BMI
* Blood Pressure and Cholesterol Insights

---

# Key Business Insights

* Blood pressure levels increase noticeably across higher age groups.
* Cholesterol trends vary by both **age** and **sex**.
* High and Very High blood pressure categories contain the highest-risk patient population.
* Readmission and ICU metrics help identify patients requiring closer clinical monitoring.
* Interactive dashboards provide healthcare professionals with faster access to patient risk information.

---

# Skills Demonstrated

## Advanced Excel

* IFS()
* CONCATENATE()
* Pivot Tables
* Pivot Charts
* Slicers
* Dashboard Development
* Data Categorization

## Python

* Pandas
* Matplotlib
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Scatter Plot Visualization
* Patient Risk Pattern Analysis

## Power BI

* Power Query
* Data Transformation
* Data Modeling
* DAX
* KPI Reporting
* Interactive Dashboard Development
* Healthcare Business Intelligence

---

# Power BI Dashboard

**Please find the link to the Power BI Dashboard showcasing the Patient Risk Profile:**

**https://drive.google.com/file/d/1SoDR4gaGgATK7-DhGrfJFHJvkPoly8J0/view?usp=drive_link**

---

# Project Outcome

This project demonstrates my ability to perform **healthcare data analysis using Advanced Excel, Python, and Power BI**, build interactive dashboards, calculate healthcare KPIs using DAX, and identify patient risk patterns through exploratory data analysis. It reflects practical experience in **data cleaning, dashboard development, business intelligence, and healthcare analytics**, making it highly relevant for **Data Analyst, Healthcare Data Analyst, MIS Analyst, and Power BI Developer** roles.

---

# Author

**Prayank Mathur**

* LinkedIn: https://www.linkedin.com/in/prayank-mathur-b341a7359/
* GitHub: https://github.com/pra-mat
