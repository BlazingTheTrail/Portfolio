# Transaction-Based Loan Risk POC

## Context

Developed a confidential proof of concept that transformed recent banking
transaction history into applicant-level features for loan risk assessment.
Client identity, raw data, proprietary rules, exact volumes, and production
details are intentionally withheld.

## My contribution

- Defined a point-in-time feature window to prevent post-decision leakage.
- Built cash-flow, balance, income-frequency, overdraft, and behavioral event
  features with Python, Pandas, and NumPy.
- Benchmarked logistic regression, random forest, and a TensorFlow/Keras neural
  network challenger.
- Evaluated ROC-AUC, PR-AUC, precision, recall, F1, and decision-threshold
  trade-offs rather than relying on accuracy alone.

## Delivery controls

The portfolio version uses synthetic tests only. The client repository and data
remain private. Model scores are treated as decision support and require
privacy, fair-lending, security, and human-review controls.

## Skills demonstrated

MySQL · DataGrip · Python · Pandas · NumPy · Scikit-learn · TensorFlow/Keras ·
ROC-AUC · F1
