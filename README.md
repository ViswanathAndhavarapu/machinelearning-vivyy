This dataset is taken from www.kaggle.com
Description about attributes is given in Data Dictionary file attatched here.
Steps involved in this projects are:
              Data Preprocessing:
                  importing the required libraries
                  importing the dataset
                  to visualise the 1st 5 rows of dataset
                  to find the info of the datase
                  to find all the statistical details of the dataset
                  to show all the columns of the dataset
                  plot that gives various plots against each other(plot between every two variables)
                  plot that gives the correlation among the dataset
                  here we reomve some categorical data variables to improve the performance of the  model also these doesn't effect the models improvement
                  dividing the dataset into independent and dependent(to be predicted) variables/vectorstake fuel type,aspiration,engine type cylindernumber are taken as rest                       donot contribute to the model
                  label encoding the categorical data(fuel)
                  encoding the categorical data(here only x),0,7,8,1 columns as  categorical variable here we cannot encode using LabelEncoding
             Splitting the data into training and test sets:
                  splitting the dataset into training and test sets
             Train the model using multiple linear Regression:
                  training the model using multiple linear regression
                  since we cannot visualise the results directly we concatenate the two vectors for easy identification
              Visualise both test set and predicted results:(in same plot)
                  visualise the results(test set and predicted results)
              Check the accuracy using r2_score:
                  check the accuracy score or rate
                  
              
  In this project we predict the price of Cars using ,ultiple Linear regression also other Ml models like SVR,RFR,DTR can also be tried to find the best or accurate results.
  Overfitting and underfitting may harm the data.Also as other categorical data contribute very less or not at all those were  ignored or deleted. 
  
  
  
  ThankYou
