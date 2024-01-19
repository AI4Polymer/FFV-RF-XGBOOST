1. The ML models were trained to assist in understanding how the substructures of PIMs affect FFV using the SHAP (SHapley Additive exPlanations) method. 

2. There are two machine learning models, one is Random Forest (RF.ipynb) and the other is XGBoost (XGBOOST.ipynb) for validating the reliability of the results. The inputs are polymer repeating units represented by their SMILES strings, and the outputs are the fractional free volume (FFV). 10 folds cross-validation was used to tune the hyperparameters and select the best model. 

3. The predicted FFV of PIMs in this work can be found in "PIM_Pred_FFV.pdf".
