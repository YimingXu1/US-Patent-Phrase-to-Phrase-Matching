# U.S. Patent Phrase to Phrase Matching
## Kaggle Competition - Help Identify Similar Phrases in U.S. Patents

### Introduction

Over the past two centuries, the USPTO has amassed nearly 11 million patents, and such massive amounts of data have created difficulties in patent examination and search. How can a patent examiner determine whether a newly-filed patent has previously been described? What happens if a patent searcher finds the subject he is looking for in the vast ocean of data?

We can address the aforementioned issues by training models on a novel semantic similarity dataset to extract relevant information by matching key phrases in patent documents. Specifically, given a pair of phrases, our model can predict the similarity score (0/0.25/0.5/0.75/1) between the two phrases.

Cooperative Patent Classification was added as a technical domain context to assist us in resolving such ambiguities as an additional feature for the disambiguate. For example, if one invention claims to be "strong material" and another uses "steel," they may be equivalent if the domain is steel, but not if the domain is ripstop fabric (you don't want steel for your parachute).


Todo：

Upload EDA

Upload Model

Upload Dataset
