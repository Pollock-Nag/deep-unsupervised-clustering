# deep-unsupervised-clustering

Unsupervised learning is a cornerstone of modern machine learning, focused on discovering
inherent patterns and structures within unlabeled data. Among its primary tasks, clustering
aims to group data points into meaningful subsets. While traditional algorithms like K-Means
are effective on low-dimensional data, they often fail on complex, high-dimensional data such as
images. Deep clustering methods address this by using neural networks to learn low-dimensional
feature representations that are more amenable to clustering.

This project specifically explores and compares deterministic and non-deterministic unsu-
pervised neural network models for the application of unsupervised clustering on the CIFAR-10

image dataset.
The primary objectives of this research are:

• To design and implement a deterministic deep clustering model using an Enhanced Con-
volutional Autoencoder (CAE) as a strong baseline.

• To design and implement a non-deterministic model using a Variational Autoencoder
(VAE) to investigate the impact of stochasticity on representation learning.
• To quantitatively evaluate and compare the clustering performance of both deep models
against traditional methods (K-Means, PCA + K-Means) using standard metrics.
• To analyze the results and discuss the insights gained from comparing the deterministic
and non-deterministic approaches.

This report documents the design, implementation, and evaluation of these models, providing a comprehensive analysis of their behavior and performance.
