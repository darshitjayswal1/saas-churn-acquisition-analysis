# Customer Churn & Retention Analysis

> **SaaS business analysis** uncovering why paid acquisition converts at half the rate of organic — with cohort retention heatmap, funnel analysis, and MRR tracking.

## 📊 Dashboard Preview

| Chart | Insight |
|-------|---------|
| Acquisition Funnel | 6,000 leads → 1,438 paid customers (24% overall conversion) |
| Channel Conversion | Referral (36.5%) vs Meta Ads (13.1%) — 2.8x difference |
| Organic vs Paid | Organic converts at 30%, Paid at only 16.9% |
| MRR Over Time | Grew from $0 to $34k+ over 24 months |
| MRR by Channel | Organic drives $25k MRR vs Paid's $9k despite similar lead volume |
| Cohort Retention Heatmap | Early cohorts retaining 50%+ after 24 months |
| Regional Breakdown | India (615 paid), US (315), UK (181) top markets |

## 🔍 Key Business Questions Answered

1. **Why is paid acquisition underperforming?** — Meta Ads (13.1%) and Google Ads (16.0%) convert at roughly half the rate of Referral (36.5%) and Organic Search (28.7%)
2. **Is MRR growing healthily?** — Yes, $34k+ MRR, but organic customers account for 75%+ of revenue
3. **Which cohorts retain best?** — Jan 2025+ cohorts show stronger Month 6+ retention than 2024 cohorts
4. **Top markets by conversion** — All regions convert within 22-25% range, India leads volume

## 📁 Files

| File | Description |
|------|-------------|
| `Customer_Churn_Analysis.ipynb` | Full analysis notebook with all charts |
| `Churn_Analysis_Dashboard.html` | Interactive dashboard (open in browser) |
| `customers.csv` | 6,000 customer records with acquisition journey |
| `subscriptions_monthly.csv` | Monthly subscription data for MRR & cohort analysis |

## 🛠 Tech Stack

- **Python** (pandas, numpy)
- **Plotly** (interactive charts: Funnel, Heatmap, Area, Line, Bar)
- **Jupyter Notebook**

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/darshitjayswal1/customer-churn-retention-analysis

# Open in Jupyter
jupyter notebook Customer_Churn_Analysis.ipynb

# Or open the interactive dashboard directly
open Churn_Analysis_Dashboard.html
```

## 💡 Recommendations (from analysis)

1. **Reduce Meta Ads spend** — 13.1% CVR is below break-even for most SaaS CAC models
2. **Double down on Referral program** — highest CVR at 36.5% with low acquisition cost
3. **Investigate 2024 cohort churn** — early cohorts show faster Month 12+ decay vs 2025 cohorts
4. **Organic SEO/Content investment** — drives 75% of MRR at 30% CVR

---
*Dataset: Proprietary SaaS customer acquisition data (2024-2026)*
