# Activation Functions

### One-Liner:
*   **What it is:** A mathematical function applied to the output of a neuron in a neural network, determining whether and how strongly that neuron should "fire" or be activated.

### The Big Picture:
Activation Functions are the **decision-makers** inside a neural network. They introduce non-linearity, allowing the network to learn complex patterns and make sophisticated decisions, far beyond what a simple linear model could do.

### How it Works (The Core Idea):
A neuron calculates a weighted sum of its inputs. The activation function takes this sum and produces the final output of the neuron. This output is then passed as input to the next layer of neurons.

### Why it Matters:
Without an activation function, a neural network would just be a stack of linear transformations, no more powerful than a single linear regression. Activation functions are what give neural networks their ability to approximate any complex function.

### A Simple Analogy:
**A team of advisors making a decision.**
*   The **weighted sum** is like each advisor giving their opinion based on their expertise.
*   The **activation function** is the team leader who listens to the combined opinion and makes the final yes/no decision or a nuanced judgment.
*   A simple **step function** would be a strict "yes" or "no."
*   A **sigmoid function** would be a probabilistic "probably yes" or "probably no."

### Common Activation Functions & Examples:
*   **Sigmoid:** Squishes values to between 0 and 1. Good for probability outputs. (Historically important)
*   **ReLU (Rectified Linear Unit):** Returns the input if positive, else returns 0. The most popular choice for hidden layers in deep networks due to its simplicity and effectiveness.
*   **Tanh:** Squishes values to between -1 and 1.
*   **Softmax:** Used in the output layer for classification to turn scores into probabilities that sum to 1.

---
*🌳 **A Fundamental Building Block:** Essential for [[Neural Networks]] and [[Deep Learning]].
* 📈 **Introduces Non-Linearity:** The key to learning complex patterns.
* 🧠 **The "Firing" Mechanism:** Mimics the all-or-nothing principle of biological neurons.
