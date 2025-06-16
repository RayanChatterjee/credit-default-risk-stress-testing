# credit-default-risk-stress-testing
Stress testing a credit default prediction model under synthetic economic shocks using logistic regression and SHAP-based model interpretation.

This project builds on a credit default prediction model using logistic regression, based on the publicly available **"Give Me Some Credit"** dataset, shared in this account. It stress-tests this model by simulating adverse macroeconomic and behavioral conditions and analyzes how the predicted defaults respond under such stress, while also offering interpretability using SHAP values.

---

## 🚀 Project Highlights

- ✅ Builds a logistic regression model for predicting customer credit default 
- 🔄 Performs **stress testing** by synthetically modifying key financial features:
  - Increased **DebtRatio** to simulate increased debt burdens
  - Increased **NumberOfTime30-59DaysPastDueNotWorse** to simulate repayment delays
- 📊 Quantified not just net increases in predicted defaults, but also the **individual shifts** in customer risk categories (safe → risky, risky → safe)
- 🎯 Used **SMOTE** for class imbalance handling and **VIF** to address multicollinearity
- 💡 Used **SHAP values** for interpreting feature contributions to the default predictions

---
