# Timeseries-Forecasting-with-Facebook-Prophet-Model

**`Project Description`**

This project aims to develop a highly accurate model for predicting hourly energy consumption based on historical data from the PJM Interconnection LLC Energy Consumption dataset. PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia. The hourly power consumption data comes from PJM's website and are in megawatts (MW). 

We will employ, Prophet Model  designed for automatic forecasting of univariate time series. It was developed by Meta as an algorithm for the in-house prediction of time series values for different business applications. 
Hence, it is specifically develped for timeseries forecasting of business operation. It is particularly useful for handling data with daily observations that contain seasonality, holiday effects, and trend components which makes it suitable for our case. The model is flexible and can accommodate missing data points and outliers, however will do dataprocessing to handle those issues. 

**`Mian Project Tasks`**

**`I. Data Loading, Cleaning and Preprocessing`**

- Load the dataset from Kaggle using the Kaggle API, importing it into the working directory.
- Develop an overview of the dataset, detailing data types, structure, and summary statistics to identify errors, inconsistencies, and patterns, missing data or duplicates
- Handle missing values and duplicates within the dataset, if any.
- Ensure data schema consistency by addressing irregularities in data entries.
- Inspect and treat any outliers in the data.

**`II. Explanotary Data Analysis and Feature Engineering`**

Since we are dealing with Time series data with date time and corrosponding values feature only, We will create new relavent predictor features and we will carry out EDA using those features.

**`III. Formating the Dataset for Prophet Model Using`**

**`IV. Baseline(with Default Parameter) Evaluation`** 

**` V. Hyperparameter Tuning with Bayesion Optimization`**

**`VI. Prediction with best Performing Model`**