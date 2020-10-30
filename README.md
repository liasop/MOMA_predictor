# MOMAPredictor

This repository contains scripts from an artifical intelligence project done with 2 peers on the MOMA dataset. We investigatde the impact of pruning and the effects of three different methods for handling imbalanced data on a classification task with decision trees. In particular, we use grammatical attributes of the titles of works of modern art to predict artist gender. The works and artists are taken from the metadata provided by the Museum of Modern Art. 

We evaluated the performance of both post-pruned and unpruned decision trees trained with data balanced using the methods of oversampling, undersampling, and ensemble sampling. The best performing tree was a post-pruned decision tree trained with data balanced using ensemble sampling.
