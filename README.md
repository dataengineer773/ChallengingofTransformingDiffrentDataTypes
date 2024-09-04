It is important to prepare data prior to modeling .This may involve replacing missing values scaling numerical values and one hot encoding categorical data, Data transforms can be performed using the scihit-learn library
 For example the SimpleImputer can be used missing values, The MinMaxScaler class can be used to scale numerical values and the OneHotEncoder can be used to encode categorical variables.
 Traditionally , this would require you to seperate the numerical and categorical data and then manually apply the transform on those groups of features before combining the columns back together in order to fit
 and evaluate a model
