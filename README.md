Kaggle link : https://www.kaggle.com/ozgurozgur/week23


# Class4-Machine_Learning-Week23


## [RAIN IN AUSTRALIA DATA PREPROCESSING](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)

### 1. Missing values analysis
*	Variables with missing values
*	Percentage of missing values for each variable as a dataframe
*	Drop missing values in RainToday and RainTomorrow variables

### 2. Multivariate imputation with (a) selected algorithm(s) and label encoding
*	Tip: May consider to drop some categorical variables with too many categories, if it takes too much time to get a result
*	Tip: Do not forget to encode categorical variables. 
*	Tip: You get error if you have data type such as string or date. The values should be integer or float.

### 3. Outliers
* Apply Z-score method to detect outliers
*	Apply IQR method/boxplot visualization for selected variables to detect outliers
*	Apply Isolation Forest and Local Outlier Factor methods to detect outliers
    *	Tip: Consider standardization based on the algorithm that you use.
*	Decide on a threshold observation to replace outliers
*	Replace the outliers with the threshold observation
