# Principal Component Analysis (PCA)

### One-Liner:
*   **What it is:** A statistical technique that transforms correlated variables into a set of uncorrelated components ordered by how much variance they capture from the data.

### The Big Picture:
PCA is the **variance maximizer** of dimensionality reduction. It finds the "viewing angles" that show the most spread in the data, allowing you to see the big picture while ignoring minor variations.

### How it Works (The Core Idea):
PCA identifies new axes (principal components) in the data:
1.  **First PC:** The direction of maximum variance
2.  **Second PC:** The direction of maximum remaining variance, perpendicular to the first
3.  **And so on...** until all variance is captured
These components are linear combinations of the original features.

### Why it Matters:
It's incredibly effective for removing redundancy, reducing noise, and visualizing high-dimensional data. It's also the foundation for many other techniques.

### A Simple Analogy:
**Photographing a 3D object from the best angles.**
*   You want photos that show the object's most distinctive features.
*   **First photo:** From the front, showing the full shape (most variance)
*   **Second photo:** From the side, showing depth (next most variance)
*   **Third photo:** From above, showing minor details (remaining variance)
*   With just 2-3 photos, someone can understand the 3D object perfectly.

### Real-World Examples:
*   **Face Recognition:** Reducing thousands of pixel dimensions to key "eigenfaces."
*   **Genomics:** Identifying the main patterns across thousands of genes.
*   **Finance:** Finding the dominant market factors driving stock movements.

---
*🌳 **Parent Concept:** A specific [[Dimensionality Reduction]] technique.
*📊 **The Focus:** **Maximum variance preservation**.
*📐 **The Method:** **Orthogonal linear transformations**.
*🎯 **The Result:** **Uncorrelated components** ordered by importance.
