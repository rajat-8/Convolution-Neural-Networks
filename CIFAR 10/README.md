# CIFAR 10 Dataset using Convolution Neural Networks

In this notebook, we train a CNN to classify images from the CIFAR-10 database.


## Workflow 
- we first load the database which we importes from keras.datasets
- We then scale the images in [0,1]
- we  then divide the dataset into training, validation and testing
- (optional) we can also use image augmention to increase the dataset and make it more versatile to identify images
  from keras.preprocessing.image import ImageDataGenerator
   
 - create a model and train the model on the given training dataset and optimise in the validation data.
 - finally, calculate the accuracy on the testing data
 
 ## Conclusion
 
 - The accuracy came out for the given model is 66.01%
 - The accuracy on the given dataset may not be much but we can increase its accuracy by using more complex networks 
  but they would take hours to days to trained.you can can such examples 
  [here](http://blog.kaggle.com/2015/01/02/cifar-10-competition-winners-interviews-with-dr-ben-graham-phil-culliton-zygmunt-zajac/)
