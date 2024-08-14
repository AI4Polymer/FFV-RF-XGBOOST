1. The ML models were trained to assist in understanding how the substructures of PIMs affect fractional free volumes (FFVs) using the SHAP (SHapley Additive exPlanations) method. 

2. Training of machine learning models (Expected run times ＜ 10 min)

There are two machine learning models, one is Random Forest (RF.ipynb) and the other is XGBoost (XGBOOST.ipynb) for validating the reliability of the results. The inputs are polymer repeating units represented by their SMILES strings (FFV.xlsx), and the outputs are the fractional free volume (FFV). 10 folds cross-validation was used to tune the hyperparameters and select the best model. SHAP method was used to provide interpretability of how the substructures of PIMs affect FFVs (SHAP_RF.png and SHAP_XGBoost.png). 

3. Software download and installation (Expected times ＜ 60 min)

python == 3.10

pandas == 2.0.3

numpy == 1.24.3

rdkit == 2022.09.5

scikit-learn == 1.3.0

shap == 0.42.1

matplotlib == 3.7.2

Note: The computer used in this protocol was a MacBook Pro 2020 with the following hardware: Apple M1 8-Core CPU, 16 GB memory. A Lenovo Legion Y9000P was also available: i9-13900 CPU, 16 GB memory. This specification is recommended but optional. The download and installation times may vary based on specific computing resources.
