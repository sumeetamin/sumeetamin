# Sumeet Amin

**Sports Analytics | Applied ML & Decision Systems**

I bring 2+ years across sports analytics and freelance data projects, backed by a BSc in Data Science. I build reproducible ML systems that turn data into useful decisions, with careful evaluation, clear assumptions, and practical workflows. The projects below demonstrate that approach across fraud detection, demand forecasting, and document processing.

## Selected projects

### [Fraud Detection Platform](https://github.com/sumeetamin/fraud-detection-platform)
Temporal fraud modelling with delayed-label simulation, a FastAPI scoring service, analyst review queue, drift monitoring, and reproducible evaluation. On an OpenML benchmark replay, 1,000 local authenticated requests completed with zero errors; at concurrency 16, throughput was 58.14 requests/s with 394.97 ms p95 latency on this workstation. This is not hosted capacity or financial decision evidence.

### [Retail Demand Intelligence](https://github.com/sumeetamin/retail-demand-intelligence)
Demand forecasting with temporal backtests, uncertainty intervals, and an inventory planning workflow. On three held-out windows, gradient boosting reduced mean MAE 18.3% versus a seasonal baseline, but raised simulated inventory cost 9.2%; the README recommends the seasonal baseline for the tested cost setup. Includes a reproducible Python demo with FastAPI and Streamlit.

### [Credit Risk Fairness Monitor](https://github.com/sumeetamin/credit-risk-fairness-monitor)
A 30,000-row UCI benchmark with a stratified holdout, threshold trade-offs, and subgroup error audit. The logistic-regression baseline achieved ROC-AUC 0.715 and average precision 0.499 on one split. Research prototype only; not a lending decision or fairness claim.

### [Document Verification AI](https://github.com/sumeetamin/document-verification-ai)
Local NLP and optional OCR for invoice extraction, evidence review, and purchase-order matching. The README distinguishes synthetic evaluation from real-world performance and documents supported input limits.

## How I approach ML projects

- Compare against clear baselines and use evaluation splits that respect time and label availability.
- Make assumptions, limitations, and failure cases visible.
- Include tests and repeatable run instructions alongside the model.
- Connect predictions to a review or decision workflow.

## Tools used in these projects

Python · pandas · scikit-learn · FastAPI · Streamlit · pytest · SQLite · Docker

These repositories are portfolio demonstrations. Their documentation describes what has been measured and what would still be needed before production use.

[GitHub profile](https://github.com/sumeetamin)
