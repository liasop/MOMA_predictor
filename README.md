# MOMAPredictor

This repository contains scripts from an artifical intelligence project done with 2 peers on the MOMA dataset. We investigated the impact of pruning and the effects of three different methods for handling imbalanced data on a classification task with decision trees. In particular, we use grammatical attributes of the titles of works of modern art to predict artist gender. The works and artists are taken from the metadata provided by the Museum of Modern Art. 

We evaluated the performance of both post-pruned and unpruned decision trees trained with data balanced using the methods of oversampling, undersampling, and ensemble sampling. The best performing tree was a post-pruned decision tree trained with data balanced using ensemble sampling.

A example row from our dataset after using NLP

![dataset](https://github.com/liasop/MOMA_predictor/blob/main/data.png?raw=true)

Our decision tree before balancing the data

![tree1](https://github.com/liasop/MOMA_predictor/blob/main/tree_pre_bal.png?raw=true)

Our decision tree after balancing the data

![tree1](https://github.com/liasop/MOMA_predictor/blob/main/tree_post_bal.png?raw=true)

The overall effects of various balancing methods 

![effects](https://github.com/liasop/MOMA_predictor/blob/main/effects_of_bal.png?raw=true)
