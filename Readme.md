IMPROVED PRUNING FOR CONVOLUTIONAL NEURAL NETWORK

Big deep learning models including CNNs require lot of computation and memory. It becomes really challenging when you want to deploy model on end devices. Pruning is one of the techniques that can help reduce size of the model without compromising much on performance.

I have implemented the paper "Pruning filters for efficient convnets" by Hao li et al. considering the VGG-16 network and CIFAR-10 data set. I show there is almost no effect on performance after pruning the trained model. Also compared results with pruned model trained from scratch. I also proposed cosine similarity based pruning on top of the given approach to further prune the model.

You can find all details and results in the given report and presentation. 