# Report: Impact of Weather Uncertainty on Flight Delay Predictions

## 1. Introduction
Flight delays are heavily influenced by weather conditions. This report explores a machine learning model for predicting delays, incorporating uncertainty in weather data using Monte Carlo simulations.

---

## 2. Methodology
- **Data Preparation**:
  - Weather features (e.g., precipitation, snow, temperature, wind speed) were used to predict delays (`DEP_DEL15`).
- **Model Development**:
  - Logistic regression was used for classification.
  - Monte Carlo simulations added uncertainty by introducing random noise to weather features.
- **Evaluation**:
  - Metrics: Accuracy, precision, recall, ROC-AUC.
  - Visualizations: Boxplots and confidence intervals to show prediction variability.

---

## 3. Results
- **Deterministic Predictions**:
  - Logistic regression performed well under deterministic conditions.
- **Impact of Uncertainty**:
  - Higher variability in predictions for borderline cases (probabilities 0.4–0.6).
  - Consistent predictions for low- or high-probability cases.
- **Visualization**:
  - **Boxplots**: Highlighted variability across simulations.
  - **Confidence Intervals**: Showed prediction spread and uncertainty.

---

## 4. Discussion
- **Incorporating Uncertainty**:
  - Improved robustness for ambiguous cases.
  - Demonstrated the need for better weather forecasts.
- **Trade-offs**:
  - Slightly reduced accuracy but better handling of prediction uncertainty.
- **Improvements**:
  - Explore Bayesian Neural Networks and real-time weather updates for enhanced performance.

---

## 5. Conclusion
Incorporating weather uncertainty improves the reliability of flight delay predictions, especially for ambiguous cases. Monte Carlo simulations provide valuable insights into prediction confidence, enabling the development of more robust models.

---
