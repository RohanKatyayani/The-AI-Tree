# Optimizers

### One-Liner:
*   **What it is:** The algorithm that determines *how* a neural network updates its parameters (weights and biases) during training to minimize the loss function.

### The Big Picture:
Optimizers are the **navigators** of the training process. While Gradient Descent provides the basic direction (downhill), optimizers decide the *strategy* for the journey—how big of steps to take, how to handle rough terrain, and how to avoid getting stuck.

### How it Works (The Core Idea):
An optimizer takes the gradients (direction of steepest descent) computed by backpropagation and uses them to update the model's parameters. Different optimizers use different strategies to make this process faster and more reliable.

### Why it Matters:
The choice of optimizer can dramatically affect how quickly a model trains, whether it converges to a good solution, and how well it generalizes. It's a key hyperparameter in any deep learning project.

### A Simple Analogy:
**Hiking down a mountain to find the lowest valley.**
*   **Basic Gradient Descent:** Always walk straight downhill, taking steps of the exact same size. You might get stuck in a small ditch (local minimum) or take forever on a flat plain.
*   **Advanced Optimizer (like Adam):** Is like a smart hiker with momentum and terrain awareness. They might build up speed on slopes, adjust step size for different terrains, and sometimes even "jump" out of small ditches to find the true lowest valley.

### Common Optimizers & Real-World Examples:
*   **SGD (Stochastic Gradient Descent):** The fundamental, reliable workhorse.
*   **Adam:** The most popular modern optimizer, combining ideas of momentum and adaptive learning rates. Used in training most LLMs and vision models.
*   **RMSprop:** Effective for recurrent neural networks and noisy problems.

---
*🌳 **The Navigator:** Guides the [[Gradient Descent]] process.
*🎯 **The Goal:** To efficiently minimize the [[Loss Function]].
*⚙️ **A Key Hyperparameter:** The choice of optimizer is crucial for training success.
*🚀 **Enables:** Faster convergence and better final performance.
