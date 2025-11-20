**Drug-Induced Autoimmune Disease (AD) Prediction Using Machine Learning**

This project presents a machine-learning–based workflow to predict whether a drug compound has the potential to induce autoimmune diseases (ADs) based on structural alerts, molecular descriptors, and chemical features.
The goal is to support toxicological prescreening during early drug development.

🚀**Project Overview**

Autoimmune toxicity is an important safety concern in drug discovery. This project aims to:

✅ Develop a predictive ML model for drug-induced autoimmune diseases
✅ Analyze structural alerts (especially reactive metabolite–related)
✅ Identify high-risk chemical patterns
✅ Improve prediction accuracy beyond existing models (target ~92%)

The project is based on a dataset containing:

407 FDA-approved drugs

171 reactive metabolite (RM)–related structural alerts

Molecular descriptors (e.g., BalabanJ, Chi indices)

Chemical fragments and substructures

Daily dose information

Binary label →

1 = drug associated with autoimmune disease

0 = drug not associated

🧠**Background**

Drug-induced autoimmune responses can occur due to reactive metabolites (RMs) generated during metabolism.
Certain structural alerts—especially nitrogen-containing aromatic substituents—are known to correlate with autoimmunity risk.

Prior research achieved:

AUC ~ 70%

Identified specific RM-related alerts significantly associated with ADs

This project aims to improve this prediction accuracy using advanced ML techniques such as:

LightGBM

XGBoost

Random Forest

Feature selection


🧬 **Key Findings**

Nitrogen-containing benzene substituent alerts show strong association with autoimmune risks.

Structural alerts related to reactive metabolites rank highly.

Feature-selected LightGBM/XGBoost provides the best performance.

Model interpretation using SHAP reveals mechanistic relationships between structure and AD risk.

🛠️ **Technologies Used**

Python

Google Colab

Pandas, NumPy

Scikit-learn

LightGBM / XGBoost / CatBoost

RDKit (optional for SMILES encoding)

SHAP

