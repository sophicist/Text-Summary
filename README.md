# Text-Summary

 Often times you find that you may need to summarise 
 texts to just a few sentences automatically. There are machine learning 
 models that can do that but are very complex and take time to train and use.
 This project proposes a simple method that uses similarity of sentences as the criteria and returns the 
 desired summary number of sentenses.

# Requirements

* from nltk.corpus import stopwords
* from nltk.cluster.util import cosine_distance
* import numpy as np
* import networkx as nx
