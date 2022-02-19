# MCMC for noisy XOR classification

I created a BNN with Metropolis-Hastings sampler, which is trained on a train dataset of 10k points, and tested on a test dataset of 2k data points.

The MLP has a hidden layer and an output layer. The hidden layer has 3 nodes. Each layer uses sigmoid activation function, and all the weights are initialized using a standard normal distribution (chosen arbitrarily).

The weights are sampled by Metropolis Hasting algorithm with the proposal mean being the current mean of the weight, with standard deviation of 1. The acceptance distribution is uniform. I did not use a specific prior which could distil important knowledge of the XOR function in the neurons. Instead, I opted for a generic function.

The best model with Metropolis-Hastings sampler gave an accuracy of 91.1% on the test dataset, whereas a random ensemble of models gave an accuracy of 88.0%.
