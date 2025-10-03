# Hyperparameters

### One-Liner:
*   **What it is:** Configuration settings for machine learning models that are set before the training process begins and control how the model learns.

### The Big Picture:
Hyperparameters are the **control panel** for machine learning. Unlike model parameters (weights and biases) that are learned from data, hyperparameters are choices made by the data scientist that guide the learning process itself.

### How it Works (The Core Idea):
Hyperparameters influence:
- **How fast** the model learns (Learning Rate)
- **How complex** the model can be (Number of Layers, Hidden Units)
- **How regularized** the model is (Dropout Rate, L2 Penalty)
- **Training duration** (Number of Epochs)

### Why it Matters:
Choosing the right hyperparameters can be the difference between a model that works brilliantly and one that fails completely. They're often tuned experimentally to find the optimal configuration.

### A Simple Analogy:
**Baking a cake.**
*   **Model Parameters:** The final cake's texture and taste (learned during baking).
*   **Hyperparameters:** The recipe choices: oven temperature, baking time, ingredient proportions (set before baking).
*   Change the hyperparameters (recipe), and you get a completely different cake!

### Real-World Examples:
*   **Learning Rate:** How big of steps to take during gradient descent.
*   **Batch Size:** How many examples to process before updating weights.
*   **Number of Epochs:** How many times to iterate through the entire dataset.
*   **Dropout Rate:** What percentage of neurons to randomly disable during training.

---
*🌳 **A Foundational Concept:** Essential for all [[Machine Learning]].
*🎛️ **The Control Panel:** Settings that guide [[Training]].
*🔧 **Tuned Via:** **Hyperparameter Optimization** techniques.
*📊 **Different From:** **Model Parameters** which are learned from data.
