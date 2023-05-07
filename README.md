# DCGAN
Created a deep convolutional generative adversarial network (DCGAN) on a MNIST dataset with Pytorch. The goal was to train a discriminator and generator in order to replicate real life images of numbers, from the MNIST dataset.
A batch size of 128, input noise of 100 dimension and Adam optimizer with learning rate of 2e-4 was used.
The Generator produced a [batchsize, 1, 28, 28] vector (image) from the given [batchsize, 100, 1, 1] vector (noise).
The Discriminator produced a [batchsize, 1] vector (image) from the given input [batchsize, 1, 28, 28] vector (noise).
Training was done in only 5 epochs with 600 training steps (~5 min) to achieve adequate results.
