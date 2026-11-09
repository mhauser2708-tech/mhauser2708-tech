<p align="center">
  <img src="assets/banner.svg" alt="Maximilian Hauser, MSc Data Science" width="100%">
</p>

### Hi, I'm Maximilian 👋

I'm a Master's student in Data Science at the University of Southern Denmark (SDU), originally from Austria. My projects cover supervised and unsupervised machine learning, statistical modelling and causal inference, with a focus on evaluating models carefully: cross-validation, confidence intervals, diagnostics and checking the data before trusting the results.

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-4f8cff?style=flat-square&logo=python&logoColor=white">
  <img alt="R" src="https://img.shields.io/badge/R-7c5cff?style=flat-square&logo=r&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-8b98b8?style=flat-square&logo=scikitlearn&logoColor=white">
  <img alt="XGBoost" src="https://img.shields.io/badge/XGBoost-8b98b8?style=flat-square">
  <img alt="pandas" src="https://img.shields.io/badge/pandas-8b98b8?style=flat-square&logo=pandas&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-8b98b8?style=flat-square&logo=jupyter&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-8b98b8?style=flat-square&logo=git&logoColor=white">
</p>

## Projects

Each repository has a README with the results at a glance and an architecture diagram, a `documentation.md` with the full methodology and limitations, and scripts that reproduce the results.

| Project | What it does | Stack |
|---|---|---|
| [fraud-detection](https://github.com/mhauser2708-tech/fraud-detection) | Unsupervised anomaly detection on bank transactions without labels: Isolation Forest, LOF and K-Means compared with a leakage-free pipeline and injected anomalies | Python |
| [diabetes_classifier](https://github.com/mhauser2708-tech/diabetes_classifier) | Binary diabetes classification on CDC health indicators, seven tuned model families compared with cross-validation (Kaggle challenge) | Python, scikit-learn, XGBoost |
| [rhc-causal-analysis](https://github.com/mhauser2708-tech/rhc-causal-analysis) | Causal effect of right heart catheterization on mortality: OLS, IPW, AIPW with double ML and causal forest CATEs | R, grf, DoubleML |
| [a3-clustering-analysis](https://github.com/mhauser2708-tech/a3-clustering-analysis) | K-Means, GMM and hierarchical clustering compared with TD², silhouette and BIC/AIC against a GA-VQ reference | Python, scikit-learn |
| [wine-quality-classification](https://github.com/mhauser2708-tech/wine-quality-classification) | Multiclass wine quality prediction with KNN, SVM, decision tree and random forest, including confidence intervals and a duplicate-leakage check | Python, scikit-learn |
| [body-fat-estimation](https://github.com/mhauser2708-tech/body-fat-estimation) | Interpretable body fat formula from three tape measurements: exhaustive model search, diagnostics, cross-validation and prediction intervals | R |

## What the projects cover

- **Supervised learning:** classification with model tuning, baselines, class imbalance and honest evaluation
- **Unsupervised learning:** clustering, model selection and anomaly detection
- **Causal inference:** propensity scores, doubly robust estimation and heterogeneous treatment effects
- **Statistical modelling:** linear models, model selection, regression diagnostics and prediction intervals
