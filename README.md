# bank_term_deposit
README

Summary of Findings

Support Vector Machine (SVM) achieved the highest F1-score and ROC AUC, indicating superior discrimination on imbalanced data.

Logistic Regression delivered robust performance with easily interpretable coefficients, highlighting key predictors such as age and call duration.

Decision Tree offered transparent decision rules but showed slightly lower overall metrics, useful for rule-based business heuristics.

K-Nearest Neighbors (KNN) was competitive in accuracy and F1-score but more computationally intensive.

Ensemble Methods (Random Forest and XGBoost) further boosted performance, with XGBoost outperforming all individual models.


Next Steps & Recommendations

Deploy XGBoost or SVM models in production for customer scoring.

Use F1-score and Precision-Recall curves for ongoing evaluation due to class imbalance.

Incorporate SMOTE or class weights to address any residual imbalance.

Leverage Decision Tree rules for quick campaign heuristics and frontline guidance.

Implement continuous model monitoring and periodic retraining to maintain accuracy over time.

Jupyter Notebook

All analysis, code, and visualizations are available in the consolidated Jupyter Notebook:

View the full analysis notebook
