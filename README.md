# Random Forest Regression - Car Price Prediction

### Day 10 / 21 of ML with Code warriors

Mini project on predicting car price using Random Forest regression.

*Random Forest Regression is a collection of decision tree models . It is an example of ensemble learning that is it is a model that makes prediction based on
a different number of models. Each indiviual model are trained in a parallel way (Bagging).

*Given a car data set , The csv data is loaded and data preprocessing is done. The selected number of features(year,km_driven,fuel,transmission) is stored in an array X and the target variable (Selling price) is stored in an array y.

*The scikit learn will not accept the categorical values , so those categorical values from column fuel and transimmion is converted into dummy varaible using the LabelEncoder .
module from Scikit learn and this process is called as one hot encoding method.

*The data's are splitted as train and test set.

*GridSearchCV module is imported from sklearn.model_processing for hyperparameter tuning to select the best n_estimators in Random forest regressor.

*n_estimators gives the number of decision trees in a model

*Finally the model is trained/fitted.

*Accuracy of the model is calculated . The model gives around 75.5% accuracy.

*New record is passed to test how model works on unseen data.
