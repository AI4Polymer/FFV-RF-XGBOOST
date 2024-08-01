1. The ML models were trained to assist in understanding how the substructures of PIMs affect fractional free volume (FFV). 

2. There are two machine learning models, one is Random Forest (RF.ipynb) and the other is XGBoost (XGBOOST.ipynb) for validating the reliability of the results. The inputs are polymer repeating units represented by their SMILES strings, and the outputs are the FFV. 10 folds cross-validation was used to tune the hyperparameters and select the best model. SHAP (SHapley Additive exPlanations) method was used to study how each substructure affects FFV.
