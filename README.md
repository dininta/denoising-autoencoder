# ISPR - Midterm 3

*Assignment 1*

DATASET (MNIST): http://yann.lecun.com/exdb/mnist/

Train a denoising or a contractive autoencoder on the MNIST dataset: try out different architectures for the autoencoder, including a single layer autoencoder, a deep autoencoder with only layerwise pretraining and a deep autoencoder with fine tuning. It is up to you to decide how many neurons in each layer and how many layers you want in the deep autoencoder. Show an accuracy comparison between the different configurations.

Provide a visualization of the encodings of the digits in the highest layer of each configuration, using the t-SNE model to obtain 2-dimensional projections of the encodings.

Try out what happens if you feed one of the autoencoders with a random noise image and then you apply the iterative gradient ascent process described in the lecture to see if the reconstruction converges to the data manifold.

***

Useful readings:
- https://www.deeplearningbook.org/contents/autoencoders.html
- http://colah.github.io/posts/2014-10-Visualizing-MNIST/
- https://distill.pub/2016/misread-tsne/
- https://www.jmlr.org/papers/volume11/erhan10a/erhan10a.pdf
- https://www.jmlr.org/papers/volume15/alain14a/alain14a.pdf
- https://arxiv.org/pdf/1206.5538.pdf
- http://proceedings.mlr.press/v28/kamyshanska13.pdf