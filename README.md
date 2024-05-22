An Empirical Study of Over-Training Regimes in Scaling Language Models

This paper studies the intricacies of scaling language models, particularly in over-training regimes. 
The prevalent trend of scaling language models often involves amplifying both the parameter count and the training dataset size. 
However, recent works focus on over-training a model with an amount of data exceeding the optimal level for a given compute budget, which leads to the case that bigger models without over-training not always result in better performance. 
Motivated by this limitation, we conduct an extensive series of experiments to examine the impact of varying degrees of over-training on models, with up to 200 billion training tokens and 7 billion parameter models. Interestingly, we discover that when the over-training ratio exceeds 20, the performance enhancement associated with an increase in the over-training ratio diminishes, indicating a significant over-training restriction. 
Furthermore, we introduce and empirically validate a novel set of over-training scaling laws, providing a more accurate prediction of the performance of over-trained large models compared to previous scaling laws. These laws are particularly effective when dealing with a higher number of over-trained smaller models.
