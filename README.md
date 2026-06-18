# Credit Risk Scoring Model

**Business question:** Which borrowers are likely to 
default — and how early can a model identify them?

## Results
- **88% AUC-ROC** on holdout test set
- **12 features engineered** from raw borrower and 
  transaction data
- Best model: XGBoost, outperforming Logistic 
  Regression and Random Forest
- Threshold optimised for business risk tolerance — 
  tuned to catch more defaulters at acceptable 
  precision cost

## The problem
Lenders need to assess credit risk before issuing 
loans. Manual review is slow and inconsistent. 
This model automates that assessment using 
historical borrower data and assigns a probability 
of default that can inform approval decisions.

## Tools & Libraries

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Author

Ruth Bonareri Ondiere
