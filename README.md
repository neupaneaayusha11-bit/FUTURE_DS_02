# Customer Churn Analysis - Power BI & Python

**Future Interns | Data Science & Analytics | Task 02 (2026)**

## Objective
Understand why customers leave, which segments churn the most, how long customers stay, and what the business can do to improve retention.

## Dataset
Telco Customer Churn dataset (Kaggle), 7,043 customers.

## Tools
Python (Pandas, NumPy, Matplotlib, Seaborn), Excel, Power BI

## Project Structure
```
FUTURE_DS_02/
├── Data/                  # dataset (csv)
├── images/                # charts exported from the notebook
├── notebooks/             # Python analysis (churn_analysis.ipynb)
├── powerbi/               # .pbix dashboard file
├── powerbi_screenshots/   # dashboard preview (Dashboard.png)
├── .gitattributes
├── README.md
└── requirements.txt
```

## Key Metrics
| Metric | Value |
|---|---|
| Total customers | 7,043 |
| Churned customers | 1,869 |
| Churn rate | 26.54% |
| Retention rate | 73.46% |

## Key Insights
- Month-to-month contracts have the highest churn.
- Churn is highest in the first months of tenure.
- Customers without tech support churn much more.
- Long-term contracts improve retention.

(Update this section with your own results from the notebook.)

## Recommendations
- Incentivize 1-2 year contracts.
- Improve onboarding for new customers (first 3 months).
- Promote tech support and security add-ons.

## How to Run
```
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis.ipynb
```

## Dashboard Preview
![Dashboard](powerbi_screenshots/Dashboard.png)

## Author
Your Name | [LinkedIn](https://www.linkedin.com/) | Future Interns
