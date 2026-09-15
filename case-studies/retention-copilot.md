# Bank Customer Retention & Advisor Copilot

**July 2026 | Sinchon Data & AI Hackathon | First place among 18 teams**

## Problem

A churn score does not tell a bank employee what to discuss with a customer. This project connected prediction, explanations, proposed interventions and a counseling workflow.

## My contribution

As representative of a three-person team, I led model comparison and tuning, validation design, SHAP explanations, probability calibration, retention-strategy calculations, Copilot design and presentation.

- Compared six models and selected a tuned LightGBM model using predefined validation criteria.
- Checked the selected candidate with a second stratified fold assignment using a different seed on the same training rows. This is a robustness check, not an independent held-out dataset. Rejected a blend whose small apparent gain did not satisfy the statistical acceptance rule.
- Used customer-level SHAP explanations and what-if predictions to connect risk estimates to proposed actions.
- Separated policy-based action selection from language generation, with staff approval and an audit record for the proposed customer-facing response.

## Result

The team won first place. The selected model achieved public leaderboard average precision of 0.73673. The project includes a local dashboard and Copilot demonstration with a deterministic mode that does not need a live language-model API.

## How to interpret the result

This was a hackathon prototype using synthetic bank-churn data, not a system deployed at a bank. Changing a feature and re-running a model is a scenario prediction, not evidence that the intervention causes that change. Retention economics depend on explicit assumptions about success rates and contact costs.

Code: [bank-retention-copilot](https://github.com/Junhan1029/bank-retention-copilot). The public repository contains the pipeline, acceptance tests, Copilot service and reports. The competition dataset, customer-level predictions and the dashboard file with embedded customer rows are excluded because competition data cannot be redistributed.

[Back to profile](../README.md) · [Explore the code](../docs/code-guide.md)
