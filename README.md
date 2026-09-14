# Payroll Workforce Analysis

An end-to-end payroll analysis project examining employee compensation, departmental payroll costs, salary distribution, workforce demographics, tenure and data quality. The analysis was developed from a stakeholder perspective to identify actionable insights and recommendations for management.

The analysis follows a professional data analytics workflow:
Data Inspection → Data Cleaning → Validation → Exploratory Analysis → KPI Development → Visualization → Insights → Recommendations

### Key Results

- ₦21.53M monthly gross payroll
- ₦17.22M monthly basic payroll
- ICT is the largest payroll cost centre
- 48% of employees fall within the ₦250K–₦350K salary band
- Average male basic salary: ₦384,400
- Average female basic salary: ₦304,400
- 5.76 years average employee tenure

## Screenshot 1 — Executive Dashboard
<img width="947" height="547" alt="image_2026-09-14_132925809" src="https://github.com/user-attachments/assets/d7675472-1a96-456a-85f1-1075f8c63f00" />

## Department Analysis
The analysis found that ICT is the largest payroll cost centre,accounting for approximately 21.4% of basic payroll.

## Screenshot 2 — Department Analysis
<img width="1096" height="562" alt="Employee department screenshot" src="https://github.com/user-attachments/assets/3d63fd26-07b5-46b2-803c-5932d2a29380" />

## Workforce & Pay Equity Analysis
The workforce is evenly split by gender, with:
-	25 female employees
-	25 male employees

## Average basic salary by Gender:
- Male	  ₦384,400
- Female	₦304,400

<img width="607" height="347" alt="Employee gender salary analysis screenshot" src="https://github.com/user-attachments/assets/64cfad3f-bd41-4133-8123-b1363ef5e92c" />

## Analytical Approach
1. Data Understanding
2. Data Cleaning
3. Data Quality Validation
4. Payroll Calculation Validation
5. Descriptive Analysis
6. Department Analysis
7. Salary Distribution Analysis
8. Workforce Demographic Analysis
9. Pay Equity Signal Analysis
10. Insight Generation
11. Recommendations
12. Stakeholder Reporting

## Data Quality Finding

During validation, I identified an inconsistency between the
calculated payroll figures in the primary salarydata sheet and
the displayed values in another workbook section.

Further investigation indicated that the displayed figures were
consistent with stale/unrecalculated Excel formula values.

I therefore used the validated salarydata calculations as the
primary analytical source and recommended:
- Recalculation of workbook formulas
- Establishment of a single source of truth
- Automated payroll reconciliation checks
- Validation controls before stakeholder reporting

## Business Recommendations
1. Establish a single payroll source of truth
Eliminate conflicting versions of payroll calculations and clearly identify the authoritative dataset.
2. Strengthen payroll controls
Implement checks for:
- Duplicate employee IDs
-	Missing information
-	Formula errors
-	Incorrect deductions
-	Gross/net salary reconciliation
3. Review compensation architecture
Introduce formal:
-	Job grades
-	Salary bands
-	Role-based compensation
-	Career progression frameworks
4. Conduct a detailed pay-equity review
Investigate the observed gender salary difference using like-for-like comparisons.
5. Improve management reporting
Develop a recurring payroll dashboard covering:
-	Headcount
-	Basic payroll
-	Gross payroll
-	Net payroll
-	Department payroll
-	Average salary
-	Salary distribution
-	Payroll trends

## Skills Demonstrated
### Technical Skills
- Microsoft Excel
- Data Cleaning
- Data Validation
- Pivot Tables
- Excel Formulas
- Data Visualization
- Descriptive Statistics
- Payroll Analysis

### Analytical Skills
- Data Quality Assessment
- KPI Development
- Salary Distribution Analysis
- Departmental Analysis
- Demographic Analysis
- Pay Equity Analysis
- Insight Generation

### Business Skills
- Stakeholder Reporting
- Business Recommendations
- Executive Communication
- Data Storytelling

## Project Deliverables

- [Stakeholder Analysis Report](report/Payroll_Stakeholder_Analysis_Report.pdf)
- [Excel Analysis Workbook](analysis/payroll_analysis.xlsx)
- [LinkedIn Project Post](linkedin/LinkedIn_Project_Post.md)


