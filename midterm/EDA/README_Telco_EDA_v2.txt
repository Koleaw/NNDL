
Telco Customer Churn — EDA v2 (deeper)
--------------------------------------
Open `telco_eda_v2.html`, choose the CSV, click "Load CSV".

Added beyond v1:
- Types and quick schema
- Duplicates & quality checks (customerID uniqueness; suspicious zeros)
- Missing-values table
- Numeric histograms and summary stats (min/median/quantiles)
- More categorical churn insights (SeniorCitizen, PaperlessBilling, PaymentMethod)
- Associations with churn: point-biserial (numeric), Cramér’s V (categorical), ranked
- Contract × Tenure segments (top risk segments)
- Class imbalance with recommended class weights
- Auto summary bullets + JSON export
