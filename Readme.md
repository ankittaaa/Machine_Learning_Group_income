The given model is built as a part of Machine Learning module for TCD kaggle ML competition. The provided data set had a list of people and their various related information like hair color, height, country and a number of other features. I used Cat Boost Algorithm to predict the yearly salaries of all people. The libraries used in building this model are numpy, pandas and sklearn. The steps followed in this project are as follows -

Loading the given data
Preprocessing : Null values were removed and replaced by mode, Handled missing data, Dropping the 'Instance' column.
Perform Label Encoding on all the categorical columns.
Create the Cat Boost Regressor model.
Fitting the model to training set.
Formulating predictions using test data.
Computing Mean Average Error(MAE).
