# DataScience1

Course project on dimensionality reduction, OLS regression, and prediction error.

## Project Overview

This project studies how principal component analysis (PCA) affects prediction performance when the underlying data-generating process is dense and many variables may contain useful signal. The notebook compares models that use all original features with models that first reduce the feature space through PCA.

The central tradeoff is bias versus variance: PCA can reduce overfitting when the training sample is small, while OLS can benefit from the full feature set when there is enough training data.

## Research Questions

- When does PCA improve out-of-sample prediction?
- How does training-sample size affect the value of dimensionality reduction?
- How many principal components are useful before extra components stop improving prediction?
- When does OLS using the full feature set outperform PCA-based models?

## Dataset

The analysis uses `PCA_data.csv`, provided with the assignment. The notebook evaluates prediction under different training-data sizes and compares mean squared prediction error across model specifications.

## Notebook Structure

- Importing libraries and assignment data
- Part 1: PCA and prediction with different component counts
- Part 2: OLS comparison and training-size experiments
- Visualization of prediction performance
- MSPE comparison across model sizes
- Interpretation of how sample size changes the best modeling choice

## Methods

The notebook uses PCA to transform the feature space, then evaluates model performance using mean squared prediction error. It compares PCA-based regressions with OLS models that use all available features.

## Key Findings

- PCA is most useful when the training sample is small because it reduces variance and limits overfitting.
- As the training sample grows, the advantage of PCA decreases.
- OLS improves with more data because it can use information from the full feature set.
- The best number of PCA components depends on the amount of training data available.

## Files

- `homework_artyom_ashigov.ipynb` - full notebook with analysis, models, plots, and interpretation.
- `homework_artyom_ashigov.html` - rendered notebook output.
- `PCA_data.csv` - dataset used in the analysis.
- `task.pdf` - assignment instructions.

## Tools

Python, pandas, numpy, scikit-learn, seaborn, matplotlib, and Jupyter Notebook.
