SMS Spam Detection
--------------------------------------------------------------------------------------------------------------------------------------------
This project is a simple tool to identify whether a text message (SMS) is spam or not using a machine learning model.

What It Does
---------------------------------------------------------------------------------------------------------------------------------------------
Spam or Ham: The program can tell if a message is spam (unwanted) or ham (safe).

Accuracy: The model is pretty accurate, with about 96% accuracy on the training data.

How It Works
-------------------------------------------------------------------------------------------------------------------------------------------
Load the Data: We use a dataset of SMS messages labeled as 'ham' (not spam) or 'spam'.

Clean the Data: We clean up the dataset by removing empty values and duplicates, and renaming columns to make them easier to understand.

Train the Model: We train a Logistic Regression model using these messages.

Make Predictions: You can input a new message, and the model will tell you if it's spam or ham.

Requirements
---------------------------------------------------------------------------------------------------------------------------------------------------
To run this project, you need Python and these libraries:

numpy

pandas

scikit-learn


Files
--------------------------------------------------------------------------------------------------------------------------------------------------
spam.csv: The dataset used for training.

sms_spam_detection.py: The main Python script.

README.md: This file.










