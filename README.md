# MNIST-CNN
Performing Batch Normalization and Dropout techniques on CNN models.

Batch normalization reduces the amount by what the hidden unit values shift around (covariance shift). To increase the stability of a neural network, batch normalization normalizes the output of a previous activation layer by subtracting the batch mean and dividing by the batch standard deviation.
-- The parameters Gamma and Beta are learned along with other parameters of the network. If Gamma (γ) is equal to the mean (μ) and Beta (β) is equal to the standard deviation(σ) then the activation h_final is equal to the h_norm, thus preserving the representative power of the network.

A single model can be used to simulate having a large number of different network architectures by randomly dropping out nodes during training, this is called dropout!


