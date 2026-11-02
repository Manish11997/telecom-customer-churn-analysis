# Telecom Customer Churn Analysis

## Project Overview

This project analyzes telecom customer churn to identify customer segments with higher churn rates, explore service and contract patterns, and estimate revenue associated with churned customers.

The project uses Python for data cleaning and exploratory data analysis, MySQL for structured querying, and Power BI for interactive reporting and business insights.

## Tools & Technologies

- **Python:** pandas, data cleaning, exploratory data analysis, feature engineering
- **MySQL:** SQL queries, aggregations, business analysis
- **Power BI:** Power Query, DAX measures, data visualization, interactive dashboards

## Business Questions

- What is the overall customer churn rate?
- How does churn vary by contract type and customer tenure?
- Which offers and internet-service segments have higher churn?
- How do churn rates differ according to selected service subscriptions?
- Which cities show unusually high churn rates?
- What is the estimated revenue associated with churned customers?

## Key Findings

- Overall churn rate: **28.4%**
- Month-to-Month contract churn: **51.9%**
- First-year tenure-group churn: **60.6%**
- Fiber Optic churn: **41.6%**

These results are descriptive findings from the current project version. They should be interpreted alongside customer counts, denominator definitions, and the validation notes in the report.

## Dashboard

The Power BI report contains three pages:

1. **Churn Overview** — customer KPIs, contract churn, and tenure patterns.
2. **Churn Drivers** — churn by offers, internet type, and internet services.
3. **Churn Reasons & Revenue** — recorded churn categories, city-level churn, and revenue-related measures.

## Business Recommendations

- Investigate churn among first-year customers.
- Review retention strategies for Month-to-Month customers.
- Validate the high churn rate associated with Offer E.
- Investigate the Fiber Optic segment.
- Examine city-level churn after validating customer counts and churn-rate denominators.
- Test retention initiatives and measure their results over time.

## Important Notes

Revenue estimates are based on the project's defined calculations and should not automatically be interpreted as confirmed current-month recurring revenue loss. The churn-category count visual and other flagged metrics should be validated before publication.

## Author

**Manish Saini**
