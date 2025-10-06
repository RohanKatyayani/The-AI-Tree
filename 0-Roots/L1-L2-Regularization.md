# L1 and L2 Regularization

### One-Liner:
*   **What it is:** Two common regularization techniques that add penalty terms to the loss function to constrain model weights, with L1 encouraging sparsity and L2 preventing large weights.

### The Big Picture:
L1 and L2 are the **weight watchers** of machine learning. They gently guide the model toward simpler solutions by penalizing complexity directly in the optimization objective.

### How it Works (The Core Idea):
Both methods add a penalty term to the loss function:
- **L1 (Lasso):** Penalizes the absolute value of weights (∑|w|). Tends to drive some weights exactly to zero, performing feature selection.
- **L2 (Ridge):** Penalizes the squared value of weights (∑w²). Tends to shrink all weights uniformly but rarely to exactly zero.

### Why it Matters:
They provide a mathematically elegant way to control model complexity and prevent overfitting. L1 is great for feature selection, while L2 is excellent for handling correlated features.

### A Simple Analogy:
**Packing for a trip with different philosophies.**
*   **No Regularization:** Bring everything you might possibly need (overpacking).
*   **L1 Regularization:** Be ruthless - if you haven't used something in a while, leave it behind (sparse packing, feature selection).
*   **L2 Regularization:** Bring everything but in travel-sized versions (compact but complete packing).

### Real-World Examples:
*   **L1:** Gene selection in bioinformatics where you want to identify the few relevant genes among thousands.
*   **L2:** Image recognition where many pixels contribute slightly to the prediction.
*   **Elastic Net:** Combining both L1 and L2 for balanced regularization.

---
*🌳 **Parent Concept:** Specific [[Regularization]] techniques.
*📉 **The Method:** **Adding penalty terms** to the [[Loss Function]].
*⚖️ **L1 vs L2:** **Sparsity** vs **Weight shrinkage**.
*🎯 **The Result:** **Simpler models** that generalize better.
