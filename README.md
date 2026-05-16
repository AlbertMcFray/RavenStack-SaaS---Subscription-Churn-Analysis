# RavenStack SaaS — Subscription Churn Analysis

Exploratory data analysis of a SaaS subscription dataset focused on identifying churn patterns, cancellation reasons, and factors influencing customer retention.

## Dataset

**Source:** [SaaS Subscription & Churn Analytics Dataset](https://www.kaggle.com/datasets/rivalytics/saas-subscription-and-churn-analytics-dataset) — Kaggle  
**Tables:** Accounts (500), Subscriptions (5000), Churn Events (600), Feature Usage (25000), Support Tickets (2000)

## Objectives

1. What is the overall churn rate? How does it vary by plan and industry?
2. At what stage of the subscription do customers churn most often — within 30 days, 30–90, or later?
3. What are the most common cancellation reasons? Is there a connection between reason and plan?
4. Does feature usage activity affect churn? Which features are associated with lower churn?
5. Is there a relationship between support quality and churn?

## Stack

- Python, Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## Key Findings

- Highest churn rate observed in the **Enterprise + DevTools** segment (37%). DevTools shows consistently high churn across all plans.
- **Cybersecurity** demonstrates the strongest retention across all plans.
- 70% of churned customers leave after 90+ days. However, ~18.5% churn within the first 30 days, indicating potential onboarding issues.
- Cancellation reasons are distributed evenly (15–19%). Features (19%) and support (17%) are slightly elevated. Enterprise clients are significantly less likely to cite support issues (12% vs 21% for Basic).
- Feature usage has no significant impact on churn — churn rate across all 40 features falls within a narrow 20–25% range.
- Support quality metrics (satisfaction score, resolution time) show no meaningful difference between retained and churned customers.
