# readme_content = """# Marketing Analytics Pipeline — Olist E-Commerce

An end-to-end marketing analytics pipeline built on the Olist Brazilian
E-Commerce dataset (99,000+ orders, 96,000+ customers, 2 years of data).

This project demonstrates the full marketing analytics workflow: data
architecture, funnel analysis, cohort retention, LTV segmentation,
anomaly detection, propensity modeling, multilingual sentiment analysis,
and automated LLM-driven insight generation.

## Project Overview

| Step | Analysis | Key Finding |
|------|----------|-------------|
| 1 | Data Architecture | Joined 8 source tables into one governed master table |
| 2 | Funnel Analysis | 99.2% end-to-end conversion; biggest drop-off at shipping stage |
| 3 | Cohort Retention | 94.5% Month 1 churn — need-based purchase pattern |
| 4 | LTV Segmentation | Top 25% of customers generate 62.9% of revenue |
| 5 | Anomaly Detection | Z-score + Isolation Forest; caught Black Friday spike automatically |
| 6 | Propensity Model | VIP classifier with documented data-leakage handling |
| 7 | Sentiment Analysis | XLM-RoBERTa multilingual NLP on 40,656 reviews |
| 8 | LLM Insight Generator | Automated marketing brief pipeline via Claude API |

## Key Techniques

- **Data integration**: Joining orders, customers, payments, reviews, and
  products across 8 tables with identity resolution
- **Cohort analysis**: Retention heatmap tracking repeat purchase behavior
- **Customer segmentation**: LTV-based tiering (Low / Medium / High / VIP)
- **Machine learning**: Random Forest and Gradient Boosting propensity models
- **NLP**: XLM-RoBERTa transformer model for multilingual sentiment
- **Anomaly detection**: Statistical (z-score) and ML (Isolation Forest) methods
- **Automated insights**: LLM pipeline generating executive marketing briefs

## Tools

Python, pandas, scikit-learn, transformers (XLM-RoBERTa), matplotlib,
seaborn, VADER, Anthropic Claude API

## Repository Structure
## Business Context

This project mirrors the challenge of building a centralized Marketing
Data Mart — integrating fragmented data sources into one governed source
of truth, then operationalizing insights through analysis and automated
reporting.

## Author

Kehinde Oduwaye — Data & Analytics Professional, Atlanta, GA
"""

with open('/content/olist_marketing_analytics/README.md', 'w') as f:
    f.write(readme_content)

print("  ✓ README.md created")
