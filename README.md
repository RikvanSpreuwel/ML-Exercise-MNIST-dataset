# ML-Exercise-MNIST-dataset
This repository is contains the result of a school assignment on the subject of Machine Learning. The assignment description can be found below:

# Description
Fashion-MNIST (https://github.com/zalandoresearch/fashion-mnist) is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 

Part 1 Modelling, PCA and evaluation

1. Load the dataset and split into a training set and test set. 
2. Train a Random Forest classifier on the dataset and time how long it takes, then evaluate the resulting model on the test set.
3. Next, use PCA to reduce the dataset's dimensionality (with an explained variance ratio of 95%).
4. Train a new Random Forest classifier on the reduced dataset and measure how long it takes.
5. Was training much faster?
6. Evaluate the classifier on the test set: how does it compare to the previous classifier?
7. Apply softmax regression (using the original dataset) and time how long it takes, then evaluate the resulting model on the test set.
8. Apply softmax regression (using the reduced dataset) and time how long it takes, then evaluate the resulting model on the test set.
9. What can you conclude from the results?

Part 2. Visualisation

1. Use t-SNE to reduce the MNIST dataset down to two dimensions and plot the result using Matplotlib. Use dimensionality on a random subset of 12,500 images.
2. Plot a scatterplot using different colours for each class.
3. What can you conclude?
4. Now try t-SNE for a combination of 3 labels: sneaker, bag and t-shirt
