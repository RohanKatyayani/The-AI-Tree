# Decision Trees

### One-Liner:
*   **What it is:** A versatile supervised learning algorithm that makes predictions by asking a series of yes/no questions about the input features, forming a tree-like model.

### The Big Picture:
Decision Trees are a highly intuitive and visual **leaf** on the **Supervised Learning** branch. They can be used for both **classification** and **regression** tasks and are the building blocks for more powerful ensemble methods like Random Forests.

### How it Works (The Core Idea):
The algorithm builds a tree by choosing the feature that best splits the data at each step (e.g., "Is the age greater than 30?"). It continues this process, creating branches until it reaches a prediction (a leaf node). It mimics human decision-making.

### Why it Matters:
They are easy to understand and interpret. You can literally visualize the entire decision process. They also require little data preprocessing (e.g., no need for feature scaling).

### A Simple Analogy:
**Diagnosing a car that won't start.**
*   **Question 1:** Does the engine make a clicking sound? (Yes/No)
    *   **If Yes:** -> Question 2: Are the headlights dim? -> Could be a dead battery.
    *   **If No:** -> Question 3: Does the engine crank? -> Could be out of fuel.
This series of questions forms a "decision tree" to diagnose the problem.

### Real-World Examples:
*   **Banking:** Deciding to approve a loan based on income, credit score, and debt.
*   **Medicine:** A flow chart for diagnosing a disease based on symptoms.
*   **Business:** Classifying customers for targeted marketing campaigns.

---
*🌳 **Parent Branch:** [[Supervised Learning]]
*🌲 **The Building Block:** Forms the basis for powerful algorithms like [[Random Forest]] and [[Gradient Boosting]].
*🔄 **Versatility:** Can be used for both [[Classification]] and [[Regression]].
*👀 **Key Strength:** Highly interpretable and visual.
