# IMAGE-CLASSISICATION using CIFAR-10 DATSET

## Datasets:

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 
training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. 

The test batch contains exactly 1000 randomly-selected images from each class.

The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

### Dataset Summary and Exploration

Number of training examples = 40000

Number of validation examples = 10000

Number of testing examples = 10000

Image data shape = (32, 32, 3)

Number of classes = 10

### Labels and Classes

0 : airplane  

1 : automobile 

2 : bird

3 : cat  

4 : deer  

5 : dog  

6 : frog  

7 : horse 

8 : ship  

9 : truck  

## Dataset Visualization

![](https://github.com/raianilar17/IMAGE_CLASSIFICATION/blob/master/output_3.png)

![](https://github.com/raianilar17/IMAGE_CLASSIFICATION/blob/master/output_4.png)

## Design and Test a Model Architecture

I used two different kind of architecture :

1.LENET-5(used modified version) 

2.VGG-16

VGG16 perfoms very well and produce high testing accuracy as compare to LENET-5.

## Confusion matrix

I also compute  confusion matrix  to measure the performance of an model(VGG16). The name confusion matrix reflects the fact that it makes it easy for us to see what kind of confusions occur in our classification algorithms. It's also known as an error matrix.A confusion matrix is a summary of prediction results on a classification problem.The number of correct and incorrect predictions are summarized with count values and broken down by each class. This is the key to the confusion matrix.The confusion matrix shows the ways in which your classification model is confused when it makes predictions.It gives us insight not only into the errors being made by a classifier but more importantly the types of errors that are being made.


## Test a Model on Unseen Images (Output Top 5 Softmax Probabilities For Each Image):

![](https://github.com/raianilar17/IMAGE_CLASSIFICATION/blob/master/output1.png)

![](https://github.com/raianilar17/IMAGE_CLASSIFICATION/blob/master/output_2.png)


For more detail explanation , please look the [Notebook](final_Cifar_10_Classification.ipynb)

## Future Work

Improve Testing accuracy

Apply different Hyperparameters(leraning_rate, batch_size,epochs,...)

Use different Regularization technique

Apply different Architecture

Apply on differant application(field).


