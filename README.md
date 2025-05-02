# Empirical Evaluation of Machine Learning Ensembles for Rumor Detection

Paper URL: https://doi.org/10.1007/978-3-031-05061-9_30

## Abstract

Rumor detection is a recent and quite active topic of multidisciplinary
research due to its evident impact on society, which can even result in
physical harm to people. Despite its broad definition and scope, most existing
research focuses on Twitter, as it makes the problem a bit more tractable from
the point of view of information gathering, processing, and further retrieval
of social network features. This paper presents an empirical study of novel
machine learning ensembles for the rumor classification task on Twitter. As it
has been observed that certain neural models perform better for specific
veracity labels, we present a study on how the combination of such classifiers
in different kinds of ensemble results in a new classifier that has better
performance. Using benchmark data, we evaluate three groups of models (two
groups of deep neural networks and a control group of classical machine
learning methods). In addition, we study the performance of three ensemble
strategies: Bagging, Stacking, and Simple Soft Voting. After varying several
parameters of the models, such as the number of hidden units and dropout, among
others experimental factors, our study shows that the LSTM, Stacked LSTM
(S-LSTM), Recurrent Convolutional Neural Networks (RCNN), and Bidirectional
Gated Recurrent Unit (Bi-GRU) yields the best results reaching an accuracy of
0.93 and an average precision of 0.97.

## Code

This is joint work with Andres Zapata, and the code and other artifacts are
available at https://github.com/andres-zapata/deteccionDeRumoresConEnsamble (in
Spanish).

## Dataset

The research uses the Twitter16 dataset as published by Wei Gao et al. in [this
link](https://www.dropbox.com/s/7ewzdrbelpmrnxu/rumdetect2017.zip?dl=0). The
folder contains both Twitter15 and Twitter16 datasets. As specified by the
original authors: *"Note that constrained by the terms of Twitter service, we
cannot contain the content of the rest of the tweets. Data users can obtain the
specifics based on the provided tweet IDs and uids by their own."*
