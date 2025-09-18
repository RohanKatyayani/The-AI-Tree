# Loss Function (or Cost Function)

### One-Liner:
*   **What it is:** A function that measures how wrong a machine learning model's predictions are compared to the actual truth. It quantifies the model's error.

### The Big Picture:
The Loss Function is the **scoreboard** for model training. It's the objective that algorithms like Gradient Descent are trying to minimize. A lower loss means a better, more accurate model.

### How it Works (The Core Idea):
For every prediction the model makes, the loss function calculates a penalty (a number) based on how far off the prediction was. The goal of the entire training process is to find the model parameters that result in the smallest possible average loss across all training examples.

### Why it Matters:
You can't improve what you can't measure. The loss function provides the crucial feedback needed to steer the model in the right direction during training.

### A Simple Analogy:
**Playing darts.**
*   The **Loss Function** is the score you get based on how far your dart is from the bullseye.
*   A dart in the bullseye has a low loss (a perfect score of 0).
*   A dart on the outer edge has a high loss (a bad score).
*   Your goal (like Gradient Descent's) is to adjust your throwing technique to minimize your average score across many throws.

### Real-World Examples:
*   **Mean Squared Error:** A common loss function for regression tasks (e.g., predicting house prices). It heavily penalizes large errors.
*   **Cross-Entropy Loss:** A common loss function for classification tasks (e.g., identifying spam). It measures the difference between predicted probabilities and actual labels.

---
*🌳 **The Guide:** Provides the target for [[Gradient Descent]] to minimize.
*🎯 **The Goal:** The entire [[Training]] process aims to reduce this.
*📊 **Specific Types:** Includes [[Mean Squared Error]] and [[Cross-Entropy Loss]].
