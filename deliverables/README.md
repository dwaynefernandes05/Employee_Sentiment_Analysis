# Employee Sentiment Analysis - Deliverables

**Dataset used**: `test(in).csv`

## Top-level deliverables (folder: deliverables/)
- `test_labeled.csv` - original dataset with sentiment labels and VADER scores
- `monthly_employee_scores.csv` - monthly aggregated sentiment scores per employee
- `monthly_rankings.json` - top 3 positive and top 3 negative employees per month
- `flight_risk_employees.csv` and `.json` - flight risk detection details
- `linear_regression_model.joblib` - trained linear regression model
- `feature_scaler.joblib` - scaler used for features
- `feature_coefficients.csv` - linear model coefficients
- `model_summary.json` - training & testing metrics
- `final_project_summary.json` - concise final project summary

## Visualizations saved under /visualizations:
- sentiment_distribution.png
- monthly_sentiment_trends.png
- message_length_distribution.png
- word_count_distribution.png
- top_employees.png
- model_actual_vs_predicted.png
- model_residuals.png
- flight_risk_pie.png (if flight risks found)

## Notes and suggestions:
- Sentiment labeling uses NLTK VADER (fast and suitable for short messages).
- Predictive modeling uses linear regression as required. Consider trying RandomForest/GradientBoosting for better predictive power.
- For reproducibility: use the saved model and scaler in `deliverables/`.