# Business Expansion Feasibility Planner

Upload CSV or Excel records, select multiple worksheets, confirm field/category matches, and generate a reviewable 36-month pre-tax expansion forecast.

Supports monthly summaries, sales transactions and single-category expense tables in CAD. Missing values stay unknown; duplicate and overlapping sources are flagged. Includes opening delays, ramp-up, seasonal assumptions, debt repayment, cash break-even, sales scenarios and downloadable reports.

This is a portfolio testing preview. The included cafe sample is fictional. Forecasts are driven by reviewed assumptions, not verified business outcomes. It is not a complete accounting system: taxes, working-capital timing, cannibalization and terminal values are outside scope. Use synthetic or approved anonymised records for public testing. The application code does not persist uploads or call an AI provider; uploads are processed on the hosting server during the session.

## Run

Install requirements.txt and run `streamlit run expansion_planner_app.py`.

## Streamlit Community Cloud

Select this repository, the main branch and `expansion_planner_app.py` as the entry point. No API keys or secrets are required.

The standalone deployment file is generated from the maintained local application's import, forecast and interface modules. Rebuild from those sources for future updates.
