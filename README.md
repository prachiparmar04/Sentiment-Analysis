### Sentiment Analysis on Twitter Tweets
  - This project focuses on sentiment analysis of Twitter tweets using multiple approaches for text embedding and classification. We explore the following methods:

    CountVectorizer Embeddings
    Sentence Transformers
    GloVe Embeddings
    Project Structure

    Sentiment_Analysis_Twitter.ipynb: The main Jupyter Notebook containing the code and analysis for the sentiment analysis task.

    data/: Directory containing the dataset of tweets.

    models/: Directory where trained models are saved.

    results/: Directory where the results of the analysis, such as evaluation metrics and plots, are stored.
  
  - Dependencies
    To run the notebook, you will need the following libraries:

    numpy
    pandas
    scikit-learn
    transformers
    torch
    sentence-transformers
    matplotlib
    seaborn

- Approaches
  1. CountVectorizer Embeddings
  We use CountVectorizer from scikit-learn to convert the text data into numerical feature vectors. This method creates a sparse matrix of token counts.
  
  2. Sentence Transformers
  We use pre-trained sentence transformers from the sentence-transformers library to convert the text data into dense vector representations. This method leverages pre-trained models like BERT to capture semantic information.
  
  3. GloVe Embeddings
  We use pre-trained GloVe embeddings to convert the text data into dense vector representations. GloVe embeddings are based on word co-occurrence statistics and provide a fixed-size dense vector for each word.



