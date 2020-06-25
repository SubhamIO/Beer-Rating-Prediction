# Beer-Rating-Prediction

## Problem Statement
Build a Machine Learning model which predicts the overall rating of the beer. (“review/overall” column in “train.csv” is your dependent variable.)

## Machine Learning Problem Formulation:
__- Formulating this prediction problem as a regression problem.__

## Metric Used : 

- Root Mean Square Error(RMSE) : https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html
- R^2 or Coefficient of Determination : https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html

## Data and Datatypes:
- index                  int64
- beer/ABV             float64
- beer/beerId            int64
- beer/brewerId          int64
- beer/name             object
- beer/style            object
- review/appearance    float64
- review/aroma         float64
- review/overall       float64
- review/palate        float64
- review/taste         float64
- review/text           object
- review/timeStruct     object
- review/timeUnix        int64
- user/ageInSeconds    float64
- user/birthdayRaw      object
- user/birthdayUnix    float64
- user/gender           object
- user/profileName      object

## Approach: 
1. Data Acquisition
2. Data Loading
3. Exploratory Data Analysis and Handling nulls 
4. Data Preprocessing
5. Data Vectorisation
6. Modelling
7. Conclusion
