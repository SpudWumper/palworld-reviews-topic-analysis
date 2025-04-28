# This is one of the projects from my AI class.

## Goal: Label reviews with a topic

## Methods:
### Preprocess text (NLP) - prepare text for topic modeling
 - Spell check and English check
 - Remove things like: stop words, punctuation
 - Lemmatization
 - Tokenize text
 - Libraries: textblob, langdetect, nltk
### Topic modeling (LDA) - creating labels for neural network
 - Perform LDA on processed reviews to create topics
 - Label our training data
 - Libraries: gensim
### Neural Network - train a model to correctly label reviews
 - Things to consider: structure of network, concern of overfitting, optimizer, other hyperparameters
 - Evaluate network with testing set
 - Libraries: PyTorch

### See pdf for specifics and analysis
