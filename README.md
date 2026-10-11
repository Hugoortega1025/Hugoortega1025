# Hugo Ortega-Morales | [LinkedIn](https://www.linkedin.com/in/hugo-ortega-morales/) | [Portfolio](https://hugoortega.my.canva.site/hugo-s-portfolio)
### Data Science & Analytics | Python · SQL · Statistics · Machine Learning · Tableau

---

I build end-to-end data science projects that turn messy data into forecasts, tested findings and clear recommendations: from framing the business question and cleaning the data, through statistical modeling and validation, to a dashboard a manager can read in seconds.

I am completing an MS in Data Science at Pace University (May 2027), with an undergraduate foundation in Applied Mathematics and Statistics. My focus is statistical rigor that leads to decisions: checking model assumptions, validating on data the model has never seen, and being clear about what the evidence does and does not show.

---

## Featured Projects

| # | Project | Domain | Core Methods |
|---|---------|--------|-------------|
| 1 | [Health Insurance Claim Cost Forecasting](https://github.com/Hugoortega1025/health-insurance-claims-analysis) | Healthcare / Insurance | Regression · Gradient Boosting · Cross-Validation · SQL · Tableau |
| 2 | [Retail A/B Testing & Segmentation](https://github.com/Hugoortega1025/retail-ab-testing-segmentation) | Retail | Quasi-Experimental Design · Statistical Inference · Python |
| 3 | [Clinical Diabetes Readmission Risk](https://github.com/Hugoortega1025/diabetes-readmission-analysis) | Healthcare | SQL · Databricks · Risk Segmentation |
| 4 | [Bank Marketing Conversion Drivers](https://github.com/Hugoortega1025/bank-marketing-conversion-driver-analysis) | Banking / Marketing | SQL · Star Schema · Leakage Prevention · Tableau |
| 5 | [Healthcare Employee Attrition](https://github.com/Hugoortega1025/Employee-Attrition-Analysis) | People Analytics | Python · Segmentation · Tableau |

---

### 1. Health Insurance Claim Cost Forecasting
Python · SQL (DuckDB) · statsmodels · scikit-learn · Tableau

[→ Repository](https://github.com/Hugoortega1025/health-insurance-claims-analysis) | [→ Tableau Dashboard](https://public.tableau.com/views/Insurance_Dashboard_17916830318640/ClaimCostForecasting)

Forecast health insurance claim costs for 1,332 members to help an insurer budget for future claims and target prevention programs. Regression diagnostics revealed that obesity raises costs mainly for smokers; modeling this interaction removed systematic forecast errors of about $7,000 in the highest-cost segment. The final gradient boosting model, chosen by cross-validation and tested once on held-out members, is off by about $3,700 per member on average, 55% less error than a flat estimate, and an explainable linear model comes within 4–9% of it.

Key finding: smokers with obesity are 11% of members but 34% of claim costs. Recommended a prevention pilot with a comparison group to measure real savings, and showed gender can be removed from the model with no loss of accuracy.

---

### 2. Retail A/B Testing & Customer Segmentation
Python · scipy · Quasi-Experimental Design

[→ Repository](https://github.com/Hugoortega1025/retail-ab-testing-segmentation) | [→ Deliverable](https://github.com/Hugoortega1025/retail-ab-testing-segmentation/blob/main/Quantium_Retail_Analytics_Deliverable.pdf)

Evaluated a new store layout trial across 264,836 transactions and 270 stores using a matched-control design, the standard approach when random assignment isn't possible, and identified the customer segments driving chip category revenue.

Key finding: Store 77 showed a statistically significant, sustained sales uplift, confirmed by both a sales test and a customer-traffic test. The effect was driven by more customers rather than higher spend per customer, which matched the revenue profile of one of the two most valuable customer segments.

---

### 3. Clinical Diabetes Readmission Risk
SQL · Databricks

[→ Repository](https://github.com/Hugoortega1025/diabetes-readmission-analysis) | [→ Deliverable](https://github.com/Hugoortega1025/diabetes-readmission-analysis/blob/main/Diabetes_Readmission_Deck.pdf)

Analyzed 101,766 diabetic patient encounters across 130 U.S. hospitals to identify which patients drive Hospital Readmissions Reduction Program (HRRP) penalties.

Key finding: prior inpatient history is the dominant driver, with readmission rising from 8% for patients with no prior admissions to 44% for those with 8 or more. The same driver explained an initially puzzling high-risk signal among young adults. Recommended a simple flag (2+ prior visits) that hospitals can apply at discharge with data they already collect.

---

### 4. Bank Marketing Conversion Drivers
SQL · Databricks · Star Schema · Tableau

[→ Repository](https://github.com/Hugoortega1025/bank-marketing-conversion-driver-analysis) | [→ Tableau Dashboard](https://public.tableau.com/views/Bank_Telemarketing_17853686325390/Dashboard1)

Modeled 41,176 telemarketing contacts into a star schema and used SQL to find which customers, contact histories and economic conditions predict term-deposit conversion, while excluding call duration from all targeting logic because it is only known after the call (target leakage).

Key finding: customers in high-converting life stages with prior contact history convert at 44.3%, nearly 4× the 11.3% baseline. Capping outreach at 3 attempts per lead would cut 18.5% of call volume while forgoing only 12% of conversions.

---

### 5. Healthcare Employee Attrition
Python · Tableau

[→ Repository](https://github.com/Hugoortega1025/Employee-Attrition-Analysis) | [→ Tableau Dashboard](https://public.tableau.com/views/EmployeeAttrition_17799308935310/AttritionAnalysis)

Analyzed 1,676 employee records across three clinical departments to find the drivers behind a 12% attrition rate.

Key finding: overtime workers are 28% of the workforce but 70% of departures. Employees who are under 35, in the bottom salary quartile, in their first two years and working overtime leave at 55%, nearly five times the company average.

---

## Technical Stack

Languages: Python · SQL · R (coursework)
Python: pandas · NumPy · statsmodels · scikit-learn · SciPy · matplotlib · seaborn
Data and BI: DuckDB · Databricks · MySQL · Tableau · Excel
Methods: Multiple Regression & Diagnostics · GLMs · Cross-Validation · Gradient Boosting · Random Forest · Regularization · A/B Testing & Quasi-Experimental Design · Confidence Intervals · Segmentation · Relational & Star Schema Design

---

## Background

- MS in Data Science, Pace University (expected May 2027)
- BA in Applied Mathematics (Statistics Track), Siena University
- Bilingual: English & Spanish
- Passionate about football, which is where my interest in analytics started; the methods travel to any domain


