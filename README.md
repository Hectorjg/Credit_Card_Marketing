# Project: Credit Card Marketing

The objective of this project is to find the best prediction model on a classification data. 
The target is the Offer_accepted column.
Here are 2 models, a linnera Regression model and a KN - neighbors model.
The dataset used for this project can be found on [GitHub-Ironhack](https://github.com/ironhack-edu/data_mid_bootcamp_project_classification)

## Objectives
  - Create a Logistic Regression model to predict the customers who will accept the offer.
  - Create a KN-neighbors model to predict the customers who will accept the offer.
  - Visualize the dataframes to understand the most important data.
  - Select the model with the highest accuracy score.

## Project Steps:

### Data Cleaning
  - Drop the customer number column.
  - Change the data types of the columns wich I consider.
  - Check for null values and drop them.
  - Plot the numerical column and remove outliers.
  - Transform the numerical data in order to make it like a standart deviation.
  - Plot the categorical columns and bucket the ones wich have a few values.
  
### Data Analysis
  - Selecting the columns that looks to be the most correlated to the target.
  - Up sampling the data in order to balance it
### Processing Data
  - Scaling the numerical data.
  - Use OneHotEncoder for the categorical data, excluding the target.
  
### Logistic Regresion Model
  - Create the logistic regression model to predict the Offer accepted.
  - Plot a confusion matrix to visualize the prediction.
  
### KN-neighbors
  -Find the best "k value" for the model.
  -Create a KN-neighbors model to predict the Offer accepted.
  -Plot a confusion matrix to visualize the prediction.
### Evaluate Accuracy
  - score and ROC AUC;
  
## Conclussion:

  -The best model for this case is the Logistic Regression model
   because it had a better accuracy.
   
-----------------
link to tableu https://public.tableau.com/app/profile/h.ctor.mondragon.reyes/viz/credit_card_marketing/Dashboard1?publish=yes

----------------
The files required for the project are in the data_files file:
  - original_dataframe.csv
  - clean_data.csv
  - up_sampling_data.csv
  - scaled_numerical_data.csv
  - encoded_categorical_data.csv
  - concatinated_final_data.csv