## Component Architecture: 

# Component 1 — Data Prep

Load raw data
Clean missing values
Encode categoricals
Split train/test
Output processed dataset (parquet)

# Component 2 — Training

Load processed data
Train LightGBM
Save model to outputs
Log metrics

# Component 3 — Evaluation

Load model
Run metrics
Generate eval JSON

# Component 4 — Scoring

Accept JSON input
Return prediction