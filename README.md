# Junhan Chang

**Applied Statistics at Yonsei University · Expected graduation: February 2027**  
President of YBIGTA, a student data science and AI society.

I work on problems where a prediction alone is not enough: deciding how to respond to customer churn, explaining a pre-game forecast, or identifying which retail promotions deserve more investment.

[Selected projects](#selected-projects) · [Explore my code](docs/code-guide.md) · [Skills](#skills)

### Start here

- **See how I turn a model into a workflow:** [Retention Copilot case study](case-studies/retention-copilot.md).
- **Inspect my statistical analysis:** [Retail analysis code and results](docs/code-guide.md#retail-promotion-analysis--my-implementation).
- **See an application:** [Book assistant screenshot and team project](https://github.com/Junhan1029/YBIGTA_newbie_team_project#see-the-result).

## Selected projects

### Bank Customer Retention & Advisor Copilot

**1st place / 18 teams · Sinchon Data & AI Hackathon · July 2026**

Connected churn predictions to explanations, proposed retention actions and staff approval. As the three-person team's representative, I led modeling, validation, SHAP analysis and Copilot design. The selected LightGBM model achieved **0.73673 public leaderboard average precision**.

`LightGBM` `SHAP` `Probability calibration` · **[Case study →](case-studies/retention-copilot.md)** · **[Code](https://github.com/Junhan1029/bank-retention-copilot)**

### SPOTV: Pre-game KBO Win Prediction

**SPOTV × YBIGTA · Industry collaboration · May–August 2026**

**Identified and corrected time leakage in pitcher inputs**, accepting a drop in ROC-AUC from 0.7153 to 0.6103 in the leakage check. I worked on batter features, modeling and explanations, and proposed content formats following company feedback. The case study separates this diagnostic comparison from the final model's holdout evaluation.

`Random forest` `SHAP` `Time-based validation` · **[Case study →](case-studies/spotv.md)**

### Retail Promotion Incrementality

**Project lead · YBIGTA Data Analysis · August 2026**

Investigated whether promotions generate additional demand or shift existing purchases. I owned the flyer-exposure analysis, built a household-category panel including zero purchases, and translated fixed-effects estimates into category-level decision rules.

`Python` `Panel data` `Fixed effects` · **[Case study](case-studies/retail-promotions.md)** · **[My analysis code](https://github.com/wisebell77/YBIGTA_project2/tree/main/%EC%9E%A5%EC%A4%80%ED%95%9C)**

### Financial Group Analysis at IBK

**Industrial Bank of Korea internship · July–August 2026**

Built a public-filings pipeline, validation framework and dashboard to compare **KB, Shinhan, Hana, Woori and IBK across 2019–2025**. The analysis supported the team's exploration of non-bank earnings and growth opportunities.

`Financial analysis` `Data validation` `Dashboard` · **[Case study →](case-studies/ibk.md)** · **[Code](https://github.com/Junhan1029/ibk-financial-group-analysis)**

Each case study includes my role, evaluation context and project limitations. Retail, hackathon and IBK code is public; datasets, credentials and internship documents are excluded from those repositories. SPOTV source code cannot be shared publicly.

## More projects

- **[Code reading guide](docs/code-guide.md):** direct entry points for my retail analysis, the team backend and the book-information assistant.
- [Low-floor bus crowding prediction](https://github.com/YBIGTA/28th-project-safemobility): team project supporting accessible travel; my work covered data collection and cleaning, exploratory analysis and the route 606 model.
- [YBIGTA team engineering project](https://github.com/Junhan1029/YBIGTA_newbie_team_project): coursework spanning review collection, analysis, a FastAPI backend, deployment and a separate book-information RAG chatbot.
- [YBIGTA individual assignments](https://github.com/Junhan1029/YBIGTA_newbie_assignment): learning exercises in Python, statistics, machine learning and language models.

## Skills

**Programming:** Python, R, SQL  
**Analysis:** predictive modeling, causal inference, data validation and explainability  
**Tools used in projects:** pandas, scikit-learn, LightGBM, XGBoost, statsmodels, BigQuery, Tableau, FastAPI

Team code remains in its original repository so collaborators and project history stay visible.
