# VQ_VAE_from_scratch
Aim: building a beta variational auto encoder (&beta;-VAE) and vector quantization VAE (VQ-VAE) for MNIST dataset.

Method:

+ &beta;-VAE minimize the output-input MSE and the KL distance of the latent distribution and a prior gaussian distribution

+ VQ-VAE minimize the output-input MSE and the Euclidean distance between latent vectors and codebook vectors (Not yet finished)

Result:

+ Recontructed image:

![Generated image](images/generated_image.png)

+ Original image:

![Original image](images/raw_image.png)