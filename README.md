# E-Commerce Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.13-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-3.2.0-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Overview
This project analyzes 400,000+ real transactions from a UK based e-commerce store to identify customers at risk of churning and quantify the revenue impact.

---

## Business Problem
- Which customers were about to leave?
- How much revenue was at risk?
- What was driving customer churn?

---

## Dataset
| Property | Value |
|---|---|
| Source | UCI Online Retail II |
| Transactions | 400,916 |
| Customers | 4,312 |
| Countries | 37 |
| Total Revenue | £8,798,233 |

---

## Customer Segments
| Segment | Customers | Revenue |
|---|---|---|
| Champion | 1,105 (25.6%) | £58,35,924 |
| Loyal | 794 (18.4%) | £11,82,875 |
| At Risk | 848 (19.7%) | £9,23,571 |
| Potential | 710 (16.5%) | £3,34,220 |
| Lost | 855 (19.8%) | £5,21,641 |

---

## Key Findings
- 33.3% of customers churned
- £14,45,213 total revenue at risk
- Champions generate 66% of total revenue
- Purchase Frequency is biggest churn driver

---

## ML Model
| Property | Value |
|---|---|
| Algorithm | XGBoost Classifier |
| Accuracy | 71.15% |
| Top Feature | Purchase Frequency |

---

## Business Recommendations
1. **Protect Champions** → 66% of revenue depends on them
2. **Re-engage At Risk** → 848 customers worth £9 lakh
3. **Focus on Frequency** → biggest churn driver

---

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core analysis |
| Pandas | Data cleaning |
| Matplotlib | Visualization |
| XGBoost | Churn prediction |
| SHAP | Model explainability |

---

## Project Structure
```
ecommerce-churn-analysis/
├── notebooks/
│   └── 01_eda.ipynb
├── outputs/
│   ├── rfm_final.csv
│   ├── rfm_churn_scores.csv
│   └── segment_summary.csv
└── README.md
```

---

## Author
  Akash Kumar
- GitHub : https://github.com/Akashkmr180/ecommerce-churn-analysis
