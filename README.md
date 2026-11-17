# Sumeet Amin

**Data Science | Applied Machine Learning | AI Engineering**

I hold a BSc in Data Science and build reproducible data and machine-learning systems that turn analysis into useful decisions. My work emphasizes leakage-aware evaluation, clear assumptions, and practical workflows across fraud detection, forecasting, model monitoring, and LLM evaluation.

## Selected projects

### [Fraud Detection Platform](https://github.com/sumeetamin/fraud-detection-platform)
End-to-end fraud scoring workflow with delayed-label simulation, a FastAPI service, analyst review queue, drift monitoring, and reproducible evaluation. On a local authenticated API replay, 1,000 requests completed with zero errors; at concurrency 16, throughput was 58.14 requests/second with 394.97 ms p95 latency on this workstation. This measures local replay performance, not hosted capacity or financial decision quality.

### [Retail Demand Intelligence](https://github.com/sumeetamin/retail-demand-intelligence)
Demand forecasting with temporal backtests, uncertainty intervals, and an inventory planning workflow. Across three held-out windows, gradient boosting reduced mean MAE 18.3% versus a seasonal baseline, but raised simulated inventory cost 9.2%; the documented recommendation is to retain the seasonal baseline for the tested cost setup.

### [LLM Evaluation Workbench](https://github.com/sumeetamin/llm-evaluation-workbench)
Evaluation tooling for traces, rubric-based grading, and benchmark analysis. On 2,675 official RAGTruth test responses from 450 disjoint source groups, a TF-IDF context/answer support baseline achieved 75.3% accuracy, 70.9% balanced accuracy, and 0.781 ROC-AUC. The workbench also prepares a source-disjoint, human-annotated RAGTruth sample for semantic-judge calibration; no semantic-judge scores are claimed yet. The benchmark result above is a lexical baseline, not the semantic LLM judge; performance varies sharply by task and is not production safety evidence.

### [Credit Risk Fairness Monitor](https://github.com/sumeetamin/credit-risk-fairness-monitor)
A 30,000-row UCI benchmark with a stratified holdout, threshold trade-offs, and subgroup error audit. The logistic-regression baseline achieved ROC-AUC 0.715 and average precision 0.499 on one split. Research prototype only; not a lending decision or fairness claim.

### [Document Verification AI](https://github.com/sumeetamin/document-verification-ai)
Local NLP and optional OCR for invoice extraction, evidence review, and purchase-order matching. The README distinguishes synthetic evaluation from real-world performance and documents supported input limits.

## Engineering approach

- Compare against simple baselines and use splits that respect time, groups, and label availability.
- Record data provenance, source fingerprints, metrics, and failure cases.
- Keep sensitive or row-level source data out of public repositories.
- Connect model outputs to review workflows, with operational limits documented.

## Tools

Python · pandas · scikit-learn · FastAPI · Streamlit · SQL · SQLite · Docker · GitHub Actions

These repositories are portfolio demonstrations. Each README states what was measured and what remains before production use.

[GitHub profile](https://github.com/sumeetamin)
