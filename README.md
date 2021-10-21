# Image-Forgery-Detection

## INTRODUCTION: 
The pixel-based image forgery detection aims to verify the authenticity of digital images without any prior knowledge of the original image.Three of the most common manipulations in literature:
* Splicing
* Copy-move
* Removal

## DATASET:
The CASIA v2.0 dataset contains 12,622 images distributed 60-40 amongst authentic-tampered.

## MODELS:

### CONVOLUTIONAL NEURAL NETWORK 
A CNN is a Deep Learning algorithm which can take in an input image, assign importance to various aspects/objects in the image and be able to differentiate one from the other
* Convolution Layer
*  Pooling Layer
*   Fully – Connected Layer

### VGG-16
VGG-16 is a convolutional neural network that is 16 layers deep.	
Loads a set of weights pre-trained on ImageNet
Default input size is 224 x 224 pixels with 3 channels for RGB image. 	
Contains convolution layers of 3x3 filter with a stride 1 and maxpool layer of 2x2 filter of   stride 2.

## CONCLUSION

### CONVOLUTIONAL NEURAL NETWORK
* Tampered accuracy - 94.4282%
* Authentic accuracy - 92.4802%
* Total accuracy - 92.9072%

### VGG-16
* Tampered accuracy - 93.2655%
* Authentic accuracy - 88.5368%
* Total accuracy - 89.5732%

From the comparison, we conclude normal CNN model gives good accuracy.To conclude, while there is surely a lot of work still to be done in the image forgery detection domain, we believe that neural networks will be able to detect tampered images regardless of their difficulty in the near future.





