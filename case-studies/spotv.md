# SPOTV: Pre-game KBO Win Prediction

**May-August 2026 | SPOTV x YBIGTA industry collaboration**

## Problem

Estimate the home team's chance of winning a KBO game using information available before the game, then explain the forecast in a form suitable for sports content.

## My contribution

- Worked on batter features, model development and SHAP explanations.
- Identified outcome information leaking into pitcher variables and revised the modeling inputs.
- Contributed to feature selection and the packaging of intermediate and final modeling outputs.
- Proposed three content formats in response to company feedback.

## Team result

The final report describes 973 games and seven selected features from 48 candidates. The team delivered a prediction pipeline, structured explanation outputs, analysis cards and social-media cards. The final model's June holdout ROC-AUC was 0.670, with a reported 95% confidence interval of 0.56-0.77.

The card-rendering and commentary components are team outputs; this page does not attribute all of their implementation to me.

## Limits

Only pre-game information was used. The holdout covered one month, and its confidence interval was wide. Live broadcast integration and load testing were outside the delivered scope. SHAP explanations describe model behavior, not causal effects.

The collaboration repository is not currently accessible to logged-out visitors. This summary does not redistribute source event logs or change the team's repository visibility.

[Back to profile](../README.md) · [Explore the code](../docs/code-guide.md) · [Explore the code](../docs/code-guide.md)
