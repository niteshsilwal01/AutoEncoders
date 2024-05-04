Autoencoders are a unique category of neural network designs where the output mirrors the input. They are trained in an unsupervised manner to grasp highly simplified representations of the input data. These simplified features are then transformed back to reconstruct the original data. Essentially, autoencoders are tasked with predicting their input, essentially modeling the identity function. These networks feature a narrow middle section with a few neurons, compelling them to generate effective representations that condense the input into a low-dimensional code. This code is utilized by the decoder to recreate the original input.

A standard autoencoder architecture consists of three primary components:

1. **Encoding Architecture**: 
This component includes a sequence of layers with progressively fewer nodes, culminating in a latent view representation.

2. **Latent View Representation**: 
This represents the most basic level of space where inputs are minimized and information is retained.

3. **Decoding Architecture**: 
This is essentially the mirror image of the encoding architecture, with each layer having an increasing number of nodes, ultimately producing an output that closely resembles the original input.

The AutoEncoder network architecture used for image reconstruction in this notebook is as below:

![alt text](<images/AE Network Diagram.png>)

   