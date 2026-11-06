# Customer Churn Analysis 

## Project Overview
This project focuses on analyzing customer churn patterns using Python to identify factors associated with customer cancellations and understand their impact on business revenue.

The analysis was completed as part of the **Workora Labs Data Analytics Virtual Internship**.

## Objectives
- Calculate customer churn and retention rates.
- Estimate Customer Lifetime Value (CLV) using historical data.
- Estimate monthly revenue at risk due to churn.
- Analyze churn across contract types, tenure groups, and payment methods.
- Compare customer behavior using support tickets and late payments.
- Develop actionable customer-retention recommendations.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Information
- Total records after cleaning: 600
- Total columns: 14
- Churned customers: 247
- Retained customers: 353

## Key Findings
- Overall churn rate: **41.17%**
- Retention rate: **58.83%**
- Month-to-Month contract customers have the highest churn rate at **59.81%**.
- Customers with 0–12 months of tenure have a churn rate of **53.85%**.
- UPI users show a churn rate of **45.07%**.
- Churned customers have higher average support tickets and late payments than retained customers.
- AutoPay users and non-users show almost identical churn rates.

## Business Recommendations
- Introduce retention offers for Month-to-Month customers.
- Improve onboarding and engagement during the first 12 months.
- Investigate recurring customer support issues.
- Improve payment reminders and payment experience.
- Monitor churn indicators regularly.

## Project Files
- `customer_churn_analysis.ipynb` – Python analysis notebook.
- `customer_churn_analytics_report.pdf` – Detailed analytics report.
- `contract_churn_analysis.csv` – Contract-wise churn results.
- `tenure_churn_analysis.csv` – Tenure-wise churn results.
- `payment_churn_analysis.csv` – Payment method-wise churn results.
- `autopay_churn_analysis.csv` – AutoPay churn results.
- `behavior_analysis.csv` – Behavioral comparison.
- `charts/` – Data visualization outputs.

## Limitations
The dataset is synthetic. The findings show associations and do not establish causation. CLV is a historical-value proxy rather than a predictive future value, and monthly revenue at risk is an estimate based on recorded monthly charges.

## Conclusion
This project demonstrates how Python-based data analysis and visualization can help identify customer churn patterns, understand potential revenue risks, and support data-driven retention strategies.

---

**Prepared by: SHREE VATHY S**  
**Data Analytics Intern | Workora Labs**
