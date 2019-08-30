# Image classification

This is one of the other CNN projects using CIFAR-10 dataset. But the difference in this project from the other one using the same dataset
is that this one is made using tensorflow rather than Keras .

## Introdution

In this project, you'll classify images from the CIFAR-10 dataset. You can preview the dataset from [here](https://www.cs.toronto.edu/~kriz/cifar.html)

- We'll preprocess the images, then train a convolutional neural network on all the samples. 
- The images need to be normalized and the labels need to be one-hot encoded. 
- We'll build a convolutional, max pooling, dropout, and fully connected layers. 
- At the end, we'll get to see your neural network's predictions on the sample images.
- You can download the dataset from [here](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)

## Libraries

In this we have used many different libraries , you can download using 2 different ways :
```
 pip install library_name 
```

```
 conda install library_name
```

- I personally prefer to use pip.

We'll need to have these following libraries
- urlib
- os
- pickle
- tqdm
- tarfile
- numpy
- pandas
- tensorflow
