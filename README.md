# DataScience1

In this project, we discuss how reducing dimensions with Principal Component Analysis (PCA) and using Ordinary Least Squares (OLS) regression affect predicting outcomes. We look at a specific situation where every feature could matter in making predictions because they all have an impact (this is called a 'dense' Data Generating Process). We're interested in seeing how the performance of various models changes when we adjust the amount of training data. By looking at the Mean Squared Prediction Error (MSPE) for models that use different numbers of PCA components versus using all features with OLS, we get insights into how training data size influences how well we can predict outcomes.

Our findings show that PCA is really helpful for avoiding overfitting when we don't have a lot of data, thanks to its ability to make the feature set simpler. However, as we get more data, this benefit starts to fade. The OLS model, on the other hand, gets better at making predictions as the amount of data increases because it can use all the detailed information available. 

- :bar_chart: [The data](https://raw.githubusercontent.com/artyomashigov/DataScience1/main/PCA_data.csv)
- :orange_book: [Jupyter notebook](https://github.com/artyomashigov/DataScience1/blob/main/homework_artyom_ashigov.ipynb)
- :white_check_mark: [Tasks](https://github.com/artyomashigov/DataScience1/blob/main/homework_artyom_ashigov.ipynb)

Email: artyomashigov@gmail.com