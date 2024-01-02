ABSTRACT:

There has been a recent interest in applying Transformers to tasks in computer vision, such as image segmentation
and image classification. In particular, Vision Transformers (ViT) and Hierarchical Vision Transformers via Shifted Windows
were used to compare the performance of Convolutional Neural Networks (CNNs) in the image classification task on the
CIFAR-100 dataset. With regularization, data augmentation, constructing hybrid models, and tuning hyperparameters, we
found that the Swin architecture with increased number of Swin blocks outperforms all model and experimental configurations
at 77.1% test accuracy. This can be compared to the best performance of the CNN model (67%) and the ViT (54.5%). Given
its performance and hierarchical structure, we also explored its potential as a basis unit for encoder and decoder in generative
modeling, notably Variational Autoencoder, in the Appendix
