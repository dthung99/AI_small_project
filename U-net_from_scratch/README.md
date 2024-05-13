# U_net_from_scratch
Aim: building a segmentation model for a customized medical MRI dataset
Method:
+ Building a U-net with 4 downsampling, 4 upsampling layers and skip connections between them
+ Downsampling with stride convolution, upsampling with bi-linear interpolation
+ Two convolutional layer with ReLu before downsampling/upsampling
+ Regularisation with Batchnorm
+ Loss function: generalized dice loss
Result:
+ Generalized dice score >0.9

