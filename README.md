# Training

Machine learning exercises built with scikit-learn, NumPy, pandas, and Matplotlib, organized as Jupyter notebooks under `ex00`–`ex06`.

## Structure

- `ex00/` — environment setup and dependency checks
- `ex01/` — regression metrics (MSE)
- `ex02/` — classification metrics (accuracy)
- `ex03/` — linear regression on California housing
- `ex04/` — logistic regression on breast cancer (ROC curve)
- `ex05/` — comparing regression pipelines (linear, SVM, tree, ensemble)
- `ex06/` — RandomForestRegressor hyperparameter tuning with GridSearchCV

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r ex00/requirements.txt
jupyter notebook
```

## Requirements

See `ex00/requirements.txt`.
