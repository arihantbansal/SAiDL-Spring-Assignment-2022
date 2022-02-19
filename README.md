# SAiDL Spring Assignment 2022

This repository is the [Spring Induction Assignment](https://github.com/SforAiDl/SAiDL-Spring-2022-Induction-Assignment) of [Society for Artificial Intelligence and Deep Learning](https://github.com/sforaidl/) for the year 2022.

The attempted sections are:

1. [Natural Language Processing](https://github.com/arihantbansal/SAiDL-Spring-Assignment-2022/tree/main/NLP)
2. [Core ML](https://github.com/arihantbansal/SAiDL-Spring-Assignment-2022/tree/main/Core%20ML)
3. [Literature Review](https://github.com/arihantbansal/SAiDL-Spring-Assignment-2022/tree/main/Literature%20Review)

## Natural Language Processing

### Aim

To implement [Mixup](https://arxiv.org/pdf/2004.12239) data augmentation technique on the [TREC](https://huggingface.co/datasets/trec) dataset.

### Implementation

Created a baseline BiLSTM model, with the following results:

Epochs: 15
Train Loss: 0.065 | Train Acc: 97.71%
Test. Loss: 0.528 | Test. Acc: 88.59%

Then, created a BiLSTM with MixText algorithm for the forward function, giving the following results:

Epochs: 15
Train Loss: 1.002
Test. Loss: 0.614 | Test. Acc: 84.81%

## Core ML

To train a model using Markov Chain Monte Carlo (MCMC) sampling on noisy XOR dataset

## Implementation

Created a BNN sampled with Metropolis-Hastings algorithm.

Epochs: 10000
Accuracy Score: 0.911

Also, created a BNN sampled with random sampler for baseline.

Epochs: 1000
Accuracy Score: 0.692

## Literature Review

Writing a review of the paper "Induction of Decision Trees".
