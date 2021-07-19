# Gender prediction
# Introduction:
Gender prediction using twitter user profile information.
The objective of this project is to create a machine learning model for predicting the gender of a twitter user based on the
profile and tweet text information and other data provided. The gender categories are male, female and brands.
While male and female refer to individuals, Brand refers to corporate entities and non individuals.

# Business Case:
Missing names and gender could be a huge concern when required for identity especially in marketing and demographic purposes.
Therefore accurate prediction of gender is of immense value for customer and consumer classification in targeted marketing.
Robotic technology has made non human tweets and responses possible hence it important to identify tweets made by individuals and tweets made by non humans. Also completing online documents and login sometimes requires identification of humans and non humans.

# Technical Solution:
A high performance multi class classifier was built to predict the the gender category using tweeter user profile information.
The predictor was trained using machine learning and deep learning algorithms. The models were trained and tested using 20050 twitter user profiles and information extracted. The solution is scalable for higher performance. 

# Summary of model building:
The data was imported using pandas library in python.
The preprocesssing of the data was executed in which each column of the dataframe was cleaned to contain the same data type. 
Exploratory data analysis with visualisation was done for insight on the data relationship, variation and
distribution.
Data transformation and engineering was done to extract features and improve the prediction model.
Four supervised machine learning models were created for pediction using selected data features after scaling.
The models were evaluated on a test unseen data.
A prediction performance of 66% accuracy, precision and recall in target prediction was achieved on initial model.
A deep learning model will include pictures to improve the model prediction performance.
'''
