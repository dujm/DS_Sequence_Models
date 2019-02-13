---
title: Word Embeddings
---


####  [Sequence Models](https://dujm.github.io/DS_Sequence_Models/sequence-models)&nbsp;  | &nbsp;    [Word Embeddings](https://dujm.github.io/DS_Sequence_Models/word-embeddings) &nbsp;  | &nbsp;  [Attention Model](https://dujm.github.io/DS_Sequence_Models/attention-model) &nbsp;  | &nbsp;  [More about Data Science](https://dujm.github.io/pages/datascience.html)


### 1. What are word representations?
  * One-Hot encodings
  * Featurized representaion: word embeddings  
    * Word embedding is one of the most popular word representation.
    * It is capable of capturing context of a word in a document, semantic and syntactic similarity, relation with other words, etc.


### 2. Summary of word embeddings
|   | Word Embeddings   |  
|---|---|
| Transfer Learning |  yes    |
| Training Set |  small  |  
|Entity recognition, text summarization, co-reference resolution, parsing   |Good  |   
| Language modeling and machine translation    | Bad |   
| Visulization   | t-SNE|    |


### 3. How does word embedding algorithms work?
  * How to use word embeddings to solve a **Word Analogy** problem?

  * How to load pre-trained word vectors, and **Measure Similarity** using cosine similarity

  * How to modify word embeddings to **reduce their gender bias**

  * Try the exercise on Coursera [Coursera notebook](https://www.coursera.org/learn/nlp-sequence-models/notebook/5NrJ6/operations-on-word-vectors-debiasing)

  * Take a look at [my notebook](https://github.com/dujm/DS_Sequence_Models/blob/master/notebooks/Finished/w2_Operations%2Bon%2Bword%2Bvectors%2B-%2Bv2_DJ.ipynb)  
(Pictures need to be added)


### 4. How to create an embedding layer and build a Kears LSTM model for sentiment classification?
* Try the Emotify exercise on Coursera [Coursera notebook](https://www.coursera.org/learn/nlp-sequence-models/notebook/acNYU/emojify)  
(Input a sentence and find the most appropriate emoji)  

* Take a look at [my notebook](https://github.com/dujm/DS_Sequence_Models/tree/master/notebooks/Finished/w2_Emojify_v2_DJ.ipynb)  
(Pictures need to be added)



--

### Reference
  * [Natural Language Processing & Word Embeddings, Coursera](https://www.coursera.org/learn/nlp-sequence-models/home/week/2)  

  * [Introduction to Word Embedding and Word2Vec](https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa)
