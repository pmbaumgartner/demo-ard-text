# Demo for News Article Collection and Volume Reduction Pipeline 

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pmbaumgartner/demo-ard-text/master)

Brief notebooks that run through the following processes using a dataset of [NYT Front Page articles](http://www.amber-boydstun.com/supplementary-information-for-making-the-news.html)

1. Find efficient keywords with word embeddings (`gensim`)
2. Remove duplicitous articles with cosine similarity on TFIDF vectors (`scikit-learn`)
3. Remove duplicitous articles with entity extraction and jaccard similarity (`spacy`)
4. Classify relevant articles (`scikit-learn`)

