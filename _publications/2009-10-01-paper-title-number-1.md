---
title: "Life detection strategy based on infrared vision and ultra-wideband radar data fusion"
collection: publications
permalink: /publication/2019-02-28-paper-title-number-1
excerpt: 'This paper is about life detection method and mutimodal data fusion with deep neural network by lstm+cnn.'
date: 2019-02-28
venue: 'February 28'
paperurl: 'http://univeryinli.github.io/homepages/files/paper1.pdf'
citation: 'Yin L, Zhou Y M. Life detection strategy based on infrared vision and ultra-wideband radar data fusion[J]. arXiv preprint arXiv:1903.01564, 2019.'
---

The life detection method based on a single type of information source cannot meet the requirement of post-earthquake rescue due to its limitations in different scenes and bad robustness in life detection. This paper proposes a method based on deep neural network for multi-sensor decision-level fusion which concludes Convolutional Neural Network and Long Short Term Memory neural network (CNN+LSTM). Firstly, we calculate the value of the life detection probability of each sensor with various methods in the same scene simultaneously, which will be gathered to make samples for inputs of the deep neural network. Then we use Convolutional Neural Network (CNN) to extract the distribution characteristics of the spatial domain from inputs which is the two-channel combination of the probability values and the smoothing probability values of each life detection sensor respectively. Furthermore, the sequence time relationship of the outputs from the last layers will be analyzed with Long Short Term Memory (LSTM) layers, then we concatenate the results from three branches of LSTM layers. Finally, two sets of LSTM neural networks that is different from the previous layers are used to integrate the three branches of the features, and the results of the two classifications are output using the fully connected network with Binary Cross Entropy (BEC) loss function. Therefore, the classification results of the life detection can be concluded accurately with the proposed algorithm.

[Download paper here](http://univeryinli.github.io/homepages/files/paper1.pdf)

Recommended citation: Yin L, Zhou Y M. Life detection strategy based on infrared vision and ultra-wideband radar data fusion[J]. arXiv preprint arXiv:1903.01564, 2019.
