# **House Prices (AmesHousingData): Advanced Regression Techniques**


Link to Kaggle Competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

**Brief about the dataset:**

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. (http://jse.amstat.org/v19n3/decock.pdf)

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

**Goal**: To predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.

**Data Manipulation & Feature Engineering**:

With multiple categorical & numerical variables to play around, the dataset poses a great challenge in terms of data manipulation and feature engineering. Dealing each feature individually to address it in a right way is the key to this competition. (More details in the notebook: DataCleaning & Feature Engineering.ipynb)

**Evaluation Metric**:

Log-RMSE: Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally)

**Modelling**:

I've tried out various models and digged deep into most of them to further tune the hyper-parameters and optimise them to maximise the performance of the model. (Detailed more in the notebook: RegressionModels.ipynb)
