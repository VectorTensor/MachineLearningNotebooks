# Machine Learning Models
These are the various notebook of the training code used to train the model the model. 
## Emotion Classification
There are two emotion classifier :

[NLP](https://github.com/VectorTensor/MachineLearningNotebooks/blob/main/NLP.ipynb)
which is made by fine tuning distilbert 

[Transformers](https://github.com/VectorTensor/MachineLearningNotebooks/blob/main/Transformers.ipynb)
which is made by feature extraction of distilbert

The first one performed better so it was deployed.
## Wine classifier
There are two wine classifier one using [SVM](https://github.com/VectorTensor/MachineLearningNotebooks/blob/main/SVM.ipynb) and another using [Logistic Regression](https://github.com/VectorTensor/MachineLearningNotebooks/blob/main/wine.ipynb). In the logistic regression I also performed PCA to reduce the dimensions of features.
The Logistic regression one is deployed.

## Sentiment analysis
There a single sentiment classifier that classifies positive and negative sentiment [RNN](https://github.com/VectorTensor/MachineLearningNotebooks/blob/main/RNN.ipynb). It is a simple model of GRU. IMDB dataset was used for training. It is currently not deployed.
