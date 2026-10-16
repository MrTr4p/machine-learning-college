# Task 1: Medical Insurance Charges Prediction

[Open the notebook](task1.ipynb).

Predict medical insurance charges using age, sex, BMI, number of children,
smoking status, and region.

## Dataset

The notebook downloads the
[Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
through KaggleHub. The CSV contains 1,338 rows; the notebook removes one exact
duplicate before training.

## Approach

1. Inspect the data for missing values and duplicates.
2. Encode sex and smoking status, and one-hot encode region.
3. Add a BMI–smoking interaction feature.
4. Use an 80/20 train/test split with `random_state=42`.
5. Fit a scikit-learn linear regression model.
6. Evaluate predictions with mean squared error and R².

Follow the [shared setup instructions](../README.md#setup), then run the notebook
cells in order from a fresh kernel.
