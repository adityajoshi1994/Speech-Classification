# Speech-Classification

<h2> Semi-supervised Learning </h2>
Many real-world applications contain a small number of labeled instances but a large number of unlabeled instances. Machine learning algorithms that are able to utilize the information from unlabeled instances are known as semi-supervised approaches.

In this project we deal with the data of speech excerpts from various Presidential candidates and the task is to predict the speaker given a new excerpt.

<h2> Multiclass logistic regression</h2>
The multiclass logistic regression uses <a href="https://en.wikipedia.org/wiki/Softmax_function" > soft max </a> function to calculate the probability of each class instead of a logistic <a href="https://en.wikipedia.org/wiki/Sigmoid_function" > sigmoid </a> in case of a binary classification. Each class has its own weight vector and eventually we end up training a matrix of n X k where n is the number of features and k is the number of classes.
