# Data Analytics Portfolio — Duver Arredondo

> Selected projects from TripleTen bootcamp + professional practice. Each folder includes context, data prep (ETL), notebook(s), and results.

## Quick Start
```bash
# (Optional) create env
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
# open notebooks
jupyter notebook
```

## Projects (overview)

| Project | Problem | Approach | Impact/Result | Stack |
|---|---|---|---|---|
| Megaline – Telecom Plan Analysis | Identify most profitable plans across regions | Descriptive stats, visualizations, hypothesis testing | Segmentation & plan adjustments → **up to +12% revenue potential** | Python (pandas, numpy, matplotlib, seaborn, scipy) |
| E-commerce – A/B Testing & Growth Prioritization | Too many ideas; need to test/learn | ICE/RICE, A/B experiments, t-test/chi-square | Highest-ROI hypothesis → **+8% sales projection** | Python (pandas, numpy, scipy) |
| Model Fitness – Churn Prediction & Segmentation | Rising churn; need early signals | Logistic Regression & Random Forest; behavioral segmentation | Retention playbook → **up to −15% churn potential** | scikit-learn, pandas, numpy, matplotlib, seaborn |
| App Funnels – Conversion & Experimentation | Measure home→payment funnel; UI change | Event validation, funnel steps, control vs test; t/chi² | No significant lift; better instrumentation & next-test design | Python (pandas, numpy, scipy) |
| Call Center – Wait Times & KPIs | High variability/abandonment | KPIs (avg/median/max wait), operator/queue ranking | Bottlenecks, workload redistribution, ops dashboard | Python (pandas, numpy), Excel |
| Zuber – Taxi Demand & Peaks | Where/when to allocate drivers | Aggregations by company/neighborhood; hourly peaks | Top zones/companies; fleet reassignment recommendations | Python (pandas, matplotlib, seaborn) |

> Each project README includes: **Problem · Data/ETL · Analysis · Results · Next Steps**.
