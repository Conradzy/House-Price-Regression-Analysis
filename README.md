# House Price Regression Analysis

Cleans a house-price dataset and compares seven regression algorithms. It reports standard error metrics and interprets the coefficients and equation produced by multiple linear regression.

## Workflow

1. Load `House_Prices.csv` and clean numeric fields and currency symbols.
2. Remove corrupted observations and select predictors and `Price` target.
3. Create training and test sets.
4. Train seven regression algorithms.
5. Compare MAE, MSE, RMSE, and R² and interpret the linear model.

## Data Requirements

- `House_Prices.csv` — property features and sale prices.

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- pandas
- NumPy
- scikit-learn
- Matplotlib

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`housepricingnapinas.ipynb`](housepricingnapinas.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Regression comparison table
- Metric charts
- Linear-regression equation
- Feature coefficient interpretation

## Repository Contents

```text
.
|-- README.md
`-- housepricingnapinas.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
