# Random Forest

### One-Liner:
*   **What it is:** An ensemble learning method that operates by constructing a multitude of decision trees at training time and outputting the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### The Big Picture:
Random Forest is the **democratic forest** of machine learning. It creates a "forest" of diverse decision trees and lets them vote on the final prediction, resulting in a model that's more accurate and robust than any single tree.

### How it Works (The Core Idea):
It uses two key techniques:
1.  **Bagging (Bootstrap Aggregating):** Each tree is trained on a random subset of the data.
2.  **Feature Randomness:** Each split in each tree considers only a random subset of features.
This creates diverse, uncorrelated trees that make different errors.

### Why it Matters:
It's remarkably effective out-of-the-box, resistant to overfitting, and provides built-in feature importance measures. It's often the first algorithm to try on structured data problems.

### A Simple Analogy:
**The wisdom of a large, diverse jury.**
*   A **single decision tree** is like one juror who might be biased or make mistakes.
*   A **Random Forest** is like having hundreds of jurors, each:
    - Hearing slightly different evidence (bagging)
    - Focusing on different aspects of the case (feature randomness)
    - The final verdict is based on majority vote, which is much more reliable.

### Real-World Examples:
*   **Predicting customer churn** based on usage patterns and demographics.
*   **Medical diagnosis** combining symptoms, test results, and patient history.
*   **Credit scoring** evaluating loan applications from multiple angles.

---
*🌳 **Parent Concept:** A specific [[Ensemble Methods]] technique.
*🌲 **The Base:** Built from many [[Decision Trees]].
*🔄 **The Strategy:** Uses **Bagging** and **Feature Randomness**.
*🛡️ **The Advantage:** **Reduces overfitting** and provides **feature importance**.
