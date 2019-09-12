# ML-Exercise-MNIST-dataset
This repository is contains the result of a school assignment on the subject of Machine Learning. The assignment description can be found below:

Description
Fashion-MNIST (https://github.com/zalandoresearch/fashion-mnist) is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 

Part 1 Modelling, PCA and evaluation

Load the dataset and split into a training set and test set. and split it into a training set and a test set.
Train a Random Forest classifier on the dataset and time how long it takes, then evaluate the resulting model on the test set.
Next, use PCA to reduce the dataset's dimensionality (with an explained variance ratio of 95%).
Train a new Random Forest classifier on the reduced dataset and measure how long it takes.
Was training much faster?
Evaluate the classifier on the test set: how does it compare to the previous classifier?
Apply softmax regression (using the original dataset) and time how long it takes, then evaluate the resulting model on the test set.
Apply softmax regression (using the reduced dataset) and time how long it takes, then evaluate the resulting model on the test set.
What can you conclude from the results?
Part 2. Visualisation

Use t-SNE to reduce the MNIST dataset down to two dimensions and plot the result using Matplotlib. Use dimensionality on a random subset of 12,500 images.
Plot a scatterplot using different colours for each class.
What can you conclude?
Now try t-SNE for a combination of 3 labels: sneaker, bag and t-shirt
