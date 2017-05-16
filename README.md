# gan_face_generation
Use generative adversarial networks to generate new images of faces.

We first build an train the network on the grayscale MNIST dataset and then train the same network on the celebA dataset (RGB), to generate faces.

The network is a Convolutional GAN, built with TensorFlow 1.1.0.

To run this code on your own system, I recommend creating a new conda environment from the env_requirements.txt provided.
You may have to install TensorFlow directly with pip, instead of using Conda.

I recommend opening the Jupyter notebook called dlnd_face_generation.ipynb to run and test the network.
