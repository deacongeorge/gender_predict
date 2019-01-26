# Gender prediction
Introduction:
Gender prediction using twitter user profile information.
The objective of this project is to create a machine learning model for predicting the gender of a twitter user based on the
profile information and other data provided. The gender categories are male, female and brands.
While male and female refer to individuals, Brand refers to corporte entities and non individuals.

Business Case
Missing names and gender could be a huge concern when required for identity especially in marketing and demographic purpose,
various methods are employed in gender prediction to meet the needs of customers. Therefore accurate prediction of gender
is of immense value for customers and consumers in targeted marketing. Also robotic technology has made non human tweets and responses
possible hence it important to identify tweets made by individuals and tweets made by non humans.Also completing online documents sometimes
requires identification of humans and non humans.

Business Solution
The question is can a fairly accurate quantitative gender prediction model be developed using tweets to accurately categorise tweets into
male, female and brand for non individuals? This will help to identify human and non human tweets. A system that can automatically
categorises tweets into male, female and brands will enable indentification of non human tweets. This will help in demographics,
targeted marketing and identification of humans and non humans in online document completion.

Technical Solution
A high performance multi class classifier is built to predict the the gender category using tweeter user profile information
to train machine learning and deep learning algorithms. The models are trained and tested using 20050 user profiles and the system
is scalable for higher performance. 

Summary of model building
The data provided was imported, The preprossing of the data was executed in which each column of the dataframe was cleaned to contain
the same data type. Exploratory data analysis with visualisation was done for insight on the data relationship, variation and
distribution, The raw data was transformed to improve the prediction model. Four base supervised machine learning models were created
for pediction using selected data features after scaling. The models were evaluated on a test unseen data. A prediction performance
of 66% accuracy, precision and recall in target prediction was achieved. 
'''
