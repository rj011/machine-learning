# machine-learning
GITHUB LINK-------> https://github.com/rj011/machine-learning.git


This is a simple ml project incorporating keras using the mnist fashion data-set.
The aim is to train the model to recognise images of different garments such as T-shirts, trousers, jeans etc.
The mnist fashion is a dataset of 60,000 28x28 grayscale images of 10 fashion categories, along with a test set of 10,000 images.
Platform used for project: Tensorflow
Dataset: keras mnist fashion dataset
Training variables: x_train, y_train
Test variables: x_test, y_test
tf.keras.datasets.fashion_mnist.load_data()------> Used to load data from the data set
.normalize()-------> Used to reduce redundancy
model.add()-----> Adding neurons in input, hidden and output layers
Input layer uses activation function "relu"
Output layer uses activation "softmax"
.complie() to compile the program   optimizer-->adam  check metrics for accuracy
.fit() to train-----> 100 iterationns
.summary() gives a summary of the model created
.evaluate----> measure avg accuracy from all epochs
