# Sentiment-Analysis-using-NLP
Sentiment Analysis is the process of determining whether a piece of writing is positive, negative or neutral.Perform Sentiment Analysis on IMDB Movie Reviews using Unigram and Bigram setting, compared model performances with and without stemming and lemmatizing methods.

## Data
The labeled training data set consists of 25,000 IMDB movie reviews. There is also an unlabeled test set with 25,000 IMDB movie reviews. The sentiment of the reviews are binary, meaning an IMDB rating < 5 results in a sentiment score of 0, and a rating >=7 have a sentiment score of 1.

##### Dataset
Dataset from kaggle : [here](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) 

## What is NLP
NLP stands for Natural Language Processing. It is the field of study that focuses on the interactions between human language and computers. It is an amalgamation of computer science, artificial intelligence, and computational linguistics.
NLP is a sub-field of Artificial Intelligence that is focused on enabling computers to understand and process human languages, to get computers closer to a human-level understanding of language.

## Major Applications of NLP
* Machine Translation
* Speech Recognition
* Spell Checking
* Language Generation
* ChatBots
* Sentiment Analysis

## Tokenization
Tokenization is the process of tokenizing or splitting a string, text into a list of tokens. A Token can be thought of as a useful unit for Semantic Processing.

## Token Normalization
### 1.Stemming

A process of removing and replacing suffixes to get to the root form of the word which is called the stem. Usually refers to the heuristics that chop off suffixes.


### 2.Lemmatization

Usually refers to doing things properly with the use of vocabulary and morphological analysis. It returns the base or dictionary form of a word, which is called a Lemma

## TF_IDF Vectorizer
### Term Frequency
The number of times a word appears in a document divded by the total number of words in the document. Every document has its own term frequency.

### Inverse Document Frequency
The log of the number of documents divided by the number of documents that contain the word w. Inverse data frequency determines the weight of rare words across all documents in the corpus.


