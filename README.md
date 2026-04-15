# CKD Staging using Machine Learning

Code and data for the paper:  
**"CKD-StageNet: A Comparative Study of Machine Learning Models for Chronic Kidney Disease Staging"**

## Files
- `CKD-ML-PROJECT.ipynb` – Complete Google Colab notebook (EDA, feature engineering, SMOTE, Optuna, SHAP, stacking)
- `ckd_dataset_with_stages.csv` – Dataset (4000 patients, 23 features, 6 stages)

## How to run
1. Upload the notebook to Google Colab.
2. Upload the CSV when prompted.
3. Run all cells.

## Results
- Best model: XGBoost (tuned) – F1 = 88.22%, AUC = 0.9778

## Citation
If you use this code, please cite our paper (see paper for details).
