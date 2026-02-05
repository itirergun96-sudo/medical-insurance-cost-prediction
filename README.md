# Medical Insurance Cost Prediction

Machine learning regression project that predicts medical insurance charges.

## Project Goal

To estimate insurance cost based on personal attributes such as age, BMI, smoking status, and region.

## Dataset

The dataset contains demographic and lifestyle information used to predict medical charges.

## Models Used

- Linear Regression
- Random Forest Regressor

Both models were trained and evaluated using standard regression metrics.

## Evaluation Metrics

- RMSE (Root Mean Squared Error)
- R² Score

Random Forest provided better performance compared to Linear Regression.

## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Saved Models

- `insurance_linear_regression.pkl`
- `insurance_random_forest.pkl`

These models can be loaded and reused without retraining.

## How to Run

```bash
pip install -r requirements.txt
