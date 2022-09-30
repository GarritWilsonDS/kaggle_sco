# Sales Conversion Optimization

### Aim

The Notebook presented here is part of a side - project, attempting to use Machine Learning to predict nr. of Conversions
of Facebook Ads.

### The Data

The dataset was pulled from kaggle and can be found via the following link:

https://www.kaggle.com/datasets/loveall/clicks-conversion-tracking?resource=download

### Outcome

The Machine Learning models for regression (predicting number of conversions based on Impressions, Clicks, and Ad Spent),
as well as for classification (predicting whether any conversion would happen at all based on the same features)
did not prove successful. The reason for this is assumed to be related to insufficiently predictive features within the data.

As a solution (and to improve prediction accuracy) it would be suggested to consult with a domain level expert,
who understands which features would influence nr. of conversions, and therefore hold predictive validity.
This data would then subsequently have to be obtained and the analysis re-run.

The project overall fulfilled its aim however, by being a great opportunity to practice the following skills involved in 
the ML - workflow:

1. Data Cleaning
- removing outliers
- inspecting Missing Values and Duplicates

2. Exploratory Data Analysis

3. Feature Engineering

4. Data Preprocessing
- Feature Encoding of categorical features
- Feature Scaling of quantitative features

4. Modeling
- selecting the best - performant algorithm based on k-fold cross validation results
- hyperparameter tuning using GridSearchCV
- assessing feature importance by using feature permutation
- modeling both a regression algorithm as well as a classification algorithm (after binning the target variable)