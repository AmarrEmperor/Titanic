# Titanic Survival Prediction

This project turns the Titanic notebook exploration into a small, reproducible machine learning pipeline.

## Setup

```bash
py -3.12 -m pip install -r requirements.txt
```

## Train the model and generate a submission

```bash
py -3.12 -c "import sys; sys.path.insert(0, r'.'); import main; main.main()"
```

The script reads the training and test CSV files in the `data/` folder, builds a preprocessing + Random Forest pipeline, and writes a `data/submission.csv` file with predictions for Kaggle-style submission.
