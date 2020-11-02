# scientific_authorship

Contains data used for authorship attribution classification experiments on scientific papers from ACL and EMNLP, as well as the source code for performing the classification experiments.

Data files
----------
- `acl_pre2014.zip`, `emnlp_pre2014.zip`, `acl_201x.zip`, `emnlp_201x.zip`: contains all of the articles used in the experiments, in .xml format, as extracted by the Grobid tool from the raw pdfs.
- `vocabulary.pkl`: contains a precomputed vocabulary of all words in the dataset, excluding rare words, as a serialized python dictionary.
- `vocabulary_vectors.pkl`: contains a precomputed list of embedding vectors for words in the vocabulary, as a serialized python dictionary with words as keys and embedding vectors as values. The embeddings are word2vec embeddings pretrained on Google News.

## References
Full paper describing methodology and results can be found here: [The Myth of Double-Blind Review Revisited: ACL vs. EMNLP, Cornelia Caragea, Ana Uban, Liviu P. Dinu](https://www.aclweb.org/anthology/D19-1236/)
