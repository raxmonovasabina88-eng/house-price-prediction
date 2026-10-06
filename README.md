# House Price Prediction using Machine Learning

## Project Overview

This project predicts house sale prices using machine learning techniques. The project is based on the House Prices dataset and uses the `SalePrice` column as the target variable.

## Objective

The main objective of this project is to build a machine learning model that can predict house prices based on different property characteristics.

## Dataset

The dataset contains information about residential properties, including numerical and categorical features.

* Training dataset: `train.csv`
* Testing dataset: `test.csv`
* Target variable: `SalePrice`

## Data Preprocessing

The following preprocessing steps were performed:

* Numerical missing values were filled using the median.
* Categorical missing values were filled using the most frequent value.
* Categorical variables were converted into numerical features using One-Hot Encoding.
* The dataset was divided into training and validation sets.

## Machine Learning Model

The project uses:

**Random Forest Regressor**

Model parameters:

* `n_estimators = 100`
* `random_state = 42`
* Validation split = 20%

## Model Evaluation

The model was evaluated using Mean Absolute Error (MAE) and R² Score.

### Results

* **Mean Absolute Error (MAE): 17,523.68**
* **R² Score: 0.89415**

The R² score of approximately 0.89 indicates that the model explains about 89% of the variation in house prices on the validation dataset.

## Prediction

After training and evaluation, the model was used to predict house prices in the test dataset.

The predictions were saved in:

`submission.csv`

The submission file contains:

* `Id`
* `SalePrice`

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Google Colab
* GitHub
* Random Forest Regression

## Conclusion

The Random Forest Regression model achieved a good validation performance with an R² score of approximately 0.89. The trained model was successfully used to generate house price predictions for the test dataset.
