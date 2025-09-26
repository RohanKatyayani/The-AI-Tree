# Pruning

### One-Liner:
*   **What it is:** A model compression technique that removes unnecessary weights, neurons, or even entire layers from a neural network that contribute little to its output.

### The Big Picture:
Pruning is like **sculpting** a model. It starts with a large, over-parameterized network and carefully carves away the redundant parts, leaving a leaner, more efficient model that retains the core functionality.

### How it Works (The Core Idea):
The algorithm identifies connections (weights) or neurons that have very little impact on the final prediction—for example, weights with values very close to zero. These are then "pruned" (set to zero or removed entirely). The model is often then fine-tuned to recover any minor loss in accuracy.

### Why it Matters:
It can reduce the size of a model by 90% or more with minimal accuracy loss. This leads to faster inference, lower memory usage, and reduced energy consumption, which is critical for edge devices.

### A Simple Analogy:
**Pruning a bonsai tree or a rose bush.**
*   A large, untrained neural network is like a wild, overgrown bush with many weak, crossing, and dead branches.
*   **Pruning** is the careful process of cutting away the deadwood and weak branches that don't contribute to the tree's beautiful shape.
*   The result is a smaller, healthier, and more elegant tree (model) that is stronger and more focused on its essential structure.

### Real-World Examples:
*   Pruning a **large image classification model** so it can run on a security camera with limited processing power.
*   Reducing the size of a **language model** for use in a mobile keyboard app to save battery life.
*   Creating sparse models that are faster to run on specialized hardware designed for sparse computations.

---
*🌳 **Parent Concept:** A key technique for [[Model Compression]].
*✂️ **The Mechanism:** Removing unimportant weights or neurons.
*🎯 **The Goal:** To create a **sparse network** that is computationally cheaper.
*🔁 **Often Followed By:** Fine-tuning to recover accuracy.
