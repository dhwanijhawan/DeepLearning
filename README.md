# DeepLearning
Deep Learning with PyTorch : Siamese Network


Implemented a Siamese Network, and trained the network with Triplet loss function. Created Anchor, Positive, and Negative image datasets, as inputs of the triplet loss function, through which the network learned feature embeddings.

Dataset : Market-1501 dataset  https://www.kaggle.com/pengcw1/market-1501

A Siamese Network is a type of neural network architecture that is used for tasks that involve finding similarities or differences between two input samples. The network consists of two identical subnetworks that share the same set of weights and are trained simultaneously.

The basic idea behind a Siamese Network is to learn a similarity metric between two input samples. In other words, the network is trained to output a high value when the two input samples are similar and a low value when they are dissimilar. This makes it useful for a variety of applications, such as image or text similarity matching, face recognition, and signature verification.

One of main advantages of a Siamese Network is that it can be trained with very few examples, making it useful for applications where data is limited. Additionally, the shared weights between the two subnetworks allow the model to generalize well to new inputs.

Siamese Networks have been shown to be effective in a wide range of applications, including image recognition, classification, and speech recognition. They have also been applied to natural language processing tasks such as sentence similarity and paraphrase detection.

