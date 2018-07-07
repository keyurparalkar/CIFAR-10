# CIFAR-10
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

Here are the classes in the dataset, as well as 10 random images from each:

  * airplane										 
  * automobile										
  * bird										
  * cat										
  * deer										
  * dog										
  * frog										
  * horse										
  * ship										
  * truck										

This python notebook focuses on implementing ConvNet for cifar-10 with four convolution ,relu and maxpooling operation which are followed by three fully connected layers.

### Steps to run 
Make sure that you have conda installed.
```
conda install pytorch torchvision -c pytorch
jupyter notebook
```

### Accuracies

>Train Set = 72.235
    
>Test Set = 53.62

