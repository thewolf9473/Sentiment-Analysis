# Sentiment-Analysis
Comparison of Sentiment analysis of IMDB dataset first using machine learning approaches of Logistic regression, XGBoost and linear SVC  and then using LSTM RNN model and then at last using BERT Model. 

# Preprocessing
First removed the duplicate datas from the dataset and then using stopwords removed stopwords(except NOT), and at last applied regex to remove all other punctuation marks etc.
# Machine Learning Approch
 After the preprocessing converted data into vectors and then applied Logistic regression which gave an accuracy of 89.5% and then used XGBoost Classifier which gave accuracy of 81.2% and at last used linear SVC Model which gave accuracy of 89.78% 
 So in ML approch Linear SVC performed the best among these 3
 
# RNN-LSTM
After using ml approch I used LSTM RNN approch with Conv 1d layer. I used embedding dimension as 64. The model gave accuracy of 88.5% for 7 Epochs.

# BERT
At last I used Google's BERT for the Classification which gave me the best accuracy of all the models. It gave me the accuracy of 91%.
