# Unsupervised Image Retrieval
In this project, we have implemented an unsupervised image retrieval system with the help of the CNN autoencoder, RESNET, and CBIR (Content-Based Image Retrieval) framework. The model design consists of an autoencoder that converts the input data into a new representation in the form of feature vectors from which we evaluate the similarity between images using the KNN (K-Nearest Neighbour) method. Images that are closer to one another in the latent space resemble one another more than those that are further apart. Images then selected are transformed into their original representations from the decoder part of the autoencoder.
## Setup
Simply upload the provided ipynb file into Google Colab or Jupyter Notebook (Colab recommended) and run the program. The dataset should be present in the specified location in your drive for training.

## Dataset
[Dataset downlaod link here](http://vis-www.cs.umass.edu/lfw/)

