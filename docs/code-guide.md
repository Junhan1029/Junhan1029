# Explore my code

[← Profile](../README.md)

Start with the retail analysis for statistical reasoning, or the team engineering project for application code. Links point to the original repositories and contributor history.

## Retail promotion analysis — my implementation

Read in this order:

1. [Overview and setup](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/README.md).
2. [Methodology](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/docs/methodology.md) — treatment definition and estimation choices.
3. [Pipeline entry point](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/run_pipeline.py) and [source modules](https://github.com/wisebell77/YBIGTA_project2/tree/main/%EC%9E%A5%EC%A4%80%ED%95%9C/src).
4. [One-page results](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/reports/FINAL_onepage_summary.md).
5. [Data setup](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/docs/data_setup.md) and [reproducibility notes](https://github.com/wisebell77/YBIGTA_project2/blob/main/%EC%9E%A5%EC%A4%80%ED%95%9C/docs/reproducibility.md) before attempting a run.

The linked folder is my analysis within a larger team project. Full reproduction requires the source data and environment described there. This portfolio update checked the entry points but did not rerun the full analysis.

## Team engineering project — backend and RAG

These are two coursework tracks with separate entry points.

| What to inspect | Where to start |
| --- | --- |
| Screenshots, team roles and configuration | [Project README](https://github.com/Junhan1029/YBIGTA_newbie_team_project#readme) |
| Backend | [app/](https://github.com/Junhan1029/YBIGTA_newbie_team_project/tree/main/app) |
| Collection and analysis | [review_analysis/](https://github.com/Junhan1029/YBIGTA_newbie_team_project/tree/main/review_analysis) |
| Book assistant | [streamlit_app.py](https://github.com/Junhan1029/YBIGTA_newbie_team_project/blob/main/streamlit_app.py) and [st_app/](https://github.com/Junhan1029/YBIGTA_newbie_team_project/tree/main/st_app) |
| Deployment | [Workflow](https://github.com/Junhan1029/YBIGTA_newbie_team_project/blob/main/.github/workflows/deploy.yaml) |

<details>
<summary>Preview the book assistant</summary>

![Team book-information assistant](https://raw.githubusercontent.com/Junhan1029/YBIGTA_newbie_team_project/main/aws/rag_agent_demo.png)

Historical team demonstration. See the project README for current configuration.

</details>

The backend requires MySQL/MongoDB; the assistant requires retrieval assets and Upstage configuration. The deployment workflow builds and deploys a container but has no test gate. A clean installation and full test run remain unverified in this portfolio review.

## Project summaries

| Project | Read about |
| --- | --- |
| [Retention Copilot](../case-studies/retention-copilot.md) | Model selection, a second fold assignment, explanations and staff approval |
| [SPOTV](../case-studies/spotv.md) | Pre-game leakage controls, holdout evaluation and content delivery |
| [IBK](../case-studies/ibk.md) | Public-filings reconciliation and a comparison dashboard |

These pages currently describe the projects and my contributions. **Hackathon and IBK code can be released publicly**, but public source packages have not yet been posted. **SPOTV code cannot be shared publicly.** Dataset redistribution and disclosure of credentials or internship documents are outside the code-release scope.
