# Player-Transfer-Value-Career-Forecasting
Goal: Estimate player market values and identify players who may be undervalued relative to their performance.

Build plan
1. Assemble historical player performance and valuation records.
2. Engineer age, position, minutes, contract, league, and performance features.
3. Train linear regression, random forests, and gradient-boosted models.
4. Analyse feature importance and prediction errors.
5. Cluster players by playing style.
6. Compare estimated values with observed valuations.
7. Build a scouting dashboard showing value ranges and confidence intervals.
Suggested stack: Python, scikit-learn, XGBoost, SHAP, PostgreSQL, Streamlit.

Module practice: Regression, clustering, preprocessing, evaluation, data warehousing.

Evaluation: MAE, RMSE, error by position/league, and temporal out-of-sample performance.

Extension: Predict career trajectories over three seasons using age curves and comparable players.

Data caveat: Estimated market value, actual transfer fee, and salary are different targets. Choose one explicitly and avoid using information that would not have been known at prediction time.
