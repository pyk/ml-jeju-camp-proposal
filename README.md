# Improve Sequence-to-Sequence model using Adversarial Learning in TensorFlow

In this proposal I will explain the reason why I want to be part of 
Machine Learning Jeju Camp 2017, what is the idea that I propose, why I'm so
excited about it and the general overview of step-by-step to implement my 
idea.

This proposal is based on these papers:

* [1] [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf) by Sutskever et al. (2014)
* [2] [Adversarial Learning for Neural Dialogue Generation](https://arxiv.org/pdf/1701.06547.pdf) by Li et al. (2017)
* [3] [A Hierarchical Neural Autoencoder for Paragraphs and Documents](https://arxiv.org/abs/1506.01057) by Li et al. (2015)


## My Goal
My goal on the Machine Learning Jeju Camp 2017 is to answer the following
question:

*Is Adversarial Learning can helps Seq2Seq model to beat the state-of-the art?*

![Benchmark Score](/benchmark-score.png)

so exciting!

## Idea
So in this camp, I want to implement Adversarial Learning to the
seq2seq model on the translation task using WMT'14 dataset. 

In this Adversarial Learning setup, I will use the seq2seq model as the 
generator network and binary-classifier based on [3] as the discriminator
network. 

## Overview step-by-step

1. Prepare the dataset
2. Build the seq2seq [1] model
3. Build the discriminator network model
4. Create the training & evaluation pipeline
5. Run the training and the evaluation
5. Done
