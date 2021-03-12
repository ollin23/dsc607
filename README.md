# dsc607
Data Mining Project

This project is a basic movie recommendation engine. I scraped the
data from IMDb, processed it with Pandas, and embedded the descriptions
using TF-IDF via Scikit-Learn and Doc2Vec via Gensim.

The results were somewhat unexpected. The cosine similarity matrix of
the TF-IDF embeddings was ~13GB for a single feature which precluded 
using multiple features for assessment.
