# HR Onboarding Analytics

## 📊 Project Overview

An HR Analytics case study designed to evaluate the performance of an Old vs New Employee Onboarding Process.

The analysis compares employees from two onboarding groups to understand whether the New Onboarding Process is associated with improvements in employee engagement and 6-month retention.

### Onboarding Groups

- **Group A:** Old Onboarding Process
- **Group B:** New Onboarding Process

### Project Dataset

- **Total Employees:** 2,400
- **Group A:** 1,179
- **Group B:** 1,221

### Key Business Questions

1. Does the New Onboarding Process improve 90-day employee engagement?
2. Is 6-month employee retention different between the two onboarding groups?
3. Are the observed results consistent across joining cohorts?
4. Are the differences statistically significant?

## 🎯 Business Problem

The company introduced a New Employee Onboarding Process to improve the early employee experience and reduce employee attrition.

Management needed to understand whether employees under the New Onboarding Process showed better outcomes compared with employees who followed the Old Onboarding Process.

This case study evaluates the two onboarding groups using employee engagement, retention and statistical analysis.

## 🎯 Project Objectives

- Compare 90-day employee engagement between Old and New Onboarding groups.
- Compare 6-month employee retention between the two groups.
- Analyze onboarding performance across joining cohorts.
- Validate observed differences using statistical tests.
- Provide data-driven insights for HR management.

## 🛠️ Tools & Techniques

### Tools
- Microsoft Excel
- Microsoft Power BI

### Analytical Techniques
- Descriptive Analysis
- A/B Group Comparison
- Cohort Analysis
- Independent Two-Sample T-Test
- Chi-Square Test
- KPI Analysis
- Data Visualization


## 📂 Dataset

The project uses an employee-level HR dataset containing **2,400 employee records**.

The dataset includes employee demographics, onboarding information, engagement metrics, productivity indicators and retention outcomes.

### Main Data Categories

| Category | Examples |
|---|---|
| Employee Information | Employee ID, Age, Gender |
| Organization | Department, Location, Level |
| Employment | Employment Type, Salary |
| Onboarding | Onboarding Group, Orientation, Buddy Assignment |
| Engagement | Engagement Before, Engagement at 90 Days |
| Performance | Productivity at 90 Days, Manager Rating |
| Retention | 3-Month Retention, 6-Month Retention |
| Exit Information | Exit Date, Exit Reason |
| Cohort | Joining Month / Cohort Month |

### Key Variables

| Variable | Description |
|---|---|
| `Onboarding_Group` | A = Old Onboarding, B = New Onboarding |
| `Engagement_A` | Engagement measure for the Old Onboarding group |
| `Engagement_B` | Engagement measure for the New Onboarding group |
| `Engagement_90D` | Employee engagement measured at 90 days |
| `Retained_3M` | Whether the employee was retained for 3 months |
| `Retained_6M` | Whether the employee was retained for 6 months |
| `Cohort_Month` | Employee joining cohort |
| `Productivity_90D` | Productivity measure at 90 days |
| `Manager_Rating` | Manager performance rating |

### Data Preparation

The dataset was reviewed and prepared before analysis.

Key preparation activities included:

- Validating column data types
- Checking employee records
- Reviewing missing values
- Maintaining appropriate null values where applicable
- Preparing the dataset for Power BI analysis


## 📊 Power BI Dashboard

The Power BI dashboard was designed as a 3-page HR management analytics solution.

### Page 1 — Management Summary

Provides a high-level overview of the workforce and onboarding outcomes.

Key elements include:

- Total Employee Count
- Old vs New Onboarding Employee Count
- Average Engagement Before Onboarding
- Average Engagement at 90 Days
- Overall 6-Month Retention
- Old vs New Onboarding Retention Rate
- Department Distribution
- Location Distribution
- Employment Type
- Interactive Onboarding Group and Location Filters

### Page 2 — Cohort & Trend Analysis

Analyzes whether onboarding outcomes remain consistent across employee joining cohorts.

Key analysis includes:

- Employees by Joining Cohort
- 90-Day Engagement by Cohort
- 6-Month Retention by Cohort
- New Onboarding Retention Advantage by Cohort
- Monthly Engagement Trend
- Cohort-level business insights

### Page 3 — Statistical Validation

Provides statistical evidence supporting the dashboard findings.

Key elements include:

- T-Test P-Value
- T-Test Decision
- Chi-Square P-Value
- Chi-Square Decision
- Statistical Methodology
- Overall Statistical Conclusion
- Management Recommendation

## 🔍 Dashboard Design Approach

The dashboard follows a management-focused storytelling approach:

**Workforce Overview → Cohort Analysis → Statistical Validation → Management Action**  


## 🔍 Key Findings

### 1. Employee Engagement

The New Onboarding group recorded a higher average 90-day engagement score than the Old Onboarding group.

| Metric | Old Onboarding (A) | New Onboarding (B) |
|---|---:|---:|
| Average 90-Day Engagement | 69.97 | 75.72 |
| Difference | | **+5.75 points** |

The New Onboarding group showed an average engagement advantage of **5.75 points**.

### 2. Employee Retention

The New Onboarding group also recorded a higher 6-month retention rate.

| Metric | Old Onboarding (A) | New Onboarding (B) |
|---|---:|---:|
| 6-Month Retention | 45.38% | 69.86% |
| Difference | | **+24.48 percentage points** |

The retention rate for the New Onboarding group was **24.48 percentage points higher** than the Old Onboarding group.

### 3. Cohort Consistency

The analysis was further segmented by joining cohort to determine whether the observed pattern was consistent across different employee joining months.

The New Onboarding group showed higher engagement and retention across all four analyzed cohorts:

- January
- February
- March
- April

The cohort-level retention advantage ranged from approximately **+20.19 to +28.03 percentage points**.

### 4. Overall Business Insight

The analysis shows that employees in the New Onboarding group had higher 90-day engagement and higher 6-month retention than employees in the Old Onboarding group.

The consistency of the pattern across cohorts provides additional context for management when evaluating the onboarding process.
