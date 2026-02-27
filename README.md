# Loan Default Prediction

Compares 3 ML models to predict loan default risk and segments 
borrowers into Low, Medium, and High risk categories.

##  Business Problem
Lenders need to identify high-risk borrowers before approving loans. 
This analysis builds and compares multiple models to find the best 
predictor of loan default.

##  What This Analysis Does
- Cleans and engineers 20+ features from raw loan data
- Creates financial ratios (loan-to-income, interest-to-income)
- Compares Logistic Regression, Random Forest & XGBoost
- Evaluates models using ROC-AUC, Precision, Recall, F1-Score
- Segments borrowers into Low / Medium / High default risk

##  Results
- Best model selected by ROC-AUC on held-out test set
- Borrowers segmented into 3 risk tiers using predicted probabilities
- Top default predictors identified via feature importance

##  Technical Stack
Python, scikit-learn, XGBoost, pandas, seaborn, matplotlib, statsmodels

## 🗂️ Files
| File | Description |
|------|-------------|
| `Team_4.ipynb` | Team_4_loan_with_risk_segments_updated_.csv |
