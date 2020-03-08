# Titanic Competition
This is the famous [Kaggle's Titanic ML competition](https://www.kaggle.com/c/titanic), where competitors are asked to build a model able to predict wheter a passanger has survived the Titanic disaster or not using passenger data.

## Data Description
As explained on [Kaggle](https://www.kaggle.com/c/titanic/data), the data has been split into a training and a testing set called 'train.csv' and 'test.csv' respectively.
'train.csv' is meant to be used to train and test our model.
'test.csv' is meant to be used to make our predictions.
 
 The variables are: 
* `Survived` key: 0 = No, 1 = Yes
* `Pclass` is a proxy for socio-economic status (SES), key: 1 = 1st, 2 = 2nd, 3 = 3rd
* `Name` 
* `Sex` is the gender of the passenger	
* `Age` is fractional if less than 1. If the age is estimated, is it in the form of xx.5
* `SibSp` is the # of siblings / spouses aboard the Titanic	
   * Sibling = brother, sister, stepbrother, stepsister
   * Spouse = husband, wife (mistresses and fiancés were ignored)
* `Parch` is the # of parents / children aboard the Titanic	
    * Parent = mother, father
    * Child = daughter, son, stepdaughter, stepson
    * Some children travelled only with a nanny, therefore parch=0 for them.
* `Ticket` is the ticket number	
* `Fare` is the passenger fare	
* `Cabin` is the cabin number
* `Embarked` is the port of embarkation, key:	C = Cherbourg, Q = Queenstown, S = Southampton

## Files Description
- `'The Data'` contains a simple EDA where the feature engineering process is determined;
- `'Titanic Competition'` contains the feature engineering, the hyperparameter tuning, the model selection, the predicion and the blending.
