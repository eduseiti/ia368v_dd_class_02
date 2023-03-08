# ia368v_dd_class_02
IA368V DD 2023/03/09 class exercises.

This repository contains the notebooks for the resolution of the 3 exercises proposed for the 2nd class of IA368V DD (held on 2023/03/09):

* [BM25_TREC-DL_2020.ipynb](BM25_TREC-DL_2020.ipynb): Execution steps to apply the Pyserini's BM25 implementation to execute the [TREC-DL_2020 Passage Ranking task](https://microsoft.github.io/msmarco/TREC-Deep-Learning-2020.html#passage-ranking-task).

* [boolean_retrieval_TREC-DL_2020.ipynb](boolean_retrieval_TREC-DL_2020.ipynb): Boolean retrieval implementation for the same [TREC-DL_2020 Passage Ranking task](https://microsoft.github.io/msmarco/TREC-Deep-Learning-2020.html#passage-ranking-task).

* [tfidf_retrieval_TREC-DL_2020.ipynb](tfidf_retrieval_TREC-DL_2020.ipynb): Finally, TF-IDF weighting retrieval implementation for the same [TREC-DL_2020 Passage Ranking task](https://microsoft.github.io/msmarco/TREC-Deep-Learning-2020.html#passage-ranking-task).


## Final results

Here are the final numbers for the 3 different approaches:

|         | BM25   | Boolean | TF-IDF weighting |
|---------|--------|---------|------------------|
| nDCG@10 | 0.4876 | 0.0538  | 0.1740 |


