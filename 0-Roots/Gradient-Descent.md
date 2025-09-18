# Gradient Descent

### One-Liner:
*   **What it is:** The fundamental optimization algorithm used to train machine learning models by iteratively minimizing their error or "loss."

### The Big Picture:
Gradient Descent is the **workhorse** behind almost all of machine learning. It's the algorithm that actually "learns" the best parameters for models like Linear Regression, Neural Networks, and many others by finding the lowest point in a "valley" of error.

### How it Works (The Core Idea):
1.  **Calculate Gradient:** The algorithm measures the current error of the model and calculates the "gradient" – which way is downhill on the error curve?
2.  **Take a Step:** It then adjusts the model's parameters slightly in the direction that reduces the error the most (the steepest downhill direction).
3.  **Repeat:** It repeats this process until it (hopefully) reaches the bottom of the valley, where the error is minimized.

### Why it Matters:
It is the core of how models learn from data. Without it, we wouldn't be able to automatically find the best patterns in complex datasets.

### A Simple Analogy:
**Finding the lowest point in a foggy valley.**
*   You can only feel the ground under your feet.
*   You take a small step in the direction that feels the steepest downhill.
*   You keep taking small steps like this until the ground is flat all around you – you've found the bottom!

### Real-World Examples:
*   Training a **Linear Regression** model to find the best-fit line.
*   Training a **Neural Network** to recognize images or translate languages.
*   It is the "G" and "D" in **GANs** (Generative Adversarial Networks).

---
*🌳 **The Engine:** Powers the [[Training]] process for most ML models.
*📉 **Minimizes:** The [[Loss Function]].
*⚙️ **A Key Hyperparameter:** The size of the step is the **Learning Rate**.
