# credit-risk-classification

Loan Risk Prediction
This project involves building a machine learning model to predict loan risk. We use a logistic regression model and handle class imbalance in our dataset using oversampling. 

Dependencies
Python
pandas
numpy
sklearn
imbalanced-learn

Data Preprocessing
The data is read from a CSV file into a pandas DataFrame. The data is then split into features (X) and target labels (y). The target labels are what we aim to predict - in this case, whether a loan is high-risk (1) or healthy (0).

Logistic Regression Model
We first fit a logistic regression model on the original data and make predictions on the test data. We then evaluate the model’s performance using metrics such as balanced accuracy score, confusion matrix, and classification report.

Handling Class Imbalance
To handle class imbalance in our dataset, we use the Random Over Sampler from the imbalanced-learn library to oversample the minority class in our training data. We then fit a logistic regression model on the oversampled data and make predictions on the test data. We evaluate the model’s performance using the same metrics as before.