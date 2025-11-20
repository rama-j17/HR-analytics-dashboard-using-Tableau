# HR Analytics Dashboard (Tableau)

📌 Project Overview

This project presents a comprehensive HR Analytics Dashboard designed to help HR managers monitor workforce trends, evaluate employee demographics, and analyze compensation patterns. It enables both strategic decision-making and granular analysis through interactive visualizations and detailed employee records.

The dashboard is powered by a synthetically generated dataset of 8,950 employees, created using Python with realistic business logic and controlled distributions.

🎯 Objectives

The dashboard is built to help HR teams:

Monitor overall workforce health and trends

Track hiring and termination patterns over time

Understand demographic composition and performance distribution

Identify salary patterns and potential disparities

Analyze employees at both summary and individual levels

📊 Dashboard Structure
1. Summary View
Overview

Provides a snapshot of core HR metrics:

Total hired, active, and terminated employees

Year-wise hiring vs termination trends (2015–2024)

Employee distribution by department and job title

Comparison of employees between:

Headquarters (New York)

Branch locations

Geographic distribution by city and state

Demographics

Insights into workforce composition:

Gender ratio

Distribution by age groups

Distribution by education levels

Employee count per age group

Employee count per education level

Correlation between education level and performance rating

Income Analysis

Salary-focused insights:

Salary comparison by education level for both genders

Age vs salary correlation segmented by department

2. Employee Records View

A detailed, filterable table containing:

Employee ID

First & Last Name

Department

Job Title

Gender

Age

Education Level

Salary

Employment Status

✅ Fully filterable across all columns for targeted analysis

🧠 Data Generation Process

The dataset was created programmatically using Python with ChatGPT-assisted prompt design to ensure realism and consistency.

Dataset Specifications

Total Records: 8,950 employees

Key attributes:

Unique Employee ID

Random first & last names

Gender (46% Female, 54% Male)

State & city mapping

Hire dates (2015–2024 with weighted probabilities)

Department & job title (probability-driven mapping)

Education level derived from job title

Performance rating (weighted categories)

Overtime status (30% Yes, 70% No)

Salary based on role and department

Birth dates aligned with age distribution

Termination dates for 11.2% of employees

Adjusted salary calculated using modifiers (age, education, gender)

⚙️ Technical Implementation

Python used for data generation and preprocessing

Rule-based logic for realistic HR data simulation

Modular script design with clear function separation

Full validation to ensure:

Consistent dates

Logical age at hire

Role-education alignment

🛠 Tools & Technologies

Power BI – Dashboarding & Visualization

Python – Synthetic data generation

Pandas – Data manipulation

Excel – Intermediate data inspection

✅ Key Features

Interactive filters & slicers

Department-wise & role-based insights

Salary equity analysis

Demographic-driven performance insights

Realistic large-scale HR dataset simulation

🚀 Use Cases

HR workforce planning

Compensation benchmarking

Diversity & inclusion analysis

Talent acquisition trend analysis
