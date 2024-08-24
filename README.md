# GAN-implementation

GANs Tutorial
Very simple implementation of GANs, DCGANs, CGANs, WGANs, and etc. with PyTorch for various dataset (MNIST, CARS, CelebA).

You can run the code at Jupyter Notebook. And actually you can also run these codes by using Google Colab immediately (needed downloading some dataset)!

Sometimes ipynb files do not work in Github, please clone and run it in your server.

# Requirements
python 3.6 (Anaconda)
pytorch 1.0.0 (updated from 0.4.0. If you want to use the previous version, then find previous commit.)

# Implementation List
MNIST
Vanilla GAN
Conditional GANs
DCGAN
Wasserstain GAN
WGAN-gp
infoGAN
CARS (Stanford dataset)
you can download the dataset from https://ai.stanford.edu/~jkrause/cars/car_dataset.html
DCGAN
But I think the dataset is small and needs preprocessing a lot.
CelebA (aligned dataset)
you can download the dataset from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
BEGAN
R1GAN
Experimental Results
You can also see the samples at ipynbs.
After DCGAN, DCGAN with condition is a base model.
Trained 30 epochs respectively.
