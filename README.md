# Goodreads Project

#### Data were downloaded from [webpage](https://mengtingwan.github.io/data/goodreads.html) .

The datasets were collected in late 2017 from [goodreads](https://goodreads.com). Details of the datasets are described in the [dataset website](https://mengtingwan.github.io/data/goodreads.html)

## Goals

1. Explore high dimensional user data from Goodreads.
2. Learn new-to-me approaches in NLP and implicit collaborative filtering/recommender systems.



## Main Notebooks

Used for my analyses so far:

- [makeDBs_complete.ipynb](/makeDBs_complete.ipynb) and [makeDBs_romance.ipynb](/makeDBs_romance.ipynb): Create SQLite database and tables for data organization/storage.
- [statistics.ipynb](/statistics.ipynb): EDA notebook to compute basic statistics of data and understand rating/review trends across genres.
- [reviews_sentiment.ipynb](/reviews_sentiment.ipynb): Sentiment analysis on >3.4 million romance book reviews.
- [romance_recommender.ipynb](/romance_recommender.ipynb): Implicit collaborative filtering on >16 million romance book ratings.



## Dataset Citations

- Mengting Wan, Julian McAuley, "[Item Recommendation on Monotonic Behavior Chains](https://github.com/MengtingWan/mengtingwan.github.io/raw/master/paper/recsys18_mwan.pdf)", in RecSys'18. [[bibtex](https://dblp.uni-trier.de/rec/bibtex/conf/recsys/WanM18)]
- Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "[Fine-Grained Spoiler Detection from Large-Scale Review Corpora](https://github.com/MengtingWan/mengtingwan.github.io/raw/master/paper/acl19_mwan.pdf)", in ACL'19. [[bibtex](https://dblp.uni-trier.de/rec/bibtex/conf/acl/WanMNM19)]