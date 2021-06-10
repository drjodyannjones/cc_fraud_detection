# Credit Card Fraud Detection Model using TensorFlow

The FBI describes credit card fraud as the unauthorized use of a credit or debit card in order to obtain money and/or property. Needless to say, this is a crucial concern for businesses as fraudulent transactions negatively impact the bottomline. In this project, I analyze a data set from Kaggle with a sample size of 284,807 cases in order to detect the likelihood of credit card fraud using a combination of deep learning and machine learning techniques. The dataset has 31 features; the response or target variable is labeled ‘Class’ where 1 represents an incidence of fraud, and 0 represents no incidence. The variables have been anonymized in order to protect personally identifiable information (PII). Also, the original variables have been transformed using principal component analysis (PCA) by the data source’s authors. The only two variables that were not initially transformed were ‘Time’ and ‘Amount’. However, as you will see in the jupyter notebook, I transformed the ‘Amount’ variable in order to account for the differences in magnitude among features. The final model reported an accuracy of 99.8%. For further information about the dataset, please visit https://www.kaggle.com/mlg-ulb/creditcardfraud. If you have any questions or comments about the model, please feel free to reach out to me at jasjones82@gmail.com. Thank you for reading.
