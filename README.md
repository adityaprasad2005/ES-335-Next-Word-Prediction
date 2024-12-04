# ML Assignment 3: Text Generation with MLP, Streamlit App, and Model Comparisons

**This repository contains the code and explanations for Machine Learning Assignment 3, focusing on:**

* **Text Generation with Multi-Layer Perceptron (MLP):**
    * Implementing an MLP-based text generator using next-word prediction.
    * Exploring the effectiveness of RNNs as suggested by Andrej Karpathy's blog post.
    * Visualizing word embeddings using t-SNE or scatter plots for dimensionality reduction.
* **Streamlit Application:**
    * Building a user-friendly interface with controls for:
        * Input text
        * Predicting next k words/lines
        * Context length
        * Embedding dimension
        * Activation function
        * Random seed
    * Integrating pre-trained models (avoiding re-training for each user input).
* **Model Comparisons:**
    * Training and comparing MLP, MLP with L1/L2 regularization, and logistic regression with additional features on an XOR dataset.
    * Evaluating MLP, Random Forest, and Logistic Regression on the MNIST dataset.
    * Analyzing F1-score, confusion matrix, commonly confused digits, and t-SNE visualizations of trained vs. untrained models.
    * Transferring the trained MLP to predict on the Fashion-MNIST dataset and comparing embeddings.

**Code Structure:**

* `question1.ipynb`: Implements the text generation with MLP, Streamlit app, and instructions.
* `question2.ipynb`: Performs model comparisons on XOR, MNIST, and Fashion-MNIST datasets.
* `question3.ipynb`: Implements model training on MNIST using MLP, RF, and Logistic regression models and then compares them.
