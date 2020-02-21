# Spam or Ham
This application is an implementation of the age-old classifcation problem: spam or ham. For this project I used the 
[SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) from Kaggle. As far as implementation, 
I used a Naive Bayes Classifier because it is a reliable approach to text classification. The data didn't need a lot of cleaning and 
modification before using it for training and testing. I used pandas to read in the data which was presented as a csv file. I 
visualized the data using pandas built-in visualization tools. Since the data only consisted of a label column and a text column, there
wasn't much to visualize. Next, I built a pipeline using sklearn's pipeline library. The pipeline vectorized the text messages using a 
count vectorizer, transformed the data with term frequency-inverse document frequency, and built a model using a multinomial Naive Bayes
classifier.
