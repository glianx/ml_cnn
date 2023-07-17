The Convolutional Neural Networks use 2 Convolutional and Max pooling layers to detect high-level features such as edges and curves,
which is fed into the Neural Network. 

Convolutions slide kernels (a square matrix of pixels) over a preprocessed image. Each kernel can detect a specific
high-level feature, depending on the weights of the pixels in it. An elementwise multiplication 
and sum is performed, which means each pixel in the image is multiplied by the weight/pixel in the kernel. This is then added to an output matrix. 

This is convolution: the 3x3 kernel slides over the 5x5 image, and the weights in the kernel and the pixels of the original image are multiplied and summed.
The final result then goes into an output matrix. 

![Alt Text](https://media.giphy.com/media/i4NjAwytgIRDW/giphy.gif)


I have achieved around 70% accuracy with the kaggle cats-and-dogs dataset with 3 epochs.