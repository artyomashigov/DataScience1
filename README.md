# DataScience1

Course project on how PCA dimensionality reduction and OLS regression affect prediction error under different training-data sizes.

## Project Goal

The project studies prediction in a dense data-generating process where many features may matter. It compares ordinary least squares using all variables against models that first reduce dimensionality with principal component analysis.

## Files

- `homework_artyom_ashigov.ipynb` - full notebook with analysis, modeling, and plots.
- `homework_artyom_ashigov.html` - rendered notebook output.
- `PCA_data.csv` - dataset used in the notebook.
- `task.pdf` - assignment instructions.

## Methods

The notebook evaluates model performance with mean squared prediction error (MSPE). It tests models using different numbers of PCA components and compares them with OLS as the available training sample grows.

## Main Questions

- When does PCA help prediction by reducing overfitting?
- How does OLS perform when more training data becomes available?
- How many principal components are useful before extra complexity stops helping?

## Summary

PCA is most useful when the training sample is small because it reduces the effective number of features. As more data becomes available, the advantage of PCA fades and OLS can better use the full feature set.

## Tools

Python, pandas, scikit-learn, statsmodels, and plotting libraries.
