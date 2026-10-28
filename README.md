# Model-comparison-performance-comparison.

AI & ML Internship Task 2 at Maincrafts Technology.
Compared three regression models on the California Housing dataset
using feature scaling and performance metrics.

## Results

| Model | RMSE | R2 Score |
|---|---|---|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7456 | 0.5758 |
| Decision Tree (max_depth=5) | 0.7242 | 0.5997 |

**Best model: Decision Tree** (lowest RMSE, highest R2)

## Key learnings
- Scaling after the split avoids data leakage
- Linear and Ridge performed almost the same on this data
- The Decision Tree captured non-linear patterns better
- R2 of about 0.60 shows there is room to improve

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib

## Files
- AI_ML_Task2_Model_Comparison.ipynb: full code and outputs
#Maincrafts technology

## Future improvements
Cross-validation, hyperparameter tuning, Random Forest / Gradient Boosting
