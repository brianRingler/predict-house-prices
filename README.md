***
# About Project
***
This project will start by focusing on **19 features** from a total of 81 that we think will be the best for **predicting** home value. We will explore these 19 features through a structured EDA process. 

***
# About Dataset
***
The dataset to be reviewed was downloaded from `Kaggle` and is part of their data competition.  In this competition the objective is to use advanced regression techniques to predict housing prices.  Kaggle provides two sets of data: One for training and one for testing the model.  More details about the competition and data set can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).


***
# Notebooks
***
1. **predicting_house_prices_explor_v01.00.ipynb**: Initial notebook for EDA process. Need to update the code to include test file for final model testing.
2. **predicting_house_prices_model_v01.00.ipynb**: In this notebook we begin encoding, scaling and modeling the data tp predict the `SalePrice`.  Models used:
      1. Decision Tree and one tuning pass
      2. Logistic Regression 
      3. more models to come
3. Final notebook will be with testing data and final model selected. The final file will be built for model deployment as part of the `RingVision Home Pricing Application`.

***
# EDA Main Findings
***
The total square footage and sale price have the strongest correlation which will be best for predicting price. Home quality and condition ratings are also strong indicators.  Then there is lot area and neighborhood which provide the most value when combined. In particular neighborhood provides the most value for predicting home prices when combined with other features. These are the best features for training the model and feature engineering.  
1. Sale Price
2. Lot Area
3. Neighborhood
4. Total Home Square Footage
5. Overall Home Quality 
6. Overall Home Condition  

