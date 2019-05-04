# Assignment 1B

# *What are Channels and Kernels (according to EVA)?*

# Kernels
Kernel is also called as Feature Extractor or it may be Feature or it may be Filter.

When we are building CNN from scratch the filters of the layers are initialized from a Gaussian distribution formula. This size is random.

Convolution is process of matrix by another one matrix which is called as "Kernel".

Most common sizes are 5X5 or 3X3.The advantage of this size of Kernel is it extracts all the information from the image. Information loss is very minimal.

By using training we adjust the values of kernels. The number of output channels are depend on number of input channel which depends on the size of Kernel.

Each filter can give one feature. For edge detection from image there will one kernel and so on.

![alt text](https://lh3.googleusercontent.com/DG8CAeltoGTkMu5Z3inbmX5r8PefiOv_p8rJsUXXsFhm4g1DiqLl0eGP43xuCVmOghLE3UI=s139)
