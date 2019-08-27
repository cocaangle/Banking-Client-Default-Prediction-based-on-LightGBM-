# Banking-Client-Default-Prediction-based-on-LightGBM-

The datasets consist of two parts, one is for client's general information; the other is the clients' credit information.

In the Jupyter Notebook, I use Py_mongo to extract data from MongoDB into Python and convert them into pandas dataframe; Then conducted data cleaning such as changing data type, deleting outliers, generating new metrics etc. and performed one-hot encoding for categorical variables and merge two datasets. Last , I used stratified k-fold cross validation method to fit LightGBM model, and identified most important factors in default prediction based on feature importance function
