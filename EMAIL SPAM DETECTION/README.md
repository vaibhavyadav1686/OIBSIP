# EMAIL SPAM DETECTION

This was the fourth task in this internship.

## PROBLEM STATEMENT

We’ve all been the recipient of spam emails before. Spam mail, or junk mail, is a type of email
that is sent to a massive number of users at one time, frequently containing cryptic
messages, scams, or most dangerously, phishing content.
In this Project, use Python to build an email spam detector. Then, use machine learning to
train the spam detector to recognize and classify emails into spam and non-spam. Let’s get
started!

## METHODOLOGY

I have used Python libraries numpy and pandas for data manipulation and nltk for string vectorisation.

We check the dataset for any empty data points which may cause discrepancies.
We convert the mails into string tokens and further into vectors.
Then we split this data into training and testing data. 
Since we are using concepts of Natural Language Processing (NLP), a safe apporach is to use the Naive Bayes classifier for building the model.
I have used Multinomial Naive Bayes classifier for this purpose. 


## RESULTS

The training data was predicted with an accuracy of 99.76%
The test data was preicted with an accuracy of 98.69%
