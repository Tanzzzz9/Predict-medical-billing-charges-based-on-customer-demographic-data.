# Predict-medical-billing-charges-based-on-customer-demographic-data.
Identifies cases where the actual billed amount is a massive statistical outlier (>3 standard deviations) above the model's predicted cost, flagging potential overcharging or waste.
## Approach easy 1
1. Load data.
2. Explore and preprocess.
3. Encode categorical features.
4. Engineer useful features.
5. Train Gradient Boosting model.
6. Evaluate performance.
7. Detect anomalies using residual Z-scores.
   
## Engineering Decisions
- Label encoding for binary features.
- One-hot encoding for region.
- Gradient Boosting for nonlinear patterns.
- Fixed random state for reproducibility.
