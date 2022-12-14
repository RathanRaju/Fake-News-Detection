# Fake News Detection

- Dataset Link - https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?datasetId=572515&sortBy=voteCount

## Outline
  - Introduction 
  - Data Description
  - Understanding our data
  - Text Preprocessing
  - Text Analysis
  - Implementation of GloVe
  - Conclusion
  - References


## Introduction

#### WHAT MAKES FAKE NEWS A PROBLEM?

- The term "fake news" describes misinformation, disinformation, or mal-information that spreads via social media, conventional media, manipulated films, memes, and unconfirmed adverts, among other digital modes of communication.
- The propagation of false information on social media has turned into a significant issue, with the potential to lead to mob violence, suicides, and other tragedies.


## Data Description

- This dataset includes roughly 40.000 items that include both true and fraudulent news. 
- In order for our algorithm to accurately forecast whether a particular piece of news is legitimate or fraudulent, it must be trained. 
- The information on bogus and legitimate news is provided in two distinct databases, each of which contains about 20,000 items.


## Understanding our data

![alt text](https://github.com/RathanRaju/Fake-News-Detection/blob/main/Balanced_Dataset.png "Balanced data")


The data is pretty much balanced.


## Text Preprocessing

Real Text:
![alt text](https://github.com/RathanRaju/Fake-News-Detection/blob/main/Real%20Text.png "Real Text")


Fake Text:
![alt text](https://github.com/RathanRaju/Fake-News-Detection/blob/main/Fake%20Text.png "Fake Text")



## Text Analysis

#### Unigram Analysis

#### Bigram Analysis

#### Trigram Analysis


## Implementation of GloVe

GloVe is a Global Vectors for word embedding and it is a method built on an important idea, You can derive semantic relationships between words from the co-occurrence matrix. Given a corpus having V words, the co-occurrence matrix X will be a V x V matrix, where the i th row and j th column of X, X_ij denotes how many times word i has co-occurred with word j. An example co-occurrence matrix might look as follows.

Example:
![alt text](https://github.com/RathanRaju/Fake-News-Detection/blob/main/Example.png "Example")


The co-occurrence matrix for the sentence ???the cat sat on the mat??? with a window size of 1. As you probably noticed it is a symmetric matrix. How do we get a metric that measures semantic similarity between words from this? For that, you will need three words at a time. Let me concretely lay down this statement.


## Conclusion

The model acheived an accuracy of 98.28% on the test data. 

Accuracy:
![alt text](https://github.com/RathanRaju/Fake-News-Detection/blob/main/Accuracy%20.png "Accuracy")



## References
- https://www.kaggle.com/datasets/bertcarremans/glovetwitter27b100dtxt
- https://nlp.stanford.edu/projects/glove/
- https://towardsdatascience.com/light-on-math-ml-intuitive-guide-to-understanding-glove-embeddings-b13b4f19c010


