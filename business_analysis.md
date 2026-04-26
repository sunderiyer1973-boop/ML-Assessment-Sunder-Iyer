## B3(c) Deployment Strategy

**Step 1: Save Model**
- Use joblib or pickle

**Step 2: Monthly Prediction**
- Prepare new data using same preprocessing
- Feed into model to generate predictions

**Step 3: Output**
- Recommended promotion per store

**Monitoring:**
- Track prediction errors over time
- Detect performance degradation

**Retraining Trigger:**
- Changes in trends or seasonality
- Decline in model accuracy

This ensures a robust and scalable deployment system.
