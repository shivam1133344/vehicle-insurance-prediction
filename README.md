# Vehicle Insurance Cross-Sell Prediction


Predict whether a customer will respond to cross-sell of vehicle-insurance.


## Problem Statement
Insurance companies want to predict the likelihood that a customer will purchase vehicle-insurance so they can allocate marketing resources efficiently.


## Dataset
Brief: customer demographic and vehicle information. Target column: `Response` (0/1).


## What I did
- EDA & data cleaning
- Label encoding and scaling
- Class balancing using SMOTE
- Trained models: Logistic Regression, Random Forest, XGBoost
- Evaluated using precision/recall/F1 and ROC-AUC


## Results
Best model: **XGBoost** (ROC-AUC: 0.84, F1: 0.91) 


 ## How to run
1. Create virtualenv: `python -m venv venv` and activate it.
2. Install: `pip install -r requirements.txt`.
3. Run notebook: `jupyter notebook notebooks/project.ipynb` or run training script: `python src/train.py`.


## Notes
- For reproducibility, set `random_state=42`.
- Do not upload the raw data if it is proprietary—use a sample or instructions to download.


## License
MIT License 

