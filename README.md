# Sentiment-Analysis

Title: Sentiment Analysis on IMDB movie review dataset using NLP and Machine Learning approaches

Dataset:

The IMDB movie review dataset is downloaded from Kaggle website. It contains total 50,000 reviews including 25,000 positive reviews and 25,000 negative reviews. Hence, the dataset is completely balanced. It contains 2 columns: review and sentiment where sentiment is the target column that we need to predict.

NLP Approaches:

In this project, we take one review as example to understand the need of cleaning the text. The following text cleaning techniques are used:

1. Removal of HTML contents.

2. Removal of special characters (\) and punctuations.

3. Removal of stopwords. 

4. Implementing stemming and lemmatization to convert the various forms of word to a single form.

    In this project, we have checked both stemming and lemmatization. But the good result is obtained using lemmatization (for example: 'little' has become 'littl' 
    using stemming but remained 'little' using lemmatization) hence lemmatization technique is used further.

5. Vectorization Techniques to encode the numeric values.

   Following vectorization techniques are tried in our project:

   CountVectorizer (Bag of Words Model)
   TfidfVectorizer (Bag of Words Model)
   Keras Tokenizer (Embedding)


6. Fit the data to the ML model

Model Implementation:

- Linear SVC

The linear SVC model is implemented and it gives 90.28% accuracy with TfidfVectorizer. 

- RNN with LSTM



