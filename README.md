# AmazonTextClustering
Everything you need for cluster the AmazonReviewDataset

# **INDEX**

0. Explorative analysis:
    - Nan's removal
    - Columns selection
1. Sentiment polarity and classification: 
    - Polarity: `TextBlob.sentiment.polarity`
    - Labeling [neg/neu/pos]
2. Preprocessing:
    - Tokenizzazione: `nltk.word_tokenize())`
    - Normalization: `str.lower(), x.translate("","",string.puntuaction)`
    - Stop words removal: `nltk.stopwords(en="english")`
    - Stemming: `PorterStemmer()`
    - Lemmatization: `Lemmatizer()`
3. Structural requirements:
    - Identify the classes
    - Create a custom vocabulary for class detection
4. Clustering
    - TFiDF Matrix
    - Cluster using KMeans
    - Cluster using SpectralClustering

