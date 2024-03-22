# LFM1M-Sensible-Attributes
A reduced version of LastFM1B dataset obtained by randomly sampling ratings and keeping only users and items with a number of occurences > 10. We also provide its freebase extracted KG. This dataset is though for Explainable Recommendation task through KG but can also be used for general recommendation or knowledge aware recommender systems.

*Note: this format is directly employable to train multiple models from our [PEARLM LIBRARY](https://github.com/Chris1nexus/pearlm)*

This table collects some statistics related to the dataset we are going to cover.

| Domain     	| Dataset Name      	| # of Users 	| # of Items 	| # of Interactions |
|------------	|-------------------	|------------	|------------	|-------------------
| Music      	| LastFM 1M [Preprocessed]         	| 4818           	| 12491            	| 1091275                   	|

This dataset has been produced and used by the following papers, we would appreciate an acknowledgment by citing one of them:

```
Balloccu, Giacomo, Ludovico Boratto, Christian Cancedda, Gianni Fenu, and Mirko Marras. 
"Faithful Path Language Modelling for Explainable Recommendation over Knowledge Graph." arXiv preprint arXiv:2310.16452 (2023).
```

```
Balloccu, G., Boratto, L., Cancedda, C., Fenu, G., Marras, M. (2023). 
Knowledge is Power, Understanding is Impact: Utility and Beyond Goals, Explanation Quality,   
and Fairness in Path Reasoning Recommendation. In: , et al. Advances in Information Retrieval. 
ECIR 2023. Lecture Notes in Computer Science, vol 13982. Springer, 
Cham. https://doi.org/10.1007/978-3-031-28241-6_1
```
