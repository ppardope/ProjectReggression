# ProjectReggression
This project implements multiple linear regression analyses and variable selection procedures to model and address multicollinearity in the dataset `LINTHALL.txt` (14 predictors). The code:
  - Fits an OLS regression model to estimate the regression coefficients, their standard errors, and the sum of squared errors (SSE).
  - Runs collinearity diagnostics using:
    - Variance Inflation Factors (VIF)
    - Condition number of the design matrix
    - Eigenvalue decomposition of \(X^TX\)
  - Uses PCR to reduce multicollinearit.
  - Transforms the PCR results back to the original predictor space.
  - Compares the sum of standard errors and SSE of the PCR model with the full OLS model.

## Files Included

- **`untitled3.py`**: Main Python script containing the analysis code.
- **`LINTHALL.txt`**: Dataset with 14 predictors.
- **`LINTH-5.txt`**: Reduced dataset with 5 predictors.

