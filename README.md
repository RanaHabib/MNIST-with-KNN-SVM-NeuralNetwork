# Machine Learning algorithms

Contains the MNIST dataset with several classifiers applied. The MNIST dataset is first extracted from the original website. HOG (histogram of oriented gradients) was then applied to the features for the feature engineering process. Then we'll use KNN, SVM and neural network to test the accuracy of each classifier.

## Theoretical Foundations of Machine Learning

### Course Project

#### MNIST

MNIST digits dataset will be utilized. It is a dataset of handwritten numbers from 0 to 9. MNIST has a training set of 60,000 examples, and a test set of 10,000 examples. It can be downloaded from: http://yann.lecun.com/exdb/mnist/
K Nearest Neighbors (KNN) is a classifier that finds the class of the test sample based on the distance of it from the training samples. It finds the K training samples with smallest distance to the test sample. The dominant class in the K points is then selected as the test point class.
Project steps are as follows:
a. Load MNIST dataset.
b. Apply HOG features to the images (sklearn).
c. Implement KNN with ‘K’ as a parameter and Euclidian distance.
d. There must be another 2 models to be implemented (of your choice).

