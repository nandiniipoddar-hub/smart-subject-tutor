Subject: Artificial Intelligence and Machine Learning (AIML) – B.Tech CSE Core
Topic 1: Artificial Intelligence vs Machine Learning vs Deep Learning
Artificial Intelligence (AI) is a broad field of computer science that focuses on creating machines capable of performing tasks that normally require human intelligence, such as reasoning, problem-solving, decision-making, and understanding language.

Machine Learning (ML) is a subset of AI that enables computers to learn from data and improve their performance without being explicitly programmed for every task. ML algorithms identify patterns in training data and use those patterns to make predictions or decisions.

Deep Learning (DL) is a subset of Machine Learning that uses artificial neural networks with multiple hidden layers to learn complex patterns from large datasets. It is widely used in image recognition, speech processing, and natural language processing.

Topic 2: Types of Machine Learning
Machine Learning is mainly divided into three major categories based on how an algorithm learns from data:

1. Supervised Learning: In supervised learning, the model is trained using labeled data, where both input features and their correct outputs are provided. The algorithm learns the relationship between inputs and outputs to make predictions on unseen data. Common algorithms include Linear Regression, Logistic Regression, Decision Trees, and Support Vector Machines (SVM). It is mainly used for Classification and Regression tasks.

2. Unsupervised Learning: In unsupervised learning, the model is trained using unlabeled data, where the correct output is not provided. The algorithm identifies hidden patterns, similarities, and structures within the dataset. Common techniques include K-Means Clustering, Hierarchical Clustering, and Principal Component Analysis (PCA). It is commonly used for customer segmentation and data analysis.

3. Reinforcement Learning: In reinforcement learning, an intelligent agent learns by interacting with an environment. The agent performs actions and receives rewards or penalties based on its decisions. Its objective is to learn an optimal policy that maximizes the total cumulative reward over time. It is commonly used in robotics, autonomous systems, and game-playing applications.

Topic 3: Artificial Neural Networks (ANN), Perceptron, and Backpropagation
An Artificial Neural Network (ANN) is a computational model inspired by the structure and functioning of the human brain. It consists of interconnected processing units called Neurons, which work together to identify patterns and learn relationships from data.

A basic ANN consists of three types of layers:

Input Layer: Receives input features from the dataset.

Hidden Layer: Processes information using weights, biases, and activation functions to learn complex patterns.

Output Layer: Produces the final prediction or classification result.

A Perceptron is the simplest type of artificial neural network and consists of a single computational neuron. It calculates a weighted sum of inputs, adds a bias, and applies an activation function to generate an output.

Backpropagation is a fundamental learning algorithm used to train neural networks. It calculates the error between predicted and actual outputs and propagates this error backward through the network to update weights and biases using gradient descent. This process is repeated over multiple training iterations to minimize the loss function and improve model accuracy.

Topic 4: Model Evaluation Metrics (Accuracy, Precision, Recall, and F1-Score)
Model Evaluation is the process of measuring how effectively a Machine Learning model performs on unseen data. Evaluation metrics help determine whether a model makes reliable predictions and identify areas where its performance can be improved.

1. Accuracy: Accuracy measures the proportion of correctly predicted observations out of all predictions made by the model. It is useful when the dataset has a balanced distribution of classes.

Formula: Accuracy = (TP + TN) / (TP + TN + FP + FN)

2. Precision: Precision measures how many of the observations predicted as positive are actually positive. It is particularly important when False Positives need to be minimized.

Formula: Precision = TP / (TP + FP)

3. Recall: Recall measures how many actual positive observations are correctly identified by the model. It is important when False Negatives need to be minimized, such as in disease detection.

Formula: Recall = TP / (TP + FN)

4. F1-Score: F1-Score is the harmonic mean of Precision and Recall. It provides a balanced evaluation when both False Positives and False Negatives are important.

Formula: F1-Score = 2 × (Precision × Recall) / (Precision + Recall)

Important Terms:

TP (True Positive): Correctly predicted positive cases.

TN (True Negative): Correctly predicted negative cases.

FP (False Positive): Negative cases incorrectly predicted as positive.

FN (False Negative): Positive cases incorrectly predicted as negative