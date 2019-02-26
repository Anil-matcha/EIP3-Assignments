Name :- Matcha. Anil , Email :- matcha72@gmail.com , Batch :- 1

# Convolution

Convolution in neural nets is the operation of multiplying an input matrix such as an image with a kernel(another matrix) which is smaller in size than the input image. The multiplication is done one-on-one and the kernel is slided over the input to cover it entirely. It is done to extract important details from the input specific to the task 

![alt](https://cdn-images-1.medium.com/max/1600/1*Fw-ehcNBR9byHtho-Rxbtw.gif)

# Filters/Kernels

Filter/Kernel in a neural network refers to a matrix which is multiplied to input to obtain specific information. To the input a bunch of filters are applied each performing a different action and the information is passed on to the next layer. In older computer vision days the kernels are hand prepared but in neural networks backpropagation does the work for us.

![alt](https://cdn-images-1.medium.com/max/1600/1*_34EtrgYk6cQxlJ2br51HQ.gif)



# Epochs

To train a neural network inputs are sent in batches. When all the inputs from different batches sent combined equals total number of inputs in dataset it is considered an epoch.  A neural network is trained for a certain number of epochs until no improvement in accuracy is observed or until the network doesn't overfit.

![alt](https://kheangseng.files.wordpress.com/2010/09/how-to-choose-epochs1.jpg)

# 1x1 Convolution

In neural networks 1x1 convolutions are generally used to reduce the dimensions of input in the filter dimension. As the depth of the neural network is increased in general the filter dimension is increased which leads to a lot of computation. To save this effort 1x1 convolutions are used. They were extensively used in Google's inception architecture

![alt](https://raw.githubusercontent.com/iamaaditya/iamaaditya.github.io/master/images/conv_arithmetic/full_padding_no_strides_transposed_small.gif)

# 3x3 Convolution

3x3 Convolution is the standard convolution used in the latest neural network architectures. All major hardware are made efficient to run 3x3 convolutions hence using 3x3 convolutions provides an advantage. Any higher dimension convolution can be represented by multiple 3x3 convolution such as receptive field of 1 5x5 is same as 2 3x3 stacked together. 

![alt](https://mlnotebook.github.io/img/CNN/convSobel.gif)

