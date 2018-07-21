# recommendation-system

We build recommendation systems using the dataset containing reviews and ratings of Amazon instant videos.
The dataset is downloaded from http://jmcauley.ucsd.edu/data/amazon/.

In Collaborative Filtering.ipynb, we apply traditional item-based CF algorithm and SVD of matrices to train recommendation systems, and compare their performances.

In Deep Learning RS.ipynb, we re-implement the paper https://arxiv.org/abs/1701.04783, and then replace the CNN layers with GRU and LSTM layers, and compare their performances.
