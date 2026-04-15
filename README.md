# CKD Staging using Machine Learning

Code and data for the paper:  
**"CKD-StageNet: A Comparative Study of Machine Learning Models for Chronic Kidney Disease Staging with Explainable AI"**

## Results (after mild noise injection)
- **Best model:** Gradient Boosting – F1 = **95.31%**, Accuracy = **95.38%**
- Random Forest: F1 = 95.08%
- XGBoost (tuned): F1 = 94.58%
- Confidence interval (95%): 93.78% – 96.74%

## Noise injected (realistic, mild)
- 1% Gaussian noise on numeric features
- 2% random missing values (MCAR)
- 0.5% GFR outliers
- 0.5% label noise (stage flipping)

## Files
- `CKD-ML-PROJECT.ipynb` – Complete Google Colab notebook (EDA, feature engineering, SMOTE, Optuna, SHAP, stacking)
- `ckd_dataset_with_stages.csv` – Dataset (4000 patients, 23 features, 6 stages)
- `figures/` – All plots (EDA, confusion matrices, ROC curves, SHAP, etc.)

## How to run
1. Open the notebook in Google Colab.
2. Upload the CSV when prompted.
3. Run all cells.

## Key techniques
- SMOTE for class balancing
- Optuna hyperparameter tuning
- SHAP explainability
- Stacking ensemble (fast version)

## Citation
If you use this code, please cite our paper (see paper for details).
